---
layout: post
title: "Emotionless: Privacy-Preserving Speech Analysis for Voice Assistants"
date: 2019-07-08
---
Voice-enabled interactions provide more human-like experiences in many popular IoT systems. 
Cloud-based speech analysis services extract useful information from voice input using speech recognition techniques. 
The voice signal is a rich resource that discloses several possible states of a speaker, such as emotional state, con dence and stress levels, physical condition, age, gender, and personal traits. Service providers can build a very accurate profile of a user’s demographic category, personal preferences, and may compromise privacy. 

To address this problem, a privacy-preserving intermediate layer between users and cloud services is proposed to sanitize the voice input. It aims to maintain utility while preserving user privacy. It achieves this by collecting real time speech data and analyzes the signal to ensure privacy protection prior to sharing of this data with services providers. Precisely, the sensitive representations are extracted from the raw signal by using transformation functions and then wrapped it via voice conversion technology.

Experimental evaluation based on emotion recognition to assess the efficacy of the proposed method shows that identication of sensitive emotional state of the speaker is reduced by ∼96 %. A samples of the original and generated files are listed below:
Note: the speaker identity is preserved, and the conversion is done for the emotion only. 
- From Happy to Neutral conversion 
<audio controls> <source src="https://drive.google.com/uc?export=download&id=1OOQ_UHAfbIlyZnW3SppLq9U7R-H2Rnnc" /> </audio>
<audio controls> <source src="https://drive.google.com/uc?export=download&id=1AP5C9VYFxMBXYNBDC1rsFyRMw85B2Unj" /> </audio>

<audio controls> <source src="https://drive.google.com/uc?export=download&id=1lfUE4PHBrMWU3_A0fow_5AzLGV9h7y8G" /> </audio>
<audio controls> <source src="https://drive.google.com/uc?export=download&id=1BPKjsCyahnYIKAeTEmNE5_zzTaqpJEAt" /> </audio>

- From Angry to Neutral conversion 
<audio controls> <source src="https://drive.google.com/uc?export=download&id=11xQNSeYOIbeVxo96gD_zrSoPGz-qrjj6" /> </audio>
<audio controls> <source src="https://drive.google.com/uc?export=download&id=15lDKSgklNQdAK_4aMZLFfjig-aUJcRqp" /> </audio>

<audio controls> <source src="https://drive.google.com/uc?export=download&id=1K5DRRyxE8TZaUzZxT1vXo_4jeky_7AfC" /> </audio>
<audio controls> <source src="https://drive.google.com/uc?export=download&id=1vdeLOLigvxQMMgFif4pivnLbIbRy_N7E" /> </audio>

