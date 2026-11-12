<img src="assets/hero.svg" alt="Olive Knot AI - research and mobile inference" width="100%">

# Olive Knot AI | Award-winning research

**Computer vision · Mobile machine learning · Agricultural research**

An interdisciplinary software research project exploring visual classification of olive knot disease stages and observations of a possible biocontrol approach. The aim was to make a complex agricultural condition easier to understand by building a **phone-based stage-classification prototype** alongside a small plant experiment.

**This is a public case study, not a source-code release.** Original implementation, dataset, model weights, notebooks and detailed scientific protocols remain unpublished.

## Key outcomes

| Area | What the original project documented |
| :-- | :-- |
| Computer vision | A supervised, CNN-based image classification workflow distinguishing **four disease stages** |
| Mobile ML | A phone interface showing stage predictions and confidence distributions, using a TensorFlow Lite-format model |
| Evaluation | **88.33% reported classification accuracy** (0.88333 in the project poster); not an independent field-performance estimate |
| Experimental study | **12 olive saplings**, four comparison groups and a four-month observation period |
| Recognition | The provided award graphic identifies **first place in the software category** for Huseyin Eren Arikan |

## Concept in one view

<img src="assets/overview.svg" width="100%" alt="Conceptual public diagram of plant image, vision classifier, mobile result and parallel plant study">

The system's public-facing story is straightforward: **observe a branch, classify its visible stage, and display a result the user can interpret**. TensorFlow/Keras was used in the original model development and a mobile prototype was demonstrated. The diagrams are conceptual; they deliberately omit model and deployment internals.

The accompanying research investigated differences in disease progression among comparison groups, including a group involving *Bacillus subtilis*. The project poster describes slower symptom progression under the combined condition during the study period. This is an early experimental observation, **not** proof of a generally effective agricultural treatment.

## Interface demonstration

<img src="assets/mobile-experience.svg" alt="Illustrated reconstruction of two original mobile prototype screenshots, showing stage 1 and stage 4 predictions and confidence scores." width="100%">

<sub>Illustrative reconstruction of the original mobile prototype screenshots. The branch photographs and full original application are not distributed here. Individual confidence values describe the two pictured predictions, not model-wide accuracy.</sub>

## What the demonstrations show

The original materials include phone screenshots with stage-1 and stage-4 predictions and confidence percentages. **Per-image confidence (such as the 98.03% value in one screenshot) is not the same as evaluation accuracy**. The poster's 88.33% accuracy figure is reported separately.

A curated, code-free media package is retained for publishing an independent project gallery. The original poster is not hosted publicly because it contains code screenshots and detailed research procedures.

## The work behind the project

- Developed the computer-vision classification approach and connected its outputs to an accessible mobile experience.
- Organized a four-stage visual classification problem and reviewed training/validation behavior.
- Connected AI results with a four-month experimental research program using observed plant progression.
- Presented the engineering, scientific context and mobile demonstration in a formal research exhibition.

## Award and provenance

The supplied award graphic reads **"Yazilim Dali Birincisi" (first place, software category)** under TUBITAK and Istanbul Technical University branding. It establishes software-category recognition but is not used here to infer an unsupported national ranking.

**Researcher:** Huseyin Eren Arikan (Eren Arikan)  
**Supervising teacher (original poster):** Volkan Gonen

## Disclosure boundary

**Published:** research problem, high-level workflow, broad tools, selected reported outcomes, recognition, conceptual illustrations.

**Not published:** original model code, training scripts, architecture internals, trained weights, datasets, laboratory procedures, full poster, downloadable mobile package or proprietary documentation.

This case study describes a research prototype rather than a production-ready diagnostic tool. More testing and external validation are necessary before field use.

[Back to engineering profile](https://github.com/erudaperu)
