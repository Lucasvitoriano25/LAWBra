# LAWBra

This project aims to refine an NLP model for the Brazilian legal system by leveraging state-of-the-art language models and adapting them to process Brazilian Portuguese legal texts. Our goal is to create a tool for legal research, case analysis, and judicial decision prediction.

## Authors
Joao Pedro Volpi (joao-pedro.monteiro-volpi@student-cs.fr)
Lucas Vitoriano de Queiroz Lira (lucasvitoriano.queirozlira@student-cs.fr)
CentraleSupélec

## Abstract
This work focuses on enhancing the effectiveness of the Brazilian legal system through the application of Natural Language Processing technologies. Utilizing the Iudicium Textum Dataset, we fine-tune small LLM models such as Google Gemma and Microsoft PHI-2, aiming to create a sophisticated tool capable of understanding and analyzing legal documents within the Brazilian context.

## Introduction
The evolution of NLP technologies presents new opportunities for the legal field, especially in streamlining case analysis and judicial decision-making processes. Our project harnesses these advancements to serve the specific needs of the Brazilian legal system, contributing to the broader field of NLP.

## Background
### Dataset
Our primary dataset comprises legal decisions from the Brazilian Supreme Federal Court, designed to address the shortage of Portuguese language resources for NLP model training.


### Models Employed
We utilize Google Gemma and Microsoft Phi-2 models, chosen for their balance between performance and computational feasibility.

## Experiments / Results
Our results demonstrate the effectiveness of fine-tuning in improving model performance for legal text analysis, compared against baselines like GPT 3.5 Turbo.

![gemma_loss](https://github.com/Lucasvitoriano25/LAWBra/assets/52925699/65948c14-d7ec-472b-8cb7-3286f71ebee4)
![phi_loss](https://github.com/Lucasvitoriano25/LAWBra/assets/52925699/a2fe4744-7c11-45ba-bc3d-e38ef92fc3d1)


| Model Comparison         | Gemma (FT) |   Phi (FT) |
|--------------------------|------------|------------|
| Gemma (FT) vs. Phi (FT)  |    132     |      18    |



| Model Comparison         | Gemma | Gemma (FT) | 
|--------------------------|-------|------------|
| Gemma vs. Gemma (FT)     |  64   |     86     |
