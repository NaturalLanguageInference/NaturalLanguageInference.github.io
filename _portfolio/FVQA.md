---
caption: #what displays in the portfolio grid:
  title: FVQA
  subtitle: Fact-Based Visual Question Answering
  thumbnail: assets/img/portfolio/FVQA.jpg
  
#what displays when the item is clicked:
title: FVQA
subtitle: Fact-Based Visual Question Answering
image: assets/img/portfolio/FVQA.jpg
alt: FVQA

---
<p style="text-align:left;">
FVQA는 supporting-facts에 근거해서 이미지에 대해 추론 능력을 가진 모델이다.
Visual Question Answering(VQA)에서 장면에 근거해서 직접 대답할 수 있는 종류의 질문을 하는데, FVQA는 깊은 추론을 하면서 사실 기반 시각적 질의 대답(Fact-based Visual Question Answering)이다.
질문에 대한 대답을 하기 위해 answer-supporting fact tuple를 추가한 image-question-answer 인 triplet을 포함하였고 이를 통해 외부정보를 확장하였다.

-이미지에서 질문과 관련된 내용을 감지하고 이미 구축된 지식베이스에 있는 정보와 연관짓는다.
-Knowledge Bases: DBpedia, ConceptNet, WebChild 와 같은 기존의 구조환 된 지식베이스 사용
-질의의 경우, 이미지와 지식베이스 정보에 대해 실행되는 질문으로 맵핑된다.
-질의에 대한 반응은 supporting-facts로 이끌고 이는 질문에 대한 최종 답변을 형성하게 된다.
</p>
