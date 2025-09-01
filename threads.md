---
layout: default
title: Threads
permalink: /threads/
images:
  - {path: /assets/threads/20230814.png, caption: "About effect of curvature on epithelial tissue ", description: "by Nimesh Chahare\n <a href="https://bsky.app/profile/epimechfc.bsky.social/post/3lkhr4ctox22m">Bluesky</a>"}
  - {path: /assets/threads/20230814.png, caption: "About effect of curvature on epithelial tissue ", description: "by Nimesh Chahare\n <a href="https://bsky.app/profile/epimechfc.bsky.social/post/3lkhr4ctox22m">Bluesky</a>"}

---






<div class="gallery">
  {% for image in page.images %}
    <div class="gallery-item">
      <a href="{{ site.baseurl }}{{ image.path }}">
        <img src="{{ site.baseurl }}{{ image.path }}"/>
      </a>
      <div class="image-caption">{{ image.caption }}</div>
      <div class="image-description">{{ image.description | newline_to_br }}</div>
    </div>
  {% endfor %}
</div>

<style>
  .gallery {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
    max-width: 800px;
    margin: 0 auto;
  }
  
  .gallery-item {
    overflow: hidden;
    text-align: center;
  }
  
  .gallery-item img {
    width: 100%;
    height: auto;
    aspect-ratio: 1/1;
    object-fit: cover;
    transition: transform 0.5s ease-in-out;
  }
  
  .gallery-item:hover img {
    transform: scale(1.1);
  }
  
  .image-caption {
    margin-top: 10px;
    font-size: 0.9em;
    color: #666;
  }
</style>




<!--

<script async src="https://embed.bsky.app/static/embed.js" charset="utf-8"></script>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lkhr4ctox22m" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lhniocktj22n" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lfyyxwqru22l" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lfjqw42hot2e" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lh3x5xxs322s" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lpyry4hik22m" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lm2lnm2aks2c" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3kg7fsmww2k2s" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lpfylchpqs2e" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3ldsjjhtbqk2i" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3ljce2nk55c23" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lkz6aaiymk2g" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3liqorp2s7s27" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3loaupdehud2w" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lcqpeja7xc2a" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lrnktl6edk2s" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3ls3wkzr5os2d" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lvffg7wcgs25" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3ltszpeucir2b" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lb4x74fl222a" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lcaajuncns2u" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3ldbihhb3ns2z" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lgndug7cek26" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3libnuwdaqk26" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3ljwgtshjhk2i" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lllen63hxs2s" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lna4yoorbk2p" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lovjbjgagc2l" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lr3c5eoyd22p" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lsq2ypalhs2p" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3luevq5azf62i" data-bluesky-embed-color-mode="system">
</blockquote>

<blockquote 
class="bluesky-embed" 
data-bluesky-uri="at://did:plc:nilglqv27cobounbak6u24cl/app.bsky.feed.post/3lvzpfvnu3k2e" data-bluesky-embed-color-mode="system">
</blockquote>

-->









































