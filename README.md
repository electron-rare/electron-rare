# Clément Saillant

**Ingénieur systèmes embarqués · Architecte IA · Spectacle vivant**

> *"I would rather be a cyborg than a goddess."* — Donna Haraway

Je construis des organismes hybrides à la frontière du corps, du silicium et du langage. Basé dans le Beaujolais. Du firmware ESP32 à l'orchestration LLM multi-machines, de la recherche cognitive aux stacks d'inférence souveraines européennes — parce que les choses les plus intéressantes se passent là où les corps et les machines se touchent.

Trois entités, un même cluster, une même thèse — trois façons d'habiter cette frontière :

- **[L'Electron Rare / FineFab](https://github.com/L-electron-Rare)** — *le corps.* Hardware, firmware, IoT et EDA commerciaux.
- **[ailiance](https://github.com/ailiance)** — *le langage souverain.* Infrastructure d'IA EU-souveraine : passerelle LLM compatible OpenAI, routage vers des LoRA spécialistes, conformité EU AI Act. ([ailiance.fr](https://ailiance.fr))
- **[Hypneum Lab](https://github.com/hypneum-lab)** — *le rêve.* Recherche en IA cognitive, ouverte et pré-enregistrée sur OSF (le framework **GENIAL**).

---

## ailiance — l'IA souveraine *(le langage)*

> *« Le corps n'est pas une donnée biologique, mais une fiction politique techno-vivante. »* — Paul B. Preciado

Une passerelle LLM compatible OpenAI qui route chaque requête vers le bon spécialiste — modèles fine-tunés par domaine (KiCad, STM32, SPICE, EMC…), inférence sur cluster Apple Silicon + RTX, traçabilité conforme à l'EU AI Act. L'essentiel reste privé jusqu'à la sortie publique ; la surface ouverte est ci-dessous.

- **[isaac-cli](https://github.com/ailiance/isaac-cli)** — **ISAAC**, agent de code souverain. Extension VS Code + CLI Ink, routé par défaut vers la passerelle ailiance, tracing JSONL conforme EU AI Act.
- **[ailiance-demo](https://github.com/ailiance/ailiance-demo)** — cockpit frontend de la flotte LLM (FastAPI + Vite + React 19), vitrine publique + admin Tailscale-only.
- **[iact-bench](https://github.com/ailiance/iact-bench)** — benchmark audit-grade EU AI Act : 31 domaines, validateurs sandbox/MCP, piste d'audit NDJSON.

## L'Electron Rare / FineFab — le hardware *(le corps)*

La stack de fabrication FineFab : monorepo *Factory 4 Life*, moteur EDA, et l'outillage matériel/firmware sous lequel tout repose.

- **[euclideda](https://github.com/L-electron-Rare/euclideda)** — moteur de pipeline EDA.
- **[kicad-mcp-pro](https://github.com/L-electron-Rare/kicad-mcp-pro)** — serveur MCP pilotant KiCad pour la conception PCB assistée par LLM.
- **[hardware-coagent](https://github.com/L-electron-Rare/hardware-coagent)** — co-agent de conception matérielle.

## Hypneum Lab — la recherche *(le rêve)*

- **[dream-of-kiki](https://github.com/hypneum-lab/dream-of-kiki)** — framework formel, agnostique au substrat, pour la consolidation des connaissances par le rêve dans les systèmes cognitifs artificiels. *Papers 1 & 2.*
- **[nerve-wml](https://github.com/hypneum-lab/nerve-wml)** — protocole nerveux de communication inter-WML : neuroletters discrètes, multiplexage γ/θ, topologie apprise éparse. PyPI + DOI Zenodo.
- **[bouba_sens](https://github.com/hypneum-lab/bouba_sens)** — benchmark de plasticité cross-modale. Méthodologie multi-seed, courbes dose-réponse d'Amedi.

## Hardware & spectacle vivant

Là où le silicium rencontre la scène.

- **[Le Mystère du Professeur Zacus](https://github.com/electron-rare/le-mystere-professeur-zacus)** — escape room propulsée à l'IA. ESP32-S3 + React + pipeline vocal (ESP-SR, TTS, pont matériel MCP). *La peau.*
- **[AV-Live](https://github.com/electron-rare/AV-Live)** — monorepo de performance audiovisuelle : moteur sonore SuperCollider + oscilloscope openFrameworks + lanceur SwiftUI. GPL-3.
- **[DMX ESP Stepper Controller](https://github.com/electron-rare/DMX_ESP_Stepper-controller)** — contrôleur de moteur pas-à-pas piloté en DMX, pour l'Opéra de Montpellier.

## Modèles fine-tunés

LoRA et datasets spécialisés par domaine — ESP32, STM32, KiCad, SPICE, PlatformIO, IoT, DSP, EMC — sur Hugging Face : [electron-rare](https://huggingface.co/electron-rare) · [Ailiance-fr](https://huggingface.co/Ailiance-fr).

## Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C/C++](https://img.shields.io/badge/-C%2FC%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![KiCad](https://img.shields.io/badge/-KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MLX](https://img.shields.io/badge/-MLX-000000?style=flat-square&logo=apple&logoColor=white)
![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![SuperCollider](https://img.shields.io/badge/-SuperCollider-000000?style=flat-square&logo=supercollider&logoColor=white)

## Liens

[![lelectronrare.fr](https://img.shields.io/badge/-lelectronrare.fr-FF6B6B?style=flat-square&logo=firefox&logoColor=white)](https://lelectronrare.fr)
[![ailiance.fr](https://img.shields.io/badge/-ailiance.fr-009688?style=flat-square&logo=firefox&logoColor=white)](https://ailiance.fr)
[![saillant.cc](https://img.shields.io/badge/-saillant.cc-4A90D9?style=flat-square&logo=firefox&logoColor=white)](https://saillant.cc)
[![Hugging Face](https://img.shields.io/badge/-Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/electron-rare)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/electron-rare/)

---

*L'Electron Rare — là où le matériel mute en intelligence.*
*"The street finds its own uses for things."* — William Gibson
