---
layout: post
title: "What is a wearable medical device?"
date: 2021-03-22 00:00:00 -0400
categories: [wearable medical device]
published: true
excerpt_separator: <!-- excerpt-end -->
---

All definitions are partial, an approximation of an image in our mind, of what we think, based on the available information. The value of a definition is not only how precise it is (how close it is to the reality it describes), but also how concise (how efficient the description is), how unanimous (how many people consider it a good or a standard definition), and how operational (it provides what is needed for an entity to fit the definition) it is.

I thought a lot about what a good definition for a wearable medical device (WMD) could be. A WMD is at the intersection of two overlapping but yet separate entities: wearable devices and medical devices. In addition, as medical devices, WMDs characteristics are pretty unique, being very complex electro-mechanical devices with many subsystems interacting with each other and with different external entities, either human (like a user, a physician, a caregiver) or non-human (a computer, another device, a database).

[Wikipedia](https://en.wikipedia.org/wiki/Wearable_technology) defines wearable devices (specifically, wearable technology) in the following way:

> Wearable technology [...] are smart electronic devices (electronic device with micro-controllers) that are worn close to and/or on the surface of the skin, where they detect, analyze, and transmit information concerning e.g. body signals such as vital signs, and/or ambient data and which allow in some cases immediate biofeedback to the wearer.

I found this sentence a bit confusing (how smart is smart enough?) and not very precise (body signals are a general formulation. For example, is a microphone a wearable device?).

In one of the following paragraph, [Wearable technology and health](https://en.wikipedia.org/wiki/Wearable_technology#Wearable_technology_and_health), little effort is put into framing the wearable technology in the healthcare space, since the most significant sentence is the following:

>Wearable technology is often used to monitor a user's health.

Moving to the specialized/scientific Literature, the definition of wearable device is more rigorous. I personally like the following definition [Gao _et al_]:

>(Wearable devices are) Devices that can be worn or mated with human skin to continuously and closely monitor an individual's activities, without interrupting or limiting the user's motions.

I find it very appropriate because there is little uncertainty, no confusion, and also because the last statement adds a nice touch ("without interrupting or limiting the user's motions"): if you cannot move, you are not wearing the device, you are simply attached to it.

On the other hand, when defining WMDs (often referred to as healthcare wearable devices, or wearable technology in healthcare) I find the definition in the specialized/scientific Literature often diluted in a long list of subsets and applications [Lee _et al_]. Moreover, there is still confusion between what is health-related and what is individually clinically relevant, instead.

In this post, I will try to provide a (allegedly) technical, concise, operational definition of what a WMD is, or at least what I personally think a WMD is.

I will start with a very simple, intuitive definition.

A WMD
* is continuously (or almost continuously) worn by the user (according to the definition above, "worn" does not simply mean "attached").
* is used in relation to one or more physiological and/or behavioral event.

Based on this definition, everybody has encountered WMD in their lives, way before Fitbit and similar ones: glasses (another very common device, hearing aids, already requires a more specific formulation).

To make a narrower and more specific definition, I need more precise statements.

A WMD
* is continuously (or almost continuously) worn by the user.
* captures (continuously or not) physiologically or behaviorally related signals from the user via one or more sensors.
* is used in relation to one or more physiological and/or behavioral event.

Based on this definition, quite a number of examples come to mind. To me, the most popular and closest fit to this definition is a fitness, or activity, tracker, i.e. a device that computes one or more indexes related to physical exercise.
Even though it has been demonstrated that physical exercise is somehow related to the individual’s health (at least at a population level) [Warburton _et al_], information about physical exercise in the general population can be hardly individually clinically relevant, if not for specific medical conditions [Giggins _et al_].

To generalize, wellness, fitness and/or medical research wearables are not necessarily WMD.

Thus, it is necessary again to slightly modify the definition.

A WMD
* is continuously (or, almost continuously) worn by the user.
* captures (not necessarily continuously) physiologically or behaviorally related signals from the user by one or more sensors.
* is used in relation to the user's health.

This definition describes something close to what I think a WMD should do. Maybe a sleep tracker, which evaluates how much and/or how good the user sleeps, with various degrees of precision.

But again, I am not quite there yet. Even though [sleep is more related to the individual health](https://medlineplus.gov/ency/patientinstructions/000871.htm) than physical exercise, we cannot really say that simply measuring some general characteristics of the individual health makes a device intended for a medical or a clinical use.

Again, I need to review my definition.

A WMD
* is continuously (or, almost continuously) worn by the user.
* captures (not necessarily continuously) physiologically or behaviorally related signals from the user by one or more sensors.
* computes one or more aggregated clinically relevant indexes related to one or more, current or future, user's health condition.
* is use in relation to the user's health.

At this point, I absolutely need to clarify what "related" means, explaining the nature of the relations I care-freely suggested in the definition.
To do so, I will start with a personal revised definition of a medical device by the [FDA](https://www.fda.gov/medical-devices/classify-your-medical-device/how-determine-if-your-product-medical-device).

>(A medical device is an) "instrument [...] intended for use in the diagnosis of disease or other conditions, or in the cure, mitigation, treatment, or prevention of disease [...]."

This definition clearly says that a medical device is a device with a specific purpose.

The WMD definition can then be modified as follows.

A WMD
* is continuously (or, almost continuously) worn by the user.
* captures (not necessarily continuously) physiologically or behaviorally related signals from the user by one or more sensors.
* computes one or more aggregated clinically relevant indexes related to one or more, current or future, user's health condition.
* is intended for use in the diagnosis, or the cure, mitigation, treatment, or prevention of a disease or a health condition.

At this point, we still need to clarify one relation, i.e. the connection between the information provided by the sensors data (or the clinically relevant indexes) and the medical condition(s). It is natural to express this relation in terms of efficacy (how relevant is this information) and safety (how safe is to trust this information). In other words, we need to clinically validate the device to be effective and safe for its intended use. This does not mean that the device ability for its intended use is generally or arbitrarily good. On the contrary, this means that the device performs statistically equal or better than some real (and previously validated) or hypothetical (and clinically relevant) reference. The decision on how good the device should perform (i.e., how strong the relation is) is not (totally) arbitrary, and most of all cannot be decided by the manufacturer. This makes the whole difference in the world.

This completes the definition.

<!-- excerpt-start -->
A WMD
* is continuously (or, almost continuously) worn by the user.
* captures (not necessarily continuously) physiologically or behaviorally related signals from the user by one or more sensors.
* computes one or more aggregated clinically relevant indexes related to one or more, current or future, user's health condition.
* is intended for use in the diagnosis, or the cure, mitigation, treatment, or prevention of a disease or a health condition.
* is clinically validated for efficacy and safety for its intended use.
<!-- excerpt-end -->

#### References

Gao, W., Emaminejad, S., Nyein, H.Y.Y., Challa, S., Chen, K., Peck, A., Fahad, H.M., Ota, H., Shiraki, H., Kiriya, D., Lien, D.-H., Brooks, G.A., Davis, R.W., Javey, A., 2016. Fully integrated wearable sensor arrays for multiplexed in situ perspiration analysis. Nature 529, 509–514. [https://doi.org/10/f3kwz8](https://doi.org/10/f3kwz8)

Giggins, O.M., Clay, I., Walsh, L., 2017. Physical Activity Monitoring in Patients with Neurological Disorders: A Review of Novel Body-Worn Devices. DIB 1, 14–42. [https://doi.org/10/gjh9fq](https://doi.org/10/gjh9fq)

Lee, S.M., Lee, D., 2020. Healthcare wearable devices: an analysis of key factors for continuous use intention. Serv Bus 14, 503–531. [https://doi.org/10/gjh9dg](https://doi.org/10/gjh9dg)

Warburton, D.E.R., Nicol, C.W., Bredin, S.S.D., 2006. Health benefits of physical activity: the evidence. CMAJ 174, 801–809. [https://doi.org/10/bp223n](https://doi.org/10/bp223n)
