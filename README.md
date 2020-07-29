# 소개
HuggingFace BERT를 사용한 네이버 영화리뷰 감정분석

# 설명
BERT(Bidirectional Encoder Representations from Transformers)는 구글이 개발한 사전훈련(pre-training) 모델입니다. 위키피디아 같은 텍스트 코퍼스를 사용해서 미리 학습을 하면, 언어의 기본적인 패턴을 이해한 모델이 만들어집니다. 이를 기반으로 새로운 문제에 적용하는 전이학습(transfer learning)을 수행합니다. 좀 더 적은 데이터로 보다 빠르게 학습이 가능하다는 장점이 있습니다. 그래서 최근 자연어처리의 핵심 기법으로 떠오르고 있습니다.

이 예제에서는 한글 NLP의 Hello world라고 할 수 있는 네이버 영화리뷰 감정분석을 구현해보겠습니다. 가장 유명한 모델 중 하나인 Hugging Face의 PyTorch BERT를 사용하였습니다. 아래의 Chris McCormick의 블로그를 참조하여 한글에 맞게 수정하였음을 미리 알려드립니다.

< BERT Fine-Tuning Tutorial with PyTorch ><br>
-> https://mccormickml.com/2019/07/22/BERT-fine-tuning


BERT에 대해서 좀 더 자세한 설명은 박상길님과 Jay Alammar의 블로그를 참조하시기 바랍니다.

< BERT 톺아보기 ><br>
-> http://docs.likejazz.com/bert/

< The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning) ><br>
-> http://jalammar.github.io/illustrated-bert/

# Colab 실행
<a href="https://colab.research.google.com/drive/1tIf0Ugdqg4qT7gcxia3tL7und64Rv1dP">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
