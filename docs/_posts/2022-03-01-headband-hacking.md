I finally managed to obtain access to the IM labs, which made it possible to open up the Mindflex headband and solder leads for the Arduino to clamp to. Below is a gallery of the process of opening and soldering the headband (hover over gallery to arrow to other pictures).

<blockquote class="imgur-embed-pub" lang="en" data-id="a/M5P9ZLk"><a href="//imgur.com/a/M5P9ZLk">Hacking the Mindflex Headband</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

First impressions of the headband upon testing:

- Priming the headband for Arduino connection was surprisingly easy, requiring only 2 leads to solder.
- The headband's signalling system is evidently proprietary and not meant for such hacking. The unit of brain activity measurement used by the Mindflex is not microvolts (mV) like with conventional EEGs, but rather an internally relative unit of measure. This does make it rather difficult to make sense of the data values and parse the signal with Fast Fourier Transform (FFT).
- The headband only sends one packet per second, which makes it quite inconvenient to make our artwork react in realtime to brain activity.

As a backup plan, I ordered an Emotiv headset, which is well-suited for BCI experimentation and is expected to be much more convenient to work with than the Mindflex - albeit more expensive.