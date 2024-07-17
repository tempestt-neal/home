---
title: "Mobile Biometrics"
excerpt: "This research explores behavioral biometric modalities in mobile devices, demonstrating the effectiveness of passive continuous authentication through patterns in application use, Bluetooth and Wi-Fi activity, and communication, with significant findings including improved feature representation, gender-based usage patterns, attack simulations, and novel profiling and ranking techniques.<br/><img src='../images/mobilebiometrics.jpg'>"
collection: portfolio
---

### Project Summary

Commercial mobile devices currently employ point-of-entry (PoE) authentication methods such as face recognition and personal identification numbers. Several studies show that knowledge-based
authenticators are ineffective due to increased memory load, poorly chosen alphanumeric combinations, and repetitive use of passcodes across many applications. PoE and knowledge-based
authenticators are both ineffective throughout sessions of use; once the user is authenticated, the device and its content remain available to the current user. In this research, we explored various data based
on usage of a mobile device as behavioral biometric modalities, including patterns in application use, networking activity (i.e., Bluetooth and Wi-Fi sightings), and communication through calling and text
messaging, which can continuously and passively authenticate a device’s owner.

Significant findings and methods developed throughout this research include:
- We demonstrated the use of association rules as a feature representation for application, Bluetooth, and Wi-Fi data which outperformed previously employed frequency-based features. Our findings
suggest that patterns in application and Bluetooth traffic are more distinct than those in Wi-Fi patterns with up to 91% accuracy. Performance obtained in this study were consistent with
implementations of keystroke dynamics and touch gestures for biometric authentication, a significant indication that passive modalities are as viable as their physical counterparts.
- We provided empirically-supported evidence of gender-based usage patterns, including higher activity levels of female compared to male users in application use and the differentiation between the
two groups based on transitions between sports, navigation, and system-related apps and number of revisitations to apps within sessions.
- We developed temporally-derived replay attack simulations to assess system performance under threatening conditions in which the legitimate user is easily observed or their usage data is remotely
accessed. The intercepted data is then intelligently combined with some level of noise to avoid the replay of an exact copy of legitimate data by an attacker. The attacker’s data thus maintains a level of
similarity with the legitimate data. Our experiments show that our attack models can lead to false positive rates ranging from 30 to 50%, while in some cases, zero-effort attacks lead to much lower,
and thus misleading, error rates.
- We introduced an easily interpretable profiling technique as a feature representation for user-device interaction data that contextualizes mobile device usage patterns. Our experiments show that these
profiles allow better separation of legitimate and impostor behavior. Error rates associated with behavior profiles either improved or were not affected by the amount of data provided for authentication,
while those associated with frequency-based features, which are seen in several research studies, worsened.
- We developed a novel ranking function which quantifies the informativeness of a soft biometric class for search space reduction. The function relies on the rank-1 recognition accuracy for the class, a
score quantifying the permanence of the class, and a cost derived from the ratio of misclassifications to the number of subjects in the soft biometric class.

### Publications
- T. J. Neal, D. L. Woodard and A. D. Striegel, "Mobile device application, Bluetooth, and Wi-Fi usage data as behavioral biometric traits," 2015 IEEE 7th International Conference on Biometrics Theory, Applications and Systems (BTAS), Arlington, VA, USA, 2015, pp. 1-6, doi: 10.1109/BTAS.2015.7358777.
- Neal, Tempestt J., and Damon L. Woodard. "Surveying biometric authentication for mobile device security." Journal of Pattern Recognition Research 1.74-110 (2016): 4.
- T. J. Neal and D. L. Woodard, "Using associative classification to authenticate mobile device users," 2017 IEEE International Joint Conference on Biometrics (IJCB), Denver, CO, USA, 2017, pp. 71-79, doi: 10.1109/BTAS.2017.8272684.
- T. J. Neal and D. L. Woodard, "Spoofing analysis of mobile device data as behavioral biometric modalities," 2017 IEEE International Joint Conference on Biometrics (IJCB), Denver, CO, USA, 2017, pp. 62-70, doi: 10.1109/BTAS.2017.8272683.
- Neal, Tempestt J., Damon L. Woodard, and Aaron D. Striegel. "Mobile device usage data as behavioral biometrics." Mobile Biometrics 3 (2017): 177.
- T. J. Neal and D. L. Woodard, "A gender-specific behavioral analysis of mobile device usage data," 2018 IEEE 4th International Conference on Identity, Security, and Behavior Analysis (ISBA), Singapore, 2018, pp. 1-8, doi: 10.1109/ISBA.2018.8311459.
- T. J. Neal and D. L. Woodard, "On the Use of Mobile Calling Patterns for Soft Biometric Classification," 2018 IEEE 9th International Conference on Biometrics Theory, Applications and Systems (BTAS), Redondo Beach, CA, USA, 2018, pp. 1-6, doi: 10.1109/BTAS.2018.8698591.
- T. J. Neal and D. L. Woodard, "You Are Not Acting Like Yourself: A Study on Soft Biometric Classification, Person Identification, and Mobile Device Use," in IEEE Transactions on Biometrics, Behavior, and Identity Science, vol. 1, no. 2, pp. 109-122, April 2019, doi: 10.1109/TBIOM.2019.2905868.
- T. Neal and D. Woodard, "Mobile Biometrics, Replay Attacks, and Behavior Profiling: An Empirical Analysis of Impostor Detection," 2019 International Conference on Biometrics (ICB), Crete, Greece, 2019, pp. 1-8, doi: 10.1109/ICB45273.2019.8987407.
- T. Neal, M. A. Noor, P. Gera, K. Zanna and G. Kaptan, "Authenticating Phone Users Using a Gait-Based Histogram Approach on Mobile App Sessions," 2019 International Conference on Biometrics (ICB), Crete, Greece, 2019, pp. 1-7, doi: 10.1109/ICB45273.2019.8987418.
