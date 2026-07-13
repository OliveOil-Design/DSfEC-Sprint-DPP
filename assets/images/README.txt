IMAGE DROP-IN SLOTS
===================

Drop your images into this folder using the exact filenames below and they
will appear automatically in the passport (replace the dashed placeholder
boxes in index.html).

  planter-wall.jpg   — hero photo of the finished planter wall  (used by index.html)
  hex-planter.jpg    — hero photo of the hex planter            (used by planter-0143.html)
  pollinators.jpg    — optional: planting / bees / pollinator photo (used by both)

  (Landscape, roughly 16:9, works best for the hero slots.)

To show an image instead of a placeholder box, in index.html replace the
matching <div class="img-slot"> ... </div> with, for example:

  <img src="assets/images/planter-wall.jpg"
       alt="The Sharrow Vale community planter wall"
       style="width:100%;border-radius:12px;display:block" />

Tips
----
- Keep files reasonably small (< 400 KB) so the page loads fast over mobile data.
- JPG for photos, PNG for graphics/logos.
- Maker avatars currently use initials (RT, AB, SH). To use photos instead,
  swap the <span class="avatar">RT</span> for an <img> with the same class.
