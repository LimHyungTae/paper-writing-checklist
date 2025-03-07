# Latex Writing Checklists 

향후 같은 말을 반복하는 것을 방지하고자 천천히 하나씩 추가해 갈 예정

철저히 나의 취향이 반영된 writing checklists

---

## Basic

* **중요**: Latex에서 한 문장 당 한 줄에 쓸 것. Latex은 **Word처럼 문단 단위로 주저리주저리 쓰는게 아님!**.
  * C++과 같은 compile 언어를 사용한다는 생각으로 '코딩'하는 거임
* 영어에서 약어는 simultaneous localization and mapping (SLAM)과 같이 쓰면 됨.
 * 한글로 쓸 때와 규칙이 다름 주의

## Misc

* 위인 이름은 첫 글자 대문자로 (e.g., 'K'alman, 'R'odrigues, etc)
* 숫자와 단위 사이에는 스페이스가 필요함
  * Latex에는 반스페이스(`\,`)가 존재. 단위와 숫자 사이에는 `\,`를 사용하는 게 더 예쁨 (e.g., `20\,m`와 같이)
  * %는 단위이긴 히자민 숫자와 붙여 써야 함 (e.g., 10%, 20%와 같이)
* %가 오르는 건지, %p가 오르는 건지 잘 분간해야 함.
  * 10%에서 20%로 오르면 10% 오른 게 아니라 100%오른 거고, 10%p가 오른 것임.
* ChatGPT가 'ensure', 'faciliate'와 같은 단어를 추천해주는데, 이와 같은 단어보다 좀 더 구체적인 단어를 쓰길
  * 도대체 ensure consistency, ensure robustness가 무슨 뜻임?
  * (영) *ensure: to make (something) sure, certain, or safe*
    * 즉, 어떤 입력의 크기를 N개로 fix하는 등, 100이면 100 다 합당한 상황에서만 ensure을 쓰고, 그 이외에는 maintain consistency나 enhance robustness와 같이 독자가 직관적으로 이해할 수 있는 단어를 사용할 것

# Figures \& Tables

---

# Structure of Manuscript

## Abstract

* Abstract는 manuscript와 완전히 독립된, 하나의 paragraph임
 * 본문에 약어를 full로 썼더라도 abstract에서는 다시 해당 약어를 풀어서 써야 함.
 * Abstract에서 문단 나누지 말 것

## Introduction


## Related works


## Methodology


## Experiment results


## Conclusion

