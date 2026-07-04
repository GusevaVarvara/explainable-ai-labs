# Interpretable AI Labs

Данный репозиторий содержит практические работы по курсу «Интерпретируемый искусственный интеллект», посвященные исследованию методов объяснения решений моделей машинного обучения, анализу их надежности и изучению вопросов безопасности современных систем искусственного интеллекта.

## Содержание репозитория

Практические работы охватывают основные направления интерпретируемого искусственного интеллекта:

* анализ и аудит моделей машинного обучения;
* исследование важности признаков и глобальной интерпретации моделей;
* локальное объяснение отдельных предсказаний;
* сравнение различных методов интерпретации моделей;
* визуализация внутренних представлений нейронных сетей;
* анализ неопределенности предсказаний;
* исследование состязательных атак (Adversarial Attacks) и устойчивости моделей;
* интерпретация трансформеров и больших языковых моделей;
* исследование вопросов безопасности и выравнивания современных ИИ-систем.

В рамках проекта были реализованы и исследованы следующие методы и инструменты:

* Explainable Boosting Machine (EBM)
* Partial Dependence Plots (PDP)
* Accumulated Local Effects (ALE)
* SHAP
* UMAP
* Monte Carlo Dropout
* Saliency Maps
* Grad-CAM
* FGSM и PGD adversarial attacks
* TransformerLens (Logit Lens, Linear Probing)
* методы анализа безопасности и Constitutional AI

Во время выполнения лабораторных работ использовались модели машинного обучения, сверточные нейронные сети, трансформеры и большие языковые модели. Для каждой работы проводился анализ поведения моделей, сравнение различных методов интерпретации, визуализация результатов и исследование ограничений существующих подходов Explainable AI.

Цель работы — изучить современные методы интерпретируемого искусственного интеллекта, научиться объяснять решения моделей различной сложности, исследовать их надежность, устойчивость к атакам и ограничения при использовании в реальных задачах.

| Файл | Colab |
|---|---|
| [1_model_interpretability_basics.ipynb](./1_model_interpretability_basics.ipynb) | [Открыть в Colab](https://colab.research.google.com/drive/1MwZ1tH1WleW_3VuUPironTaSoeIVMdsE?usp=sharing) |
| [2_model_agnostic_explainability.ipynb](./2_model_agnostic_explainability.ipynb) | [Открыть в Colab](https://colab.research.google.com/drive/1mAjtdLhA1S91xeoSoPb5Qaayquxybb8A?usp=sharing) |
| [3_uncertainty_and_visual_explanations.ipynb](./3_uncertainty_and_visual_explanations.ipynb) | [Открыть в Colab](https://colab.research.google.com/drive/1io5x5g2qB7x0r4cHZdfBLdTz_2gMutWv?usp=sharing) |
| [4_adversarial_attacks_and_xai.ipynb](./4_adversarial_attacks_and_xai.ipynb) | [Открыть в Colab](https://colab.research.google.com/drive/1HCBwADWf2LRMZcqoSYvi73nIcN2hKrtF?usp=sharing) |
