---
title: Sesame CSM
emoji: 🌱
colorFrom: gray
colorTo: green
sdk: gradio
sdk_version: 5.20.0
app_file: app.py
pinned: false
license: apache-2.0
short_description: Conversational speech generation
---

## CSM 1B

**2025/03/13** - We are releasing the 1B CSM variant. Code is available on GitHub: [SesameAILabs/csm](https://github.com/SesameAILabs/csm). Checkpoint is [hosted on HuggingFace](https://huggingface.co/sesame/csm-1b).

---

CSM (Conversational Speech Model) is a speech generation model from [Sesame](sesame.com) that generates RVQ audio codes from text and audio inputs. The model architecture employs a [Llama](https://www.llama.com/) backbone and a smaller audio decoder that produces [Mimi](https://huggingface.co/kyutai/mimi) audio codes.

A fine-tuned variant of CSM powers the [interactive voice demo](https://www.sesame.com/voicedemo) shown in our [blog post](https://www.sesame.com/research/crossing_the_uncanny_valley_of_voice).

A hosted [HuggingFace space](https://huggingface.co/spaces/sesame/csm-1b) is also available for testing audio generation.

## Misuse and abuse ⚠️

This project provides a high-quality speech generation model for research and educational purposes. While we encourage responsible and ethical use, we **explicitly prohibit** the following:

- **Impersonation or Fraud**: Do not use this model to generate speech that mimics real individuals without their explicit consent.
- **Misinformation or Deception**: Do not use this model to create deceptive or misleading content, such as fake news or fraudulent calls.
- **Illegal or Harmful Activities**: Do not use this model for any illegal, harmful, or malicious purposes.

By using this model, you agree to comply with all applicable laws and ethical guidelines. We are **not responsible** for any misuse, and we strongly condemn unethical applications of this technology.

**Prompts**
Conversational prompts are from the [EdAcc dataset](https://groups.inf.ed.ac.uk/edacc/)
Read speech prompts are form the [LibriTTS-R dataset](https://google.github.io/df-conformer/librittsr/)

**Authors**
Johan Schalkwyk, Ankit Kumar, Dan Lyth, Sefik Emre Eskimez, Zack Hodari, Cinjon Resnick, Ramon Sanabria, Raven Jiang, and the Sesame team.
