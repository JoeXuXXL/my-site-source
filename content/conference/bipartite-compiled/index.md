---
title: Quantitative quantum soundness for all bipartite compiled Bell games via the sequential NPA hierarchy

# event: Hugo Blox Builder Conference
# event_url: https://example.org

# location: ''
# address:
#   street: ''
#   city: ''
#   region: ''
#   postcode: ''
#   country: ''

summary: A joint talk given by me and Matilde Baroni at several different venues. My part is on the quantitative quantum soundness for bipartite compiled Bell games, while she talks about asymptotic results for the multipartite cases.
abstract: |
  Compiling Bell games under cryptographic assumptions removes the need for physical separation, enabling tests of nonlocality with a single untrusted device. Beyond preserving quantum advantage, prior results established quantum soundness—no cheating quantum device can beat the original Bell score—quantitatively only for specific bipartite games; later work proved a general but qualitative version under infinitely secured compilation. However, the more practically relevant case of finitely secured compilation remained open. In this talk, we resolve this problem. Specifically, for every bipartite compiled Bell game with a finite-dimensional optimal strategy, we give the first quantitative soundness bounds: any polynomial-time prover’s score is negligibly close to the game’s ideal quantum value. More generally, for all bipartite games we upper-bound compiled scores via a newly formalized, convergent sequential Navascués–Pironio–Acín (NPA) hierarchy, which we fully characterize, including comparisons to the standard NPA and the flatness condition.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-07-17'
# date_end: '2030-06-01T15:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2025-07-17'

authors:
  - admin

tags: [Quantum cryptography]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**myself :D**]()'
  focal_point: Right

links:
  - type: slides
    url: compiled_bell_IWOTA_joint.pdf
  # - type: video
  #   url: https://pirsa.org/24090110
  # - type: poster
  #   url: bipartite_compiled_poster.pdf
  - type: website
    url: https://xiangling-xu.github.io/publication/klep-2025-quantitativequantumsoundnessbipartite/

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

<div class="talk-multi-venues">

<style>
/* Smaller inline footnote refs (beats .prose defaults) */
.prose .talk-multi-venues sup.footnote-ref,
.prose .talk-multi-venues sup > a[role="doc-noteref"],
.prose .talk-multi-venues a[role="doc-noteref"] {
  font-size: 0.70em !important;
  line-height: 1;
  text-decoration: none;
}

/* Footnotes list at bottom: smaller + muted */
.prose .talk-multi-venues section.footnotes,
.prose .talk-multi-venues .footnotes {
  font-size: 0.80rem !important;   /* adjust to taste */
  color: #6b7280;                   /* gray-500 */
}
.prose .talk-multi-venues section.footnotes hr,
.prose .talk-multi-venues .footnotes hr { display: none; }

/* tighten just figures you mark with class="tight-cap" */
.prose figure.tight-cap figcaption { margin-top: .25rem !important; }
.prose figure.tight-cap figcaption p { margin: .125rem 0 0 0 !important; }

</style>

<p class="text-sm text-gray-500 dark:text-gray-400">
This talk has been presented at multiple venues. The date above is set to the most recent instance for correct ordering in the Talks list. Materials (slides/poster) are shared with minor venue-specific tweaks.
</p>

### Talks
| Date | Event | Host / Location | Type |
|---|---|---|---|
| 2024-09 | **YQIS25**[^yqis] | ICFO, Castelldefels (ES) | Contributed |
| 2025-07 | **IWOTA 2025**[^iwota] | University of Twente, Twente (NL) | Contributed |
| 2025-06 | **IQC-PCQT-Quantum Saclay Workshop**[^saclay] | Sorbonne University, Paris (FR) | Invited |

<!-- # Poster sessions
| Date | Event | Host / Location |
|---|---|---|
| 2024-11 | **YQIS24**[^yqis] | Inria Paris, Paris (FR) |
| 2024-11 | **GDR TeQ 2024**[^gdr] | Sorbonne University, Paris (FR) | -->

*Also presented at various internal group meetings during research visits.*
---

{{< figure
    class="tight-cap"
    src="iwota2025.jpg"
    alt="IWOTA 2025 at Twente, Netherland"
    caption="Image credit: *IWOTA 2025 at Twente, Netherland*"
    link="iwota2025.jpg"
    width="650"
>}}


[^yqis]: <https://www.icfo.eu/event/4000/8th-international-conference-for-young-quantum-information-scientists-yqis25-/>
[^iwota]: <https://www.utwente.nl/en/iwota2025/>
[^saclay]: <https://project.inria.fr/iqcpcqtqsworkshop/>

</div>
