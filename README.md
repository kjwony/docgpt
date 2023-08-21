# Docgpt
## Overview
- This project uses openai chatgpt to create a document-based chatbot and visualize the results using wandb.

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```python
python docgpt_wandb.py
```

## Description
- 이 프로젝트는 openai chatgpt를 사용하여 문서 기반의 챗봇을 만든 후, wandb를 사용하여 결과물을 시각화합니다.
- doc.tsv는 챗봇의 system prompt와 user prompt를 구성하는 참조 문서들과 질문으로 구성되어 있습니다.
- doc.tsv를 기반으로 system prompt와 user prompt를 생성한 후, [wandb prompts](https://docs.wandb.ai/guides/prompts?_gl=1*1omyst2*_ga*NTk5NTE1MzU3LjE2ODA3NTY0NTc.*_ga_JH1SJHJQXJ*MTY5MjU3OTc3Mi43MC4wLjE2OTI1Nzk3NzMuNTkuMC4w)를 사용하여 챗봇의 결과물을 확인할 수 있습니다.
- doc.tsv의 내용은 chatgpt를 통해 생성되었습니다. 이것은 사용법을 설명하기 위한 예시 파일로 전문적인 지식이 아니니 주의하시기 바랍니다.
- 스크립트를 실행한 후, 나오는 wandb 링크를 클릭하면 결과물을 확인할 수 있습니다.