IMAGE DROP-IN SLOTS
===================

Drop your images into this folder using the exact filenames below and they
will appear automatically in the passport (replace the dashed placeholder
boxes in index.html).

  planter-wall.jpg   — hero photo of the finished planter wall  (used by index.html)
  hex-planter.jpg    — hero photo of the hex planter            (used by planter-0143.html)
  pollinators.jpg    — optional: planting / bees / pollinator photo (used by both)

  Landscape or portrait both work for the hero slot — see below.

To show an image instead of a placeholder box, find the matching
<div class="img-slot wide"> ... </div> in the <header> and replace the
whole block with:

  <img src="assets/images/planter-wall.jpg"
       alt="The Sharrow Vale community planter wall"
       class="hero-photo" />

The "hero-photo" class (defined near the top of the file, in the
"4. IMAGE PLACEHOLDERS" CSS section) has no fixed aspect ratio, so a
portrait photo won't get squashed or oddly cropped like it would in the
dashed placeholder box — it just caps the height so a tall photo doesn't
take over the whole screen.

For the smaller, optional image slots further down the page (e.g. the
wildlife/pollinator photo), the placeholder box is fine to keep, or you
can swap it the same way — just drop the "wide" class from the <img> if
you want it full-height too.

Tips
----
- Keep files reasonably small (< 400 KB) so the page loads fast over mobile data.
- JPG for photos, PNG for graphics/logos.
- Maker avatars currently use initials (RT, AB, SH). To use photos instead,
  swap the <span class="avatar">RT</span> for an <img> with the same class.
