---
layout: page
---
# *TerraBytes - Towards global datasets and models for Earth Observation*
{% include figure.html img="organizers.jpg" alt="sponsors" width="150%" %}
---
### About the workshop

Earth Observation (EO) presents unique challenges and opportunities that set it apart from other fields of machine learning
(ML) and computer vision (CV) (Rolf et al., 2024). EO data is abundant, repeatedly covering a large but limited environment:
our planet. The colocation and evolution of these observations is a rich, emergent source of information, of multimodal and
multitemporal nature. However, due to both local and global changes, especially climate change, the statistical distribution
of EO data is inherently non-stationary (Tarasiou et al., 2023). These properties break some of the usual assumptions of
ML, and EO data require special care for data handling and modeling (Mai et al., 2022). In addition, current EO datasets
are sampled with spatio-temporal biases. Some areas, e.g., the global South, are strongly under-represented within EO
datasets (Cornebise et al., 2022). In optical imagery, cloud cover is undesirable, thus leading to datasets that remove cloudy
images at the risk of biasing their geographical coverage (Tiede et al., 2021). Addressing these distributional biases is of
primary importance, as they have an impact on the performance and reliability of models for downstream applications in
ecology, geosciences, agriculture, urban planning, etc. (Kattenborn et al., 2022).

TerraBytes is an initiative to address these challenges. At the intersection of data curation, data archiving, and representation learning, this workshop will
foster a holistic discussion covering major steps in the EO from downlinked satellite data, training paradigms to downstream applications. 

### Call for submissions
We invite submissions on the following topics:

* Large-scale Earth observation datasets and benchmarks:
  - curation of new large-scale vision datasets for EO,
  - augmentation techniques for EO data and their impact on learning, data traceability and expansion of existing datasets,
  - re-use and adoption of existing datasets in new scenarios,
  - impact of training data quality and size on downstream tasks under domain shifts.
* Efficient and continual representation learning for remote sensing:
  - weakly and self-supervised learning for EO data,
  - domain adaptation strategies to deal with temporal, geographical or sensor gaps,
  - continual and online learning, to update models when facing distribution shifts,
  - active learning and reinforcement learning.
* Real-world applications:
  - early detection, monitoring and assessment of disasters e.g. floods, landslides, wildfires,
  - large-scale Land Cover and Land Use mapping,
  - 2D and 3D change detection in urban and rural areas,
  - estimation of biophysical parameters (biomass, biodiversity, soil stress, etc.).

#### Submission process

Submission to the TerraBytes workshop is **double-blind**. The workshop accepts short research papers (4 pages, excluding references) and full-length papers (8 pages, excluding references). Authors are required to follow standard ICML paper format ([LaTeX style files](https://media.icml.cc/Conferences/ICML2025/Styles/icml2025.zip)).

** We also accept datasets and research papers already published in the last 6 months. Please submit such works as a summarized four-page short paper. 

All submissions should be submitted through [Open-Review](https://openreview.net/group?id=ICML.cc/2025/Conference#tab-recent-activity) before the deadline (see important dates below). 
The workshop does not publish proceedings under ICML. However, we are looking into publishing a special issue comprised of the accepted full-length papers, either in [DMLR](https://data.mlr.press/) or [JSTAR](https://ieeexplore-ieee-org.focus.lib.kth.se/xpl/RecentIssue.jsp?punumber=4609443) journal.
All submissions will be reviewed by at least two reviewers. All papers will be presented during a dedicated poster session. Full-length papers and selected short papers will also be presented as spotlight presentations throughout the day.

It is expected that at least one author of each accepted paper will register for the workshop and present the article during the event. Online presentations will be considered for presenters that are not allowed to come, e.g. to visa or personal constraints. If you have any questions, do not hesitate to contact the organizers (see contacts below).

#### Important dates
---
* Papers submission deadline: **May 16th, 2025**
* Papers acceptance notification: June 6, 2025
* Workshop: July 18/19, 2025

#### Program
---

**Morning session**

* 9:00-9:10: Opening remarks
* 9:10-9:50: Keynote: AI for Earth Observation
* 9:50-10:10: Paper spotlights (best short papers)
* Coffe break
* 10:40-11:20: Keynote: EO data curation and archiving
* 11:20-12:00: Paper spotlights 1

**Afternoon session**

* 13:15-14:00: Paper spotlights 2
* 14:00-15:00: Poster session
* Coffe break
* 15:30-16:10: Keynote: Biases and diversity in ML for EO
* 16:10-17:10: Panel session: Towards global models
* 17:10-17:20: Closing remarks

### Organizers
---
* [Nicolas Audebert, IGN, CNAM](https://nicolas.audebert.at)
* [Hossein Azizpour, KTH Royal Institute of Technology](https://www.csc.kth.se/~azizpour/)
* [Valentin Barriere, University of Chile](https://www.copernicuslac-chile.eu/en/persona/valentin-barriere/)
* [Javiera Castillo Navarro, CNAM](https://javi-castillo.github.io/)
* [Mikolaj Czerkawski, Asterisk Lab](https://mikonvergence.github.io/)
* [Heng Fang, KTH Royal Institute of Technology](https://hfangcat.github.io/)
* [Alistair Francis, Asterisk Lab](https://asterisk.coop/)
* [Valerio Marsocci, ESA Phi Lab](https://sites.google.com/uniroma1.it/valeriomarsocci)
* [Andrea Nascetti, KTH Royal Institute of Technology](https://www.kth.se/profile/nascetti)
* [Ritu Yadav, KTH Royal Institute of Technology](https://www.linkedin.com/in/ritu-yadav-5a810158/)

**Primary Contacts**: Valerio Marsocci (valerio.marsocci@esa.int), Nicolas Audebert (nicolas.audebert@ign.fr)


### Program Committee
---

To be announced.

### Sponsors
------

We thank CopernicusLAC for their sponsorship of this event.

{% include figure.html img="logo_copernicuslac_chile.png" alt="CopernicusLAC Chile sponsor" width="50%" %}
{% include figure.html img="IADF.png" alt="IEEE IADF sponsor" width="50%" %}

