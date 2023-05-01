---
layout: splash
header:
  overlay_color: "#5e616c"
  overlay_filter: "0.01"
  overlay_image: assets/images/header_bertha_big.png
  caption: "rviz"
title: 'Bridging the gap between map-based and map-less driving'
excerpt: 'An upcoming IV2023 workshop'
---

This workshop has been accepted at the [34nd IEEE Intelligent Vehicles Symposium (IV)](https://2023.ieee-iv.org/) and will take place on June 4th in Anchorage (Alaska), USA. It addresses researchers who target the deployment of fully automated driving in large-scale, changing environments and have to consider both uncertainty-affected perception and potentially outdated HD maps. The workshop will particularly benefit from the discussions between experts from a wide range of specializations such as behavior and motion planning, prediction, localization and mapping and environmental modelling. Also, we aim for the exchange between developers from academia and industry who have already gained experience with their research vehicles on public roads.

## Tentative Workshop Program
Starting from 8:30 AST, our session will take place in Room 6 at the Egan and Dena’ina convention centers. Please be aware that this is the tenatative time schedule, which may varry until mid May.

|Time (AST)   | Title                  | Speaker |
|--------------|--------------------------------------|-----------|
|8:30 - 8:40 | **Introduction** | [Frank Bieder](https://www.mrt.kit.edu/mitarbeiter_bieder.php) & [Ö. Sahin Tas](https://www.omersahintas.com/) - KIT & FZI, Germany (chairs)
|8:40 - 9:15 | **Vision-based Autonomous Drones** | [Davide Scaramuzza](https://rpg.ifi.uzh.ch/people_scaramuzza.html) - University of Zurich, Switzerland (Keynote)
|9:15 - 9:50 | **Online HD Map Learning for Automated Driving** | [Abhinav Valada](https://rl.uni-freiburg.de/people/valada) - University of Freiburg, Germany (Keynote)
|9:50 - 10:00 | *Coffee break*
|10:00 - 10:35 | **The Role of Maps in Next-Generation Autonomy Stacks** | [Boris Ivanovic](https://www.borisivanovic.com) & [Marco Pavone](https://profiles.stanford.edu/marco-pavone) - Nvidia, Stanford, USA (Keynote)
|10:35 - 11:10 | **Scalable Automated Driving: Fusing Map Perception with Verified HD Maps** | [Richard Fehler ](https://www.linkedin.com/in/richard-fehler/?originalSubdomain=de) - FZI Forschungszentrum Informatik, Germany (Keynote)
|11:10 - 11:20 | *Coffee break*
|11:20 - 11:45 | **Map-Aided Annotation for Pole Base Detection** | [Benjamin Missaoui](https://kit-mrt.github.io/iv2023_workshop_bridging_the_gap) - UTC, France (Accepted paper)
|11:45 - 12:20 | **TBD** | TBD
|12:20 - 12:30 | **Conclusion and Farewell** | [Frank Bieder](https://www.mrt.kit.edu/mitarbeiter_bieder.php) & [Ö. Sahin Tas](https://www.omersahintas.com/) - KIT & FZI, Germany


## Scope and Topics

Today, most automated driving systems still heavily depend on HD maps. They serve as a crucial information source for various safety-critical tasks such as localization, prediction and behavior planning. By not suffering from limited range, affected by occlusions or dependent on favorable weather/light conditions, HD maps extend the foresight of an autonomous system and the robustness towards sensor failure. At the same time HD maps are expensive to acquire and even more expensive to maintain due to frequent changes of the environment. Even with huge efforts in keeping HD maps updated, they stay a snapshot of the past and can obtain outdated information, while being a crucial requirement for map-based driving. In light of this situation, many researchers tackle the future vision of map-less driving: The recent developments in sensor, sensor fusion and machine learning technologies enable a rapidly improving online modeling of the vehicle’s surrounding and on-the-fly estimation of HD map information. While there are already many approaches to predict the surrounding semantics and detect/track objects, current research also addresses the online estimation of higher-level scene understanding layers such as lane topology and traffic rules. 

While both philosophies have their strengths and are frequently considered on their own, they can both benefit from the unique advantages of the respective other. This workshop aims to bring both perspectives closer together and explore how future approaches might consider a hybrid solution. However, the workshop is not limited to this. It welcomes a wide range of contributions regarding map-based and map-less driving solutions.  

The topics of interest of the workshop include, but are not limited to:
- Online fusion of uncertainty-affected on-the-fly map estimation with potentially outdated HD maps.
- Motion and behavior planning considering uncertainty-affected map estimation and/or potentially outdated maps
- Certifiable robustness / validation of map-based, map-less or hybrid systems
- Data sets for learning higher-level scene understanding e.g. lane topologies, traffic rules.
- Leveraging existing HD maps to generate training data for on-the-fly road modeling and map estimation.
- Online road modelling and on-the-fly map estimation for autonomous driving.
- Map change detection, map update and map validation


## Contributions

Authors are encouraged to submit high-quality, original (i.e. not been previously published or accepted for publication in substantially similar form in any peer-reviewed venue including journal, conference or workshop) research via the [submission link](https://edas.info/newPaper.php?c=30459&track=115618). Here the workshop can be selected from a list. Papers should not exceed 6 pages (two additional pages allowed with a fee) and meet the requirements stated in the [IEEE IV 2023 Guidelines](https://2023.ieee-iv.org/paper-submission/). Authors of accepted workshop papers will have their paper published in the conference proceeding. For publication, at least one author needs to be registered for the workshop and the conference and present their work.

Important dates
- **Workshop paper submission deadline**: February 01st, 2023
- **Acceptance/rejection notification**: March 30th, 2023
- **Final workshop paper due**: April 22nd, 2023
- **Workshop day**: June 4th, 2023

## Organizers

The workshop is jointly organized by researchers from Karlsruhe Institute of Technology und FZI Research Institute of Information Technology. The organizers are:

- **Frank Bieder**, PhD Student at FZI Research Center for Information Technology
- **Richard Fehler**, PhD Student at FZI Research Center for Information Technology
- **Fabian Immel**, PhD Student at FZI Research Center for Information Technology
- **Ömer Şahin Taş**, Research Group Leader at FZI Research Center for Information Technology
- **Martin Lauer**, Research Group Leader at Karlsruhe Institute of Technology


