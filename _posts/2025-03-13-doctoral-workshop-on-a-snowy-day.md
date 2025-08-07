---
title: 'Doctoral workshop on a snowy day'
date: 2025-03-13
permalink: /posts/2025/03/doctoral-workshop-on-a-snowy-day/
author_profile: false
related: false
tags:
  - research
  - life
---
In mid-March, my Doctoral school, IAEM (Informatique, Automatique, Electronique-Electrotechnique, Mathématiques), organized a "Review" day for doctoral students starting their second year. The main goals were to create an opportunity for Doctorants, who have started their thesis for more than one year, to present their work so far, and also connect people in relevant fields. As part of the event, they were asked to present a poster summarizing the research topic, initial results, and the outlook. In addition, a short presentation on the research topic was also required. I, of course, was not an exception.

Honestly, I felt quite uninterested before the event, mostly because the project I was working on had too many things to do and those were the things I didn't really like from partners' requirements. I even forgot the day of the poster submission deadline and only had one day to finish and send it to doctoral school. Anyway, order from École Doctorale, can't get away from that.

## The workshop
Most of the research topics came from people of my lab, CRAN, and focused on Control Theory, which is one of the fields I really enjoyed during undergrad and planned to pursue this direction if it was not for the PhD position here. A lot of interesting topics appeared in the list, including: System identification for aircrafts, observer for autonomous vehicles and RL-based control. Shamefully, I’ve almost forgotten everything I once knew in this field. The only thing right then I could ask those students who were working in Control was about the project they were working on and how they could apply their thesis in real-world scenarios.

However, it turned out not to be completely meaningless to come there. Safety RL-based control might be the most interesting work to me, maybe partly because it was related to my topic, at least about the RL aspect. Concretely, traditional RL learns by *trial and error*, that’s fine in games or simulations, but in the real world, trial and error could be dangerous, for examples:
> - Industrial machines operate in environments where unsafe maintenance actions can cause damage.
> - In autonomous driving, a poor decision in ECU could cause a crash.
> - A robotic manipulator that learns to pick fragile items may apply too much force and break them.

Industries like aviation, automotive, or manufacturing in general have strict safety standards, therefore, any AI-based (in general) decision making system used in these sectors must guarantee safety regulation. I tried to relate this to RL-based predictive maintenance, which is my current topic, and it really gave me some ideas.

In addition, in this workshop, I also heard about a topic about Federated Learning using Game Theory to optimize the model in central server. I didn't really know much about the Federated Learning part, but I could see some similarities between Game Theory and RL. The difference may lie in their approach to decision-making: game theory analyzes strategic interactions among multiple rational agents in *known environments*, while RL focuses on how an agent learns optimal policy through trial and error in often *unknown or dynamic* environments.

And by chance, I met a Vietnamese guy in this event. He was also working in Control sector and focused on autonomous vehicles.

<div style="text-align: center;">
  <img src="/images/doctoral-workshop-on-a-snowy-day/IMG_4469.jpg" alt="Descriptive Alt Text" width="500">
  <figcaption>My poster</figcaption>
</div>

## The snowfamily
The workshop unexpectedly took place on a day of heavy snowfall. According to Martin, one of my labmates as well as an old flatmate who also joined the event, this rarely occurs in March. It was also my first time to see such an amount of snow with my own eyes.
<div style="text-align: center;">
  <img src="/images/doctoral-workshop-on-a-snowy-day/IMG_4465.jpg" alt="Descriptive Alt Text" width="500">
</div>
After a quick lunch at Crous Resto, under freezing weather, Martin taught me how to build a snowman even though I was only wearing light clothes. Unlike what I saw in movies, building a snowman was probably much harder than I expected, mainly due to the fact I have no hand gloves and my hands turned red from trying to pack the snow blocks together. On the way back to the next section of the workshop, we came across a snowwoman built by some students in the campus. We also received a message about the snowboy made by my labmates in CRAN.
<div style="text-align: center;">
  <img src="/images/doctoral-workshop-on-a-snowy-day/IMG_4461.jpg" alt="Descriptive Alt Text" width="500">
</div>
<br>
<div style="text-align: center;">
  <img src="/images/doctoral-workshop-on-a-snowy-day/IMG_4467.jpg" alt="Descriptive Alt Text" width="500">
</div>
<br>
<div style="text-align: center;">
  <img src="/images/doctoral-workshop-on-a-snowy-day/snowboy.JPG" alt="Descriptive Alt Text" width="500">
</div>

## Remarks
* The workshop occurred as scheduled with a total of 16 representations, the topic was covered the most might be Control.
* Most of the talks were presented in French, and I found it quite difficult to keep track of them. I felt like it was mandatory for me to have a "systematic" plan for studying French as soon as possible.
* The Crous here was different from those in other campuses that I tried before, still the same price but the main disks were mostly cold food, and it seemed there was just one person who handled the payment.
* I did not know what happened to my snowman afterward, but according to Martin, people would normally give it a high kick.

## Next steps
As I mentioned, AI-based maintenance decision making approach must guarantee safety, actually not only safety but also take into account the states of the system when it changes over time in general in order to minize downtime for RMS (Reconfigurable Manufacturing Systems). In the context of RL, this could include reasoning capabilities with an aim to embedding knowledge about system constraints. This enables the algorithms to cope with such changes, which can be effective in decision support systems where complex maintenance decision making is required (enhance adaptability). One of the promising methods is to integrate RL and Ontology, or GNNs, or PINNs, and I am still working on these. This will be the next phase in my thesis.
<!-- <div style="text-align: center;">
  <img src="/images/doctoral-workshop-on-a-snowy-day/IMG_4458.jpg" alt="Descriptive Alt Text" width="500">
  <figcaption>I need a haircut</figcaption>
</div> -->