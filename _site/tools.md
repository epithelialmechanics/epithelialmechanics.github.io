# Thread tools

Three pages that turn a contributor's draft into posted content. All static, all run
entirely in the browser — nothing is uploaded and no login is needed.

| Page | URL | Who uses it |
|---|---|---|
| `submit/` | `/submit/` | **Contributors** — write and check a thread |
| `helper/` | `/helper/` | **Admin** — post the thread |
| `cite/` | `/cite/` | **Admin** — make the daily paper posts |

Only `/submit/` goes in the email to contributors. The other two are unlisted —
not in the site nav, reachable by direct URL.

---

## `/submit/` — for contributors

Send this link with the invitation email.

They draft the thread wherever they like, then fill in one card per post here.
Each card has a post type, the text, a link box, and an optional image.

- **275 characters** for the text of every post. Paper links go in their own box
  and don't count against it.
- The counter matches Bluesky exactly, including emoji and shortened links.
- Post types: introduction, paper post, context/commentary, closing.
  Only paper posts need a link, and only they count toward the 4 research + 1 review minimum.
- Media is required on Post 0 only — JPEG, PNG, GIF, MOV or MP4. Files are checked for format and size in the browser,
  and the page tells them the correct `Post0.jpg`, `Post3.png` … filename.
- The checklist on the right must be all green before they send.

They finish with **Download .txt** and email you that file plus the images.

Drafts save to their own browser, so tell them to keep their word processor
document as the master copy.

---

## `/helper/` — posting the thread

Pick the `.txt` they sent you. It splits into one card per post.

Work down the list: **Copy**, paste into the Bluesky composer, attach the file it
names, add the alt text, then press **+** in the composer for the next post.
Copied posts grey out and a progress bar tracks how far you've got.

Paste rather than retype — Bluesky resolves `@handles` and links on paste, so
mentions actually notify people.

Anything over 300 characters is flagged in red. That should be rare, since the
builder already checked, but a contributor editing the `.txt` by hand can break it.

At the bottom, **Paper links in this thread** gives you every link, deduplicated,
one per line. Copy that straight into `/cite/`.

---

## `/cite/` — the daily paper posts

Paste paper links, one per line — DOIs, `doi.org`, `nature.com`, bioRxiv,
`science.org`, PMC links, most things. Press **Generate**.

For each one you get the finished post: APA citation, the link, and the hashtag,
already trimmed to fit 300 characters. If the author list is too long it shortens
with `…`, always keeping the first authors and the last two. **Copy** puts it on
the clipboard ready for the composer.

Set the hashtag with **Default hashtag**, and override any single row with its own
dropdown. There is no automatic review detection — Crossref doesn't record whether
an article is a review, so guessing it did more harm than good.

Below the cards is a table (title, journal, year, URL, chars, post text) with
**Download CSV** and **Copy for Excel**.

Metadata comes from Crossref. If a row fails, its link is clickable so you can go
and find the DOI yourself, then paste that instead. `cell.com` links are the usual
culprit — they use internal IDs with no DOI in the URL.

---

## The loop, end to end

1. Contributor drafts in Word, fills in `/submit/`, downloads the `.txt`
2. They email you the `.txt` plus the images
3. You open `/helper/`, load the file, and copy the posts into Bluesky one by one
4. You copy the link list from the bottom of `/helper/` into `/cite/`
5. `/cite/` gives you the individual paper posts to schedule over the following days

---

## Notes

- Each page is a single file with no dependencies or build step. Edit and commit.
- The scripts are wrapped in `{% raw %}` so Jekyll's Liquid leaves them alone.
  Keep that wrapper if you edit the JavaScript.
- Page titles and descriptions come from the front matter and are rendered by
  `_layouts/default.html`, so the pages inherit the site nav, fonts and dark mode.
- `/submit/` and `/cite/` widen the body grid beyond the site's 45rem because a
  form with a sidebar doesn't fit. That override is scoped to those pages.
- `/cite/` is the only page that talks to the internet, and only to Crossref and NCBI.
