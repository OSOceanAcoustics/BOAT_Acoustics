(conceptual)=
# Conceptual framework

In this set of notebooks, we will focus on getting a solid conceptual level of understanding of how we can decompose an ocean acoustics problem into multiple pieces that can be considered separately to gain a holistic picture of the problem.


## Learning goals

Taking a systems approach to understand ocean acoustics problems, our learning goals are to be able to:
1. Identify the components of the system underlying the research problem you are working on
2. Identify the relationships of difference components in the system
3. Determine which components are knonwn and unknown
4. Understand what is possible to achieve when trying to characterize the unknowns
5. Identify caveats in the measurement or inference/estimation process in the system




## Overview: motivating examples

<!-- Description of scenarios without using the sonar equation first -->

Let's start with an overview of general ocean acoustics problems with two motivating examples.
For the fun and the importance of how this example encompasses the interdisciplinary nature of ocean acoustics, let's use the lives of Orcas, or or killer whales (_Orcinus orca_), to guide our exploration. In the example and follow up expansions later on this page, you will notice how the physics of sound, the biology of the whales and fish, the ocean environments, and our instruments all play a role in understanding the problem.

We will also briefly introduce other examples of how the elements we consider here in ocean acoustics are related to our daily lives.


(conceptual-overview-orca)=
### How do we study the life of an Orca?
Killer whales are toothed whales (odontocetes) that use sounds to communicate with each other and find food in the ocean.

- Listening for killer whales using hydrophones to know where and who (which "pod") has shown up
- "Resident" killer whales
    - typically hang out in coastal waters primarily eat fish, such as salmon.
    - They use their biological sonar system - echolocation - to detect, track, and then catch fish.
    - Explain echolocation
- "Transient" killer whales
    - primarily eat pinnipeds, like seals
    - seals can hear pretty well, so the killer whales listen for vocalization made by seals to find them, before homing in using echolocation
- other examples
    - blue whales communicate across ocean basin
    - humpback whales cultural transmission of call units


(conceptual-overview-human)=
### How are these related to our daily lives?
- Human senses
    - humans rely predominantly on vision to navigate the world
    - however listening is an important sensory modality for us and often bring powerful experiences
    - nevertheless, some unsighted humans have developed the ability to echolocate, just like the killer whales
- Technology that uses similar principles
    - radar
        - uses backscatter (EM energy bounced off from objects) to sense the environment
        - weather patterns (clouds, rain, snow, etc)
        - bird migration
    - medical ultrasound
        - non-invasive imaging of the interior of human body



## The mighty Sonar Equation

- Sonar equation: RL = SL + 2 TL + TS
- what are these terms? (conceptual descriptions of each term)
    - RL: receive level
    - SL: source level
    - TL: transmission loss
        - sound travel takes time, the medium matters (air vs water)
    - TS: target strength
- Diagram for the connection between all the components
- Two examples (with pictures!) consisting of the terms (some are known, some are unknown)
    1. killer whale hunting for fish
        - goal of analysis: are these fish salmon or herring?
        - assumptions: no multipath
    2. humans use hydrophones to listen for killer whales
        - goal of analysis: how far are the whales?
        - assumptions: constant sound speed profile/absorption
- Goal of analysis
    - are these fish salmon or herring?



## What are decibels, and why do we use them?
- General discussion of decibels
- How sound “looks” like – find some nice websites (google famous sounds?)




## How are these related to your own research?

### Exercise
1. How do we use echosounder to probe the environment?
    - what are the components in the sonar equation this maps to?
    - identify at least one possible research question can be answered from echosounder experiment and at least
    - identify at least one caveat associated with the approach
2. Mapping your research project onto the sonar equation
    - discuss which component your work falls into
    - what are the caveats?
