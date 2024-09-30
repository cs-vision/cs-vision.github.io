---
permalink: /
title: "Shi Chen's Personal Website"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi there! My name is Shi Chen (Simplified Chinese: 陈实, Japanese: 陳 実). I am currently a master student in Electrical Engineering and Information Technology at [ETH Zurich](https://ethz.ch/en.html). Previously, I obtained my Bachelor's degree at [Kyoto University](https://www.kyoto-u.ac.jp/en), where I was supervised by [Prof. Ko Nishino](https://vision.ist.i.kyoto-u.ac.jp/) and [Prof. Shohei Nobuhara](https://shohei.nobuhara.org/index.en.html) for my thesis.

I am interested in 3D vision in general, in particular 3D/4D reconstruction and SLAM. My long-term goal is to make possible an immersive, interactive and physically-plausible digital copy of the dynamic world. 

# Education

* 2022 - Present, M.Sc. Electrical Engineering and Information Technology, ETH Zurich, Switzerland.
* 2018 - 2022, B.E. Electrical and Electronic Engineering, Kyoto University, Japan.

# Selected Projects

## MonoDy-GS: Online Monocular Dynamic Gaussian Splatting
Semester project in spring 2024

Advisors: [Prof. Martin R. Oswald](https://cvg.ethz.ch/team/Dr-Martin-R-Oswald), [Dr. Sandro Lombardi](https://www.sandrolombardi.com/en/), [Prof. Marc Pollefeys](https://people.inf.ethz.ch/marc.pollefeys/)

<img src="../images/tum_sitting_render_compressed.gif" alt="Project Profile" width="600px"> 

In this project, we attempt to address the challenge of online modelling of dynamic scenes from monocular RGB-D inputs. Traditional methods for dynamic scene reconstruction often rely on extensive multi-view coverage or operate in an offline manner, which limits their accessibility and interactability in potential application scenarios such as Mixed Reality. To overcome these limitations, we propose MonoDy-GS, an online system that uses 3D Gaussians as the underlying representation to model dynamic scenes. Our approach incorporates several priors based on real-world scene dynamics to compensate for the lack of multi-view information inherent in monocular setups. This enables the system to track and model scene deformations incrementally. We validate the effectiveness of MonoDy-GS in modelling scene dynamics through a series of qualitative and quantitative experiments.

## NeRaser: NeRF-based 3D Object Eraser
Course Project for [Mixed Reality](https://cvg.ethz.ch/lectures/Mixed-Reality/)

<strong>Shi Chen</strong>, Liuxin Qing, Shao Zhou, Xichong Ling

Advisor: [Dr. Sandro Lombardi](https://www.sandrolombardi.com/en/)

[[Demo](https://www.youtube.com/watch?v=cF8qTAb9TMs)]

## EvenNICER-SLAM: Event-based Neural Implicit Encoding SLAM
Semester project in fall 2022

Advisors: [Dr. Danda Pani Paudel](https://insait.ai/dr-danda-paudel/), [Prof. Luc Van Gool](https://vision.ee.ethz.ch/people-details.OTAyMzM=.TGlzdC8zMjg3LC0xOTcxNDY1MTc4.html)

<img src="../images/teaser recording_480p_high.gif" alt="Project Profile" width="600px"> 

The advancement of dense visual simultaneous localization and mapping (SLAM) has been greatly facilitated
by the emergence of neural implicit representations. Neural implicit encoding SLAM, a typical example
of which is NICE-SLAM, has recently demonstrated promising results in large-scale indoor scenes. However,
these methods typically rely on temporally dense RGB-D image streams as input in order to function
properly. When the input source does not support high frame rates or the camera movement is too fast, these
methods often experience crashes or significant degradation in tracking and mapping accuracy. In this project,
we propose EvenNICER-SLAM, a novel approach that addresses this issue through the incorporation of event
cameras. Event cameras are a novel type of bio-inspired cameras that respond to intensity changes instead of
absolute brightness. Specifically, we integrated an event loss backpropagation stream into the NICE-SLAM
pipeline to enhance camera tracking with insufficient RGB-D input. We found through quantitative evaluation
that EvenNICER-SLAM, with an inclusion of higher-frequency event image input, significantly outperforms
NICE-SLAM with reduced RGB-D input frequency. Our results suggest the potential for event cameras to
improve the robustness of dense SLAM systems against fast camera motion in real-world scenarios.

