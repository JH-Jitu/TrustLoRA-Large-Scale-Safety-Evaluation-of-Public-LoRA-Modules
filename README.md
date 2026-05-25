# TrustLoRA Research — Report (Public)

Quick links to all files in this folder.

## Main Reports

- Self Note - TrustLoRA Four Dimension Audit Desc [PDF](./TrustLoRA%20Research%20Note.pdf) | [DOCX](./SelfNote_TrustLoRA_Research_Note.docx)
- Self Note — TrustLoRA Learning Logs & notes [PDF](./SelfNote_TrustLoRA_learning_logs.pdf) | [DOCX](./SelfNote_TrustLoRA_learning_logs.docx)

## Audited Models

Reports for each LoRA adapter audited in this study.

| Model                                   | Report (PDF)                                                       | Raw Audit (JSON)                                                                |
| --------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------- |
| artek0chumak / bloom-560m-safe-peft     | [PDF](./audited_models/artek0chumak__bloom-560m-safe-peft.pdf)     | [JSON](./examples/completed_audits/artek0chumak__bloom-560m-safe-peft.json)     |
| Divyanshh / Bloom-560M-PEFT-alpaca-gpt4 | [PDF](./audited_models/Divyanshh__Bloom-560M-PEFT-alpaca-gpt4.pdf) | [JSON](./examples/completed_audits/Divyanshh__Bloom-560M-PEFT-alpaca-gpt4.json) |
| pachaar / bloom-560m-qa                 | [PDF](./audited_models/pachaar__bloom-560m-qa.pdf)                 | [JSON](./examples/completed_audits/pachaar__bloom-560m-qa.json)                 |
| Sapka / bloom-560m-customer             | [PDF](./audited_models/Sapka__bloom-560m-customer.pdf)             | [JSON](./examples/completed_audits/Sapka__bloom-560m-customer.json)             |
| ybelkada / opt-350m-lora                | [PDF](./audited_models/ybelkada__opt-350m-lora.pdf)                | [JSON](./examples/completed_audits/ybelkada__opt-350m-lora.json)                |

## Examples

Raw audit artifacts produced by the TrustLoRA pipeline.

- [`examples/completed_audits/`](./examples/completed_audits/) — JSON outputs for every audited model (linked above).

## Current Status

This repository contains a pilot-stage safety audit of 5 public LoRA/PEFT adapters. The current version is preliminary and focuses on building an evaluation workflow, collecting structured audit logs, and documenting early observations.

## Audit Dimensions

- [Self Note - TrustLoRA Four Dimension Audit Desc (PDF)](./TrustLoRA%20Research%20Note.pdf)

## Limitations

The current audit is not a final benchmark. Results are exploratory and may be affected by small model quality, prompt design, decoding settings, and limited sample size.

## Next Steps

- Expand from 5 to 25+ adapters
- Improve evaluator reliability
- Add reproducible scripts
- Add clearer aggregate charts
- Research tool with AI automation

## Relevant Research Papers

Background literature referenced in the study.

- [01 — LoRA: Low-Rank Adaptation of Large Language Models](./relevant_research_papers_29s/01_LoRA_Low-Rank_Adaptation_of_Large_Language_Models.pdf)
- [02 — QLoRA: Efficient Finetuning of Quantized LLMs](./relevant_research_papers_29s/02_QLoRA_Efficient_Finetuning_of_Quantized_LLMs.pdf)
- [03 — AdaLoRA: Adaptive Budget Allocation for PEFT](./relevant_research_papers_29s/03_AdaLoRA_Adaptive_Budget_Allocation_for_Parameter-Efficient_Fine-Tuning.pdf)
- [04 — A Note on LoRA](./relevant_research_papers_29s/04_A_Note_on_LoRA.pdf)
- [05 — DoRA: Weight-Decomposed Low-Rank Adaptation](./relevant_research_papers_29s/05_DoRA_Weight-Decomposed_Low-Rank_Adaptation.pdf)
- [06 — Survey on Parameter-Efficient Fine-Tuning Methods](./relevant_research_papers_29s/06_Survey_on_Parameter-Efficient_Fine-Tuning_Methods.pdf)
- [07 — Prefix-Tuning: Optimizing Continuous Prompts for Generation](./relevant_research_papers_29s/07_Prefix-Tuning_Optimizing_Continuous_Prompts_for_Generation.pdf)
- [08 — SaLoRA: Safety-Alignment Preserved Low-Rank Adaptation](./relevant_research_papers_29s/08_SaLoRA_Safety-Alignment_Preserved_Low-Rank_Adaptation.pdf)
- [09 — Safe LoRA: The Silver Lining of Reducing Safety Risks](./relevant_research_papers_29s/09_Safe_LoRA_The_Silver_Lining_of_Reducing_Safety_Risks.pdf)
- [10 — Constitutional AI: Harmlessness from AI Feedback](./relevant_research_papers_29s/10_Constitutional_AI_Harmlessness_from_AI_Feedback.pdf)
- [11 — TruthfulQA: Measuring How Models Mimic Human Falsehoods](./relevant_research_papers_29s/11_TruthfulQA_Measuring_How_Models_Mimic_Human_Falsehoods.pdf)
- [12 — Red Teaming Language Models with Language Models](./relevant_research_papers_29s/12_Red_Teaming_Language_Models_with_Language_Models.pdf)
- [13 — BOLD: Dataset and Metrics for Measuring Biases](./relevant_research_papers_29s/13_BOLD_Dataset_and_Metrics_for_Measuring_Biases.pdf)
- [14 — Jailbroken: How Does LLM Safety Training Fail](./relevant_research_papers_29s/14_Jailbroken_How_Does_LLM_Safety_Training_Fail.pdf)
- [16 — PEFTGuard: Backdoor Detection for PEFT Models](./relevant_research_papers_29s/16_PEFTGuard_Backdoor_Detection_for_Parameter-Efficient_FineTuned_Models.pdf)
- [17 — LoRA-as-an-Attack: Piercing LLM Safety](./relevant_research_papers_29s/17_LoRA-as-an-Attack_Piercing_LLM_Safety.pdf)
- [18 — Survey on Backdoor Attacks on Language Models](./relevant_research_papers_29s/18_Survey_on_Backdoor_Attacks_on_Language_Models.pdf)
- [19 — BadNets: Identifying Vulnerabilities in ML Model Supply Chain](./relevant_research_papers_29s/19_BadNets_Identifying_Vulnerabilities_in_ML_Model_Supply_Chain.pdf)
- [20 — On the Exploitability of Instruction Tuning](./relevant_research_papers_29s/20_On_the_Exploitability_of_Instruction_Tuning.pdf)
- [21 — ZKLoRA: Efficient Zero-Knowledge Proofs for LoRA Verification](./relevant_research_papers_29s/21_ZKLoRA_Efficient_Zero-Knowledge_Proofs_for_LoRA_Verification.pdf)
- [22 — HELM: Holistic Evaluation of Language Models](./relevant_research_papers_29s/22_HELM_Holistic_Evaluation_of_Language_Models.pdf)
- [23 — Evaluating Large Language Models: A Comprehensive Survey](./relevant_research_papers_29s/23_Evaluating_Large_Language_Models_A_Comprehensive_Survey.pdf)
- [24 — Beyond Accuracy: Behavioral Testing with CheckList](./relevant_research_papers_29s/24_Beyond_Accuracy_Behavioral_Testing_with_CheckList.pdf)
- [25 — MMLU: Measuring Massive Multitask Language Understanding](./relevant_research_papers_29s/25_MMLU_Measuring_Massive_Multitask_Language_Understanding.pdf)
- [26 — Fine-Tuning Aligned Language Models Compromises Safety](./relevant_research_papers_29s/26_Fine-Tuning_Aligned_Language_Models_Compromises_Safety.pdf)
- [27 — The Cost of Alignment: Measuring Safety Degradation](./relevant_research_papers_29s/27_The_Cost_of_Alignment_Measuring_Safety_Degradation.pdf)
- [28 — Open-Source LLM Security: A Systematic Analysis](./relevant_research_papers_29s/28_Open-Source_LLM_Security_A_Systematic_Analysis.pdf)
- [29 — Transformers: State-of-the-art Natural Language Processing](./relevant_research_papers_29s/29_Transformers_State-of-the-art_Natural_Language_Processing.pdf)
- [30 — Model Cards for Model Reporting](./relevant_research_papers_29s/30_Model_Cards_for_Model_Reporting.pdf)
