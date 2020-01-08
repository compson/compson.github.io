---
layout: mypost
title: Nested NER -入れ子になった固有表現認識
categories: [nlp]
---

* English: Nested Named Entity Recognition
* 日本語：入れ子になった固有表現認識
* 中文：嵌套命名实体识别

## "Nested" (入れ子構造) とは？
>例文：京都大学

文  |レベル（内側)| レベル(外側)
--|---|---
京|B-LOC |B-ORG
都|I-LOC |I-ORG
大|O  |I-ORG
学|O  |I-ORG

京都は位置(LOCATION)、京都大学は組織(ORGANIZATION)です。この京都大学というの固有表現は入れ子構造です。



## 语料库Copus



## Nested








> []()<br>
> []()<br>
