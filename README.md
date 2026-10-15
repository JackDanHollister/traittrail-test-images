# TraitTrail mixed specimen test set — v1

Gallery: https://jackdanhollister.github.io/traittrail-test-images/

Repository: https://github.com/JackDanHollister/traittrail-test-images

The definitive fixed input selection for manual TraitTrail testing: **16 images
in 11 source groups**, mixing pinned insects, a shell, a mounted white butterfly,
striped beetles, and six catalogue butterflies. Five scanning sessions each
provide two genuinely different camera views. Scan subjects across sessions are
not independently identified; group counts are not a biological sample size.

Use the numbered originals in `images/` or browse the gallery in `index.html`. All original image bytes are unchanged; hashes and dimensions are
in [manifest.json](manifest.json). Thumbnails are resized previews,
not test inputs. Keep this v1 unchanged so others can run the same inputs.

## Using the set

1. Download and unpack `traittrail-test-images-v1.zip`.
2. In TraitTrail Studio, Examples → Test image set → Use for analysis loads an
   original image. Alternatively choose a file under `images/` in Analyse.
3. Select your own local model or paid API and press Analyse image explicitly.
4. Save results next to that group's images using distinct filenames per run.
   Record input ID/hash, model, prompt, settings, output, validation errors and
   human review. Use exact input IDs when discussing a failure.
5. Collection graph needs saved results as well as images. This input-only ZIP
   deliberately supplies no expected answers or model-generated truth labels.

Opening or downloading images never runs a model. Studio currently analyses one
image per request; paired views are separate test cases, not automatic combined
inference. A shell is outside the insect pilot: use it to check conservative
unknown/not-applicable behavior, not to measure shell-feature accuracy.

## Coverage

| tt-v1-01 | Pinned insect · long antennae | oblique overview | [image](images/insect-01/view-01.png) |
| tt-v1-02 | Pinned insect · long antennae | side view | [image](images/insect-01/view-02.png) |
| tt-v1-03 | Shell | side view | [image](images/shell-01/view-01.png) |
| tt-v1-04 | Shell | oblique overview | [image](images/shell-01/view-02.png) |
| tt-v1-05 | Mounted white butterfly | spread-wing oblique view | [image](images/butterfly-01/view-01.png) |
| tt-v1-06 | Mounted white butterfly | edge-on side view | [image](images/butterfly-01/view-02.png) |
| tt-v1-07 | Striped beetle · scan 4 | front-oblique view | [image](images/beetle-01/view-01.png) |
| tt-v1-08 | Striped beetle · scan 4 | top-oblique view | [image](images/beetle-01/view-02.png) |
| tt-v1-09 | Striped beetle · scan 5 | top-oblique view | [image](images/beetle-02/view-01.png) |
| tt-v1-10 | Striped beetle · scan 5 | side view | [image](images/beetle-02/view-02.png) |
| tt-v1-11 | Aglais io · LM00125 | spread-wing dorsal view | [image](images/butterfly-02/view-01.jpg) |
| tt-v1-12 | Aglais io · LM00124 | spread-wing dorsal view | [image](images/butterfly-03/view-01.jpg) |
| tt-v1-13 | Aricia artaxerxes · BMNHE_1387525 | spread-wing dorsal view | [image](images/butterfly-04/view-01.jpg) |
| tt-v1-14 | Pieris brassicae · BMNHE_1126699 | spread-wing dorsal view | [image](images/butterfly-05/view-01.jpg) |
| tt-v1-15 | Polyommatus icarus · BMNHE_1297421 | spread-wing dorsal view | [image](images/butterfly-06/view-01.jpg) |
| tt-v1-16 | Polygonia c-album · BMNHE_1061902 | spread-wing dorsal view | [image](images/butterfly-07/view-01.jpg) |

The set includes side/edge-on views with occlusion, mounting pins/labels,
spread wings, different colour/patterns, low-resolution crops, naturally irregular
wing margins and possible appendage/wing damage. Damage notes are selection
observations, not expert-confirmed labels. Do not copy species/condition notes
into model prompts as expected answers. No location claims are made.

## Image credits and reuse

- Scanner images tt-v1-01–10: photographs by **Jack Dan Hollister**, of specimens
  including museum specimens. Jack confirmed he took the photographs and asked
  for a public test set on 2026-10-15. Permission is recorded for inclusion,
  download and testing in this set; a general CC licence is not inferred.
  Credit Jack and preserve this notice. Specimen ownership and image authorship
  are distinct; museum endorsement and a specimen institution are not asserted.
- Peacock butterflies tt-v1-11–12: **Lauri Mällo / PlutoF**, CC BY 4.0.
- Museum butterfly crops tt-v1-13–16: **The Trustees of the Natural History
  Museum, London**, CC BY 4.0. These are existing crops, not full-resolution
  originals. No additional sharpening or generative modification was made.
- [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) requires attribution,
  a licence link and an indication of changes. Per-image source/media links,
  credits, changes and public GBIF media-licence records are included in the
  manifest and `sources/`. This project is not endorsed by the museums/publishers.

Original source archives: JackDanHollister/openscan-specimen-lab and
JackDanHollister/traittrail-capture. No model outputs, API keys, private account
records or unrelated project files are in this download. Source occurrence
records are reduced to media provenance; precise collection locations omitted.
