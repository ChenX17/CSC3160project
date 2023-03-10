# Introduction


## Background of VoiceMOS Challenge

"Human listening tests are the gold standard for evaluating synthesized speech. Objective measures of speech quality have low correlation with human ratings, and the generalization abilities of current data-driven quality prediction systems suffer significantly from domain mismatch. The VoiceMOS Challenge aims to encourage research in the area of automatic prediction of Mean Opinion Scores (MOS) for synthesized speech." --VoiceMOS Challenge 2022 Homepage

## Task Description

Speech synthesis technologies such as text-to-speech synthesis (TTS) and voice conversion (VC) are a very active area of research, and this field relies on judgments of quality of the synthesized speech. The gold standard for evaluation is listening tests, where human raters listen to samples generated by different synthesis methods and give their opinions. One popular type of listening test is Mean Opinion Score (MOS).
With the popularity of crowdsourcing platforms, conducting listening tests has become easier than in the past. Nevertheless, listening tests are **time-consuming and costly**, and they cannot be used as a loss term in a training objective when developing synthesis systems. Furthermore, listening tests are heavily context-dependent. Therefore, it's important to apply **data-driven, machine-learning-based approaches** to develop automatic MOS prediction models.