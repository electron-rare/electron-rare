# Clément Saillant

**Systèmes embarqués · IA locale · Spectacle vivant**

> *"I would rather be a cyborg than a goddess."* — Donna Haraway

Je construis des organismes hybrides à la frontière du corps, du silicium et du langage. Basé dans le Beaujolais. Du firmware ESP32 aux assistants IA qui tournent entièrement en local sur Apple Silicon, de la recherche cognitive pré-enregistrée aux contrôleurs de scène — parce que les choses les plus intéressantes se passent là où les corps et les machines se touchent.

Deux entités actives, un même atelier :

- **[L'Electron Rare](https://github.com/L-electron-Rare)** — *le corps.* Systèmes électroniques sur mesure, firmware, bancs de test, IA locale. ([lelectronrare.fr](https://www.lelectronrare.fr))
- **[Hypneum Lab](https://github.com/hypneum-lab)** — *le rêve.* Recherche en IA cognitive, ouverte et pré-enregistrée sur OSF (le framework **GENIAL**).

Et une entité close : **[ailiance](https://github.com/ailiance)** (2025–2026), infrastructure d'IA EU-souveraine — voir [Projets clos](#projets-clos-20252026).

---

## En ce moment — octobre 2026

- **Second cerveau** — assistant personnel *local-first* : mail, agenda, notes et mémos vocaux triés et résumés chaque matin, mémoire épisodique, inférence 100 % locale sur Apple Silicon (MLX). Code privé ; la méthode (petits services, règles explicites, modèles ouverts) est celle de tout ce qui suit.
- **HypnoLED** — contrôleur LED ESP32-S3 pour le spectacle vivant, co-simulation QEMU + ngspice, PCB en cours. Code privé jusqu'à la première série.
- **Hypneum — programme 2026-27** — quatre phases (vérité → falsifiable → dix hypothèses → écrire), ~10 h par semaine, suivi public sur le [GitHub Project de l'org](https://github.com/orgs/hypneum-lab/projects/1). Premier publiable visé : une note méthodologique sur les nuls calibrés et les errata.

## L'Electron Rare — le hardware *(le corps)*

Électronique sur mesure, firmware et outillage, avec le spectacle vivant comme terrain de jeu.

- **[Le Mystère du Professeur Zacus](https://github.com/electron-rare/le-mystere-professeur-zacus)** — escape room propulsée à l'IA : ESP32-S3 + React + pipeline vocal (ESP-SR, TTS, pont matériel MCP). Firmware : [ESP32_ZACUS](https://github.com/electron-rare/ESP32_ZACUS).
- **[AV-Live](https://github.com/electron-rare/AV-Live)** — monorepo de performance audiovisuelle : moteur sonore SuperCollider + oscilloscope openFrameworks + lanceur SwiftUI. GPL-3.
- **[DMX ESP Stepper Controller](https://github.com/electron-rare/DMX_ESP_Stepper-controller)** — moteur pas-à-pas piloté en DMX, pour l'Opéra de Montpellier.
- **[ADB pour Framework Arduino](https://github.com/electron-rare/ADB-pour-Framework-Arduino)** — protocole Apple Desktop Bus sur STM32 / ESP32 / AVR / Teensy : claviers et souris Apple vintage sur des machines modernes.
- **[Kill_LIFE](https://github.com/electron-rare/Kill_LIFE)** — méthodologie *spec-first* agentique pour l'embarqué (ESP32/STM32, gates, evidence packs).
- **[mascarade](https://github.com/electron-rare/mascarade)** — orchestration LLM multi-machines (mesh P2P, 8 providers, fine-tuning, outils MCP). Les LoRA entraînés avec sont sur [Hugging Face](https://huggingface.co/electron-rare).
- **[torch-vqc](https://github.com/electron-rare/torch-vqc)** — circuits quantiques variationnels en pur PyTorch, entraînés par autograd.
- **[openDIAW.be](https://github.com/electron-rare/openDIAW.be)** — instruments de musique pilotés par IA (drone, grain, glitch, TTS).

## Hypneum Lab — la recherche *(le rêve)*

- **[dream-of-kiki](https://github.com/hypneum-lab/dream-of-kiki)** — framework formel, agnostique au substrat, pour la consolidation des connaissances par le rêve dans les systèmes cognitifs artificiels. Axiomes DR-0..DR-4, critère de conformité exécutable.
- **[nerve-wml](https://github.com/hypneum-lab/nerve-wml)** — protocole nerveux de communication inter-WML : neuroletters discrètes, multiplexage γ/θ, topologie apprise éparse. DOI Zenodo.
- **[kiki-flow-research](https://github.com/hypneum-lab/kiki-flow-research)** — moteur de flot de gradient de Wasserstein pour la consolidation, brouillon de papier versionné sur Zenodo.
- **[bouba_sens](https://github.com/hypneum-lab/bouba_sens)** — benchmark de plasticité cross-modale ; première publication de résultats nuls du labo.
- **[micro-kiki](https://github.com/hypneum-lab/micro-kiki)** — runtime multi-LoRA sur Qwen3.6-35B-A3B (MLX) avec couche cognitive (mémoire Aeon, négociateur CAMP).

Le programme publie ses hypothèses avant de collecter les preuves, retire ses propres résultats quand les contrôles les invalident, et exige plusieurs graines pour toute affirmation. Détails et roadmap : [hypneum-lab/.github](https://github.com/hypneum-lab/.github).

## Projets clos (2025–2026)

- **[ailiance](https://github.com/ailiance)** — passerelle LLM compatible OpenAI routant vers des LoRA spécialistes (KiCad, STM32, SPICE, EMC…), agent de code **[ISAAC](https://github.com/ailiance/isaac-cli)**, benchmark EU AI Act **[iact-bench](https://github.com/ailiance/iact-bench)**, pipeline MLX **[ailiance-mac-tuner](https://github.com/ailiance/ailiance-mac-tuner)**. Développement arrêté en octobre 2026 ; les dépôts publics restent consultables, les modèles sur [Ailiance-fr](https://huggingface.co/Ailiance-fr).
- **FineFab / Factory 4 Life** — prototype de plateforme de fabrication (firmware → EDA assistée par IA), privé.
- **Formations** — six cours en ligne (Docker, LLM locaux, KiCad, IoT, FreeRTOS, ESP32 + IA) ; la plateforme est fermée, les supports sont archivés.

## Modèles fine-tunés

LoRA et datasets spécialisés par domaine — ESP32, STM32, KiCad, SPICE, PlatformIO, IoT, DSP, EMC — sur Hugging Face : [electron-rare](https://huggingface.co/electron-rare) · [Ailiance-fr](https://huggingface.co/Ailiance-fr) · [clemsail](https://huggingface.co/clemsail).

## Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C/C++](https://img.shields.io/badge/-C%2FC%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![STM32](https://img.shields.io/badge/-STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![KiCad](https://img.shields.io/badge/-KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![MLX](https://img.shields.io/badge/-MLX-000000?style=flat-square&logo=apple&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SuperCollider](https://img.shields.io/badge/-SuperCollider-000000?style=flat-square&logo=supercollider&logoColor=white)

## Liens

[![lelectronrare.fr](https://img.shields.io/badge/-lelectronrare.fr-FF6B6B?style=flat-square&logo=firefox&logoColor=white)](https://www.lelectronrare.fr)
[![saillant.cc](https://img.shields.io/badge/-saillant.cc-4A90D9?style=flat-square&logo=firefox&logoColor=white)](https://saillant.cc)
[![Hugging Face](https://img.shields.io/badge/-Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/electron-rare)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/electron-rare/)

---

*Mis à jour le 2026-10-25.*
*"The street finds its own uses for things."* — William Gibson
