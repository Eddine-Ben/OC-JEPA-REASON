<p align="center">
  <img src="images/OC-JEPA.png" alt="OC-JEPA logo" width="320">
</p>

<h1 align="center">OC-JEPA-Reason</h1>

<p align="center">
  <strong>Object-Causal Joint Embedding Predictive Architecture for Grounded Safety Reasoning</strong>
</p>

Official repository for **OC-JEPA-Reason**, a framework for dashcam-based collision anticipation, hazard localisation and grounded natural-language reasoning.

## Overview

OC-JEPA-Reason extends OC-JEPA by connecting object-level latent representations to a fine-tuned vision–language model. The framework combines collision anticipation with explanations of potentially hazardous situations and recommendations for pre-emptive action.

Its aim is to connect three questions: **Is a collision likely? Which road user presents the hazard? How can the situation be explained?**

## Framework

1. **Video input:** a sequence of dashcam frames provides the observed driving context.
2. **OC-JEPA front end:** an object-centric latent world model estimates collision risk and localises potentially hazardous road users.
3. **Grounded reasoning:** hazard information and object-level representations condition a vision–language model to generate situation explanations and suggested pre-emptive actions.

## Key capabilities

- **Collision anticipation:** estimate collision risk from observed video before collision onset.
- **Hazard localisation:** identify road users associated with the predicted risk.
- **Grounded explanations:** connect natural-language outputs to the model’s hazard representations.
- **Action recommendations:** suggest pre-emptive responses to the anticipated situation.
