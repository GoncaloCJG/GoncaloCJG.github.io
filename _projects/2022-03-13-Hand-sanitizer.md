---
layout: project
title: Buzzer to hand sanitizer
image: _project_imgs\Buzzer-to-Hand-sanitizer-front-view.jpeg
description: A project with Arduino Uno based on a buzzer that gives a signal when someone doesn't sanitize their hands. 
---

# Buzzer to hand sanitizer

This project was my final project for the "Sensors and Eletronics" class of my Master's Degree in Biomedical Engineering.

*Soon prototype front view*

## The Hardware and functionality
- Arduino Uno
- Two PIR sensors (infrared sensors)
- A module groove speaker
- Breadboard
- Jumpers

The prototype has two PIR sensors, one on top of the disinfectant, and another half meter ahead of the first. When the first one detects movement, meaning a person disinfected his hands, when he passes the second PIR sensor, the buzzer doesn't give any output sound. But when the second PIR sensor detects movement, without the first one detected, meaning a person passed by the first sensor without disinfecting his hands, the buzzer emits sound.

*Soon prototype inside view*

## The problem it solves
This projects came to mind to solve an existing problem: the problem of people walking by disinfectants without using it.

## The software
The software is pretty simple. The hardest part, altough not that hard but took me quite some time to figure it out, is the timing between the first PIR sensor and the second one.

The whole code can be found in [this repo]("https://github.com/GoncaloCJG/Buzzer-to-hand-sanitizer"), on my github profile.

## Simulation 
This video contains two phases: The first one is when someone doesn't disinfect their hands, meaning no movement was detected on the left PIR sensor and passes by the second PIR sensor generating a beep. The second is when someone disinfects their hands and consequently passes by the second PIR sensor generating no beep.

*Soon there will be a video*

## What I learnt
**Coding in C** - Although the arduino programming language is a simplified version of C, this was my first contact with the language. I found it pretty accessible, maybe because I was already familiarized with python, so the only thing that I needed to learn was the scripting part.

**Preserverance** - Working on this project reminded me to the importance of never giving up. Acepting failures as just attempts and to keep trying until something becomes right. In the end, every single try is worth it, and every single sucess is something to be proud of.