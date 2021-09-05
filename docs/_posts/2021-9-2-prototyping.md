## Goal/Idea

To hack/repurpose a toy EEG headband for applications in generative/installation art.

Electroencephalography (EEG) is a typically non-invasive way to measure the brain's overall electrical activity. Within the past decade, EEG technologies have made their way onto the consumer market as meditation monitoring tools and brain-training games. This has given tinkerers relatively cheap and reliable access to brain data. Toy EEG headbands like the ones found in [Mindflex](https://www.amazon.com/Mattel-P2639-Mindflex-Game/dp/B001UEUHCG) are able to be [rewired with Arduino](http://www.frontiernerds.com/brain-hack). By plugging the Arduino-headband rig into the computer, one may send the headband's realtime readings via serial bus into software like OpenFrameworks or Processing.

My goal is to use EEG to create an artwork or system that not only reacts to the viewer's brain activity, but also provides an output that directly affects that activity. This output should affect any of the five senses (sight, hearing, smell, taste, touch) -- ideally multiple at a time. This two-way interaction would ideally allow the viewer - or rather, user - to not only control the artwork in a novel way, but also control their own mind through a strange form of mindful meditation.

## Safety Precautions

Since I am dealing with electricity in extreme proximity to the brain, extra caution is necessary - especially when handling the Arduino-headband rig. During use, the Arduino may **only** draw power from the laptop; **no wall power allowed**. The presence of electricity also means that people suffering from epilepsy may not use the headband.

## Possible Configurations

![configs](https://user-images.githubusercontent.com/7122029/132132219-91fd8d5a-d8e9-4be7-af95-f69d06352262.png)
