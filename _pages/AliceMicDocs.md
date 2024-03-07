---
permalink: /Docs/Mics
title: "Alice Mics Usage"
excerpt: "Usage guide for OPA Alice Microphones and general XLR Microphones"
layout: single
last_modified_at: 2024-02-12T11:59:26-04:00
author_profile: true
toc: true
toc_sticky: true
---

This guide assumes that you’ve purchased a microphone assembled by me (AcerolaVR) and have all the necessary equipment already. If you don’t already have an audio interface, boom arm, and cable, you can find my recommendations [here](https://ko-fi.com/post/Recommended-Budget-Audio-Interfaces-M4M0JA7NQ).

That being said, most of this information should be applicable to other XLR condenser microphones.
## Microphone Usage
These microphones are SIDE-ADDRESS microphones, meaning that the capsule is oriented facing out the side of the microphone, and not the top.

For microphones with a logo on the body, the capsule will be facing the same side as the logo. For microphones without the logo, look at the XLR connector and find the notch where the XLR cable clips in. This should be the front/capsule side of the microphone.

If it’s unclear which side is which still, speak into either the front or rear of the microphone, the correct side should sound noticeably better than the other.
Microphones also have a pickup pattern, which describes their directional sensitivity to sound. Microphones from my shop, and most condenser microphones have a CARDIOID pattern, meaning that they pick up sound mostly from the front, some from the side, and reject sounds from directly behind.

Speak into the front of the microphone from a distance of 6-12 inches, this provides a good balance of clarity without picking up mouth or breathing sounds.

### Audio Interface Setup
Condenser microphones, including the ones I build, require +48V PHANTOM POWER to function correctly. On the interface, there should be a button or a switch to enable +48V; find and enable this. 

CAD CX2 +48V Toggle on the Rear Lower Right

Focusrite Scarlett Solo +48V beneath the Left Gain Knob

#### Setting up Gain on the Interface
The audio interface will have its own dial for gain. You want to set gain such that it is as high as it can go while not causing the microphone to peak when you are at your loudest (yelling, screaming, etc.). Most interfaces will have a light to indicate when audio is being picked up, about to peak/clip, or peaking/clipping. For example, a Focusrite interface uses green, yellow, and red for the aforementioned states. You can use this to dial in the correct gain visually by seeing if any sounds you make are causing the microphone to peak/clip.

Alternatively, you can go into a program like Audacity and make a short recording. You will be able to clearly tell in the waveforms your volume and when you are peaking.

Too Quiet

Good

Too Loud

## Program Setup
Audio interfaces will typically record a stereo input, with the microphone on one channel and an instrument/other microphone on the 2nd channel to make mixing easier. Because of this, there is some additional setup for OBS and other programs for the microphone to work as expected.
OBS Configuration
For OBS, go to Advanced Audio Properties by clicking on the gear icon in your Audio Mixer. Enable “Mono” to downmix the microphone to mono.


### Levels
[Source](https://twitter.com/VirtualKohai/status/1635119050157330432/)

### Filters
If you have filters set up from before, do not use these! Every microphone is different and you’ll need to redo these settings to get the best sound quality out of your new microphone. I do think these microphones already perform very well without filters, and adding filters will add a performance load to your computer.

Below are my recommendations of optional recommendations to use at first
- **Gain:** I typically add a 10-15 dB filter for my microphone, and then use the slider to dial in the correct gain. This gives you more control over your volume, since the audio mixer slider normally caps out at +0.0 dB
- **Noise Suppression:** Use this if you’re in a loud environment. If you have an RTX card, I would download this and use the RTX noise suppression. https://www.nvidia.com/en-us/geforce/broadcasting/broadcast-sdk/resources/. It would be preferable to make sure you’re in a quiet environment and to orient your microphone to point away from unwanted noises
- **Noise Gate:** dial in a noise gate to reject sounds you don’t want, such as keyboard, drinking, or mouth sounds.

After this, you can dial in the microphone more with filters of your choice, such as an equalizer, reverb for singing, etc… The microphones perform quite well without additional filters, and note that every filter incurs some performance load.
#### Discord
For your input device, select the audio interface to use the microphone. There should be no extra configuration to make the microphone work. For best results, I recommend going into Discord settings, Voice & Video, Voice Processing, and disabling Echo Cancellation and Noise Suppression. You may also want to have someone help dial-in your Input Volume/Gain. 
#### Windows
Make sure the interface gain/volume level is set to 100 in Windows. Control the gain only through the interface to dial in the correct gain, and in the program being used to pick up audio. Sometimes, Windows will lower the levels automatically. If you’re having strange issues, make sure that the Windows settings for your interface haven’t changed



