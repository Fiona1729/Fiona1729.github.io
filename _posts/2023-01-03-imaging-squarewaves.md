---
layout: post
title: Headphone imaging, square waves, and why the Sennheiser HD800 are the best
  gaming headphones
date: 2023-01-03 17:57 -0700
category: Blogs
---
On headphone forums an extremely common question is "what is a good pair of headphones for gaming", and the responses usually include headphones which have good imaging and soundstage. But what really is good imaging? How can you tell what has good imaging and soundstage without having tried them before, from objective measurements? To understand this, we first have to understand how your ears actually determine the direction of a sound.

# Human audio spatialisation

When a sound is made in the real world, it travels to your ears through the air, and interacts with your head and ears on the way. This gives a number of different properties which allow your brain to determine which direction a sound is coming from. The most direct is the time difference between the sound arriving at each ear (interaural time difference, or ITD), which allows fairly accurate pinpointing of sound to the left or right of your head. There's also an overall volume difference (interaural intensity difference) from your head blocking some of the sound to one ear. The delay also introduces a phase offset (difference between the timing of peaks and troughs on each sound wave), and the origin of the sound vertically or back/front causes other frequency response and phase effects which are far too complicated to explain here. These effects are the basis of a head-related transfer function (HRTF), and the science behind these is a field in itself. However, these HRTFs are often simulated in software, so we can focus on what our headphones can actually affect, the timing difference between the two sides, and phase. How can we determine whether, and to what extent, a headphone preserves this information?

# Square wave response

| ![Square wave construction via odd harmonics](/assets/img/square_wave_construction.gif) |
|:--:|
| *[By Thenub314 - Own work, CC BY-SA 3.0](https://commons.wikimedia.org/w/index.php?curid=12062602)* |

A square wave response chart is another way of showing a headphone's frequency response in a sense, but can also provide some additional useful information for our purposes. The ability of the headphone to produce very high frequency sounds is reflected in the rising and falling edges of the square wave, and the low-frequency response is reflected in the ability of the headphone to "hold" the diaphragm at the "high" position. This edge response is also known as the slew rate of the headphones. The square wave chart also shows some phase information for both high and low frequency.  The short explanation of square wave response and imaging is that the leading edges of the waves, and thus the high frequency response, are directly responsible for very clear time differences in signals arriving to your ears, and thus audio spatialisation and imaging. The brain can detect timing differences down to at least 10 MICROSECONDS so clarity here is of very high importance. The phase reflected in these diagrams additionaly can help or hinder your brain's ability to interpret the direction of a sound. The below diagram has some basic issues with square waves and the corresponding causes.

| ![Square wave distortions](/assets/img/square_wave_problems.jpg) |
|:--:|
| *[Tyll Hersten's explanation of InnerFidelity measurements](https://www.stereophile.com/content/innerfidelity-headphone-measurements-explained)* |

# DAC filters

An additional factor in the imaging of a pair of headphones can be the DAC/amp filter settings. DACs usually use filters to remove high frequency noise from the output, and many DACs provide the option to change which filters are used for this. I use a Topping DX3 Pro, and I found [this article](https://addictedtoaudio.com.au/blogs/how-to/how-to-pick-the-best-filter-setting-for-your-dac) which not only explains some of the specific filters but has images of what each filter does to a single spike. Anecdotally, imaging on my setup improved a fair bit after switching to the F-5 filter from F-1, and this was somewhat confirmed in a very adhoc A/B test with CS:GO and Rainbow 6. I don't really know of many good sources for these kinds of filters, but my understanding is that the slower roll-off filters have less ringing before and after transients, and linear phase response filters preserve phase response (of course).

# Conclusion

Headphone imaging is largely dependent on a fast and clear rising edge of a sound, though this is not the sole factor. HRTF imparts frequency response and phase information which improves the spatialisation of audio greatly. A headphone with good imaging still needs to be supported by a sound engine that actually performs the maths to get to your end result properly, and your DAC/amp can also affect this. The square wave curve offers a good rough benchmark for audio imaging from a given pair of headphones, and I've compared several headphones with (in)famously good and bad imaging and soundstage with the 300 and 3000 Hz square wave responses from Reference Audio Analyzer and the leading edges do follow this trend. I'm hoping to some quantitative analysis on these measurements as a follow-up, and I hope that measurement of imaging can progress to the point where very subjective recommendations are not the primary way to recommend a good pair of headphones for gaming.


# Sources and additional info

* [Tyll Hersten's explanation of InnerFidelity measurements](https://www.stereophile.com/content/innerfidelity-headphone-measurements-explained) is incredibly in depth and is what made me initially want to write this.

* [Tyll Hersten's talk "Finding Flat"](https://youtu.be/SDRHFNfFCFU?t=3117) has a section on square wave response

* [RTINGS Imaging Scoring](https://www.rtings.com/headphones/tests/sound-quality/imaging) has good explanations of some other effects on headphones but their measurements seem to be somewhat out of whack with subjective views on what headphones have the best imaging and soundstage for games. I can't really say if the zeitgeist is wrong or if their weightings of different factors is.

* [Wikipedia - Sound localization by the human auditory system](https://en.wikipedia.org/wiki/Sound_localization#Sound_localization_by_the_human_auditory_system) explains how humans actually interpret sound direction

* [Topping DAC/amp filters](https://addictedtoaudio.com.au/blogs/how-to/how-to-pick-the-best-filter-setting-for-your-dac) explains DAC filter effects on transients




