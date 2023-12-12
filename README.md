# [N21 - Sentence Classification]

Transformer-Encoder(from Huggingface)를 사용하여 문장의 토픽 분류를 진행


## Datasets
: [KLUE YNAT](https://huggingface.co/datasets/klue)
(Korean Language Understanding Evaluation(KLUE)의 Yonhap News Agency Topic Classificaiton(YNAT) 데이터셋)
: 본 데이터는 Creative Commons Attribution-ShareAlike 4.0 International License(CC BY-SA 4.0)를 따릅니다. 따라서 어떤 목적으로든, 심지어 상업적으로도 어떤 매체나 형식으로 자료를 공유할 수 있습니다. N21 problem에 Huggingface 모델링 실습을 위햇 데이터셋을 사용합니다.

## Huggingface 에 배포된 모델 확인



## Huggingface Tokenizer 확인
아래 세 조류의 tokenizer 사용해 모델 결과 확인
- klue_tokenizer
- kykim_tokenizer
- snunlp_tokenizer

## pytorch_lightning 활용
pytorch lightning 을 사용해 보다 간결한 모델링을 해봅니다.

## 라이브러리 버전
- datasets==1.6.5
- transformers==4.20.1
- pytorch_lightning==2.4.0
