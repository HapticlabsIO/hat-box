---
parent: Tools
layout: tool
title: Weirding Haptics
year: '2021'
platform:
    - Unity
availability: Available
license: Open Source (AGPL 3)
venue:
    - ACM UIST
use_case:
    - Virtual Reality
    - Prototyping
haptic_category:
    - Vibrotactile
hardware_abstraction: Consumer
device_names:
    - Oculus Touch
body_position:
    - Hand
driving_feature:
    - Time
    - Action
effect_localization: Target-centric
media_support:
    - None
iterative_playback: 'Yes'
design_approaches:
    - DPC
    - Process
interaction_metaphors:
    - Demonstration
connectivity:
    - None
storage:
    - None
image: /assets/tools/weirding-haptics.png
---
Weirding Haptics is a design tool for and within virtual reality environments where vocalizations are mapped to vibration patterns attached to virtual objects.
Vocalizations are recorded and mapped to vibration patterns felt when touching the object.
These patterns can have parameters such as maximum amplitude modulated based on the position or velocity of contact.
Several patterns can be layered over each other to create more complex effects impossible to accomplish through one recording.

For more information on Weirding Haptics, please consult the [UIST'21 paper](https://doi.org/10.1145/3472749.3474797) or the [GitHub repository](https://github.com/darty/wh).
