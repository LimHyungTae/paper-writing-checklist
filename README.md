# Latex Writing Checklists 

향후 같은 말을 반복하는 것을 방지하고자 천천히 하나씩 추가해 갈 예정

철저히 나의 취향이 반영된 writing checklists. 사실 어떤 것은 right/wrong (무조건 따라야 할것들)이고 어떤것은 better/worse (따르면 좋은 것들)의 영역이기는 하지만, 아마 안 따르는 것은 누구도 알려주지 않아서라고 생각됩니다.
논문을 쓰기 전에 한 번 읽고, 교수님께 논문 드리기 전에 한 번 읽고 스스로 다시 찬찬히 살펴본 후 교수님께 v1 논문을 드리면 🎓✨당신도 할 수 있다! @박사 3년 졸업★ ✨🎓 ~(아님 말고)~

---

## Basic

* **중요**: Latex에서 한 문장 당 한 줄에 쓸 것. Latex은 **Word처럼 문단 단위로 주저리주저리 쓰는게 아님!**.
  * C++과 같은 compile 언어를 사용한다는 생각으로 '코딩'하는 거임 [#1](https://github.com/LimHyungTae/paper-writing-checklist/issues/1)
  * 실제로 저는 24년부터 논문 writing도 vim으로 하는 걸로 완전히 정착함...*Latex은 '코딩'이다*!
      * (향후 이 관점에서 왜 overleaf을 쓰는게 fxxking shit인지 설명 예정)
    ![image](https://github.com/user-attachments/assets/aa76e84a-9b02-4fab-a153-6d419bdb6426)

      
* 영어에서 약어는 simultaneous localization and mapping (SLAM)과 같이 쓰면 소문자로 쓰면 됨
    *  simultaneous localization and mapping (SLAM)
* %가 오르는 건지, %p가 오르는 건지 잘 분간해야 함.
  * 10%에서 20%로 오르면 10% 오른 게 아니라 100%오른 거고, 10%p가 오른 것임.
* ChatGPT가 'ensure', 'faciliate'와 같은 단어를 추천해주는데, 이와 같은 단어보다 좀 더 구체적인 단어를 쓰길
  * 도대체 ensure consistency, ensure robustness가 무슨 뜻임?
  * (영) *ensure: to make (something) sure, certain, or safe*
    * 즉, 어떤 입력의 크기를 N개로 fix하는 등, 100이면 100 다 합당한 상황에서만 ensure을 쓰고, 그 이외에는 maintain consistency나 enhance robustness와 같이 독자가 직관적으로 이해할 수 있는 단어를 사용할 것
* 위인 이름은 첫 글자 대문자로!
  * e.g., **K**alman filter, **G**auss-**N**ewton optimization, **L**yapunov stability, **F**ourier transform, **E**uler angle, **T**alyor series, **R**odrigues' rotation formula, etc 

## Misc


* 숫자와 단위 사이에는 스페이스가 필요함
  * Latex에는 반스페이스(`\,`)가 존재. 단위와 숫자 사이에는 `\,`를 사용하는 게 더 예쁨
      * e.g., `20\,m`와 같이
  * 숫자와 %는 no space로 붙여 써야 함 
      * e.g., 10%, 20%와 같이

---

# Figures \& Tables

---

# Structure of Manuscript

논문을 한 번도 안 써본 이는 [나의 브런치 글](https://brunch.co.kr/@85a651d484d84f2)을 한 번 읽어보면 감이 오리라 생각된다.

## Abstract

* Abstract는 manuscript와 완전히 독립된, 하나의 paragraph임
 * 본문에 약어를 full로 썼더라도 abstract에서는 다시 해당 약어를 풀어서 써야 함.
 * Abstract에서 문단 나누지 말 것

## Introduction


## Related works

* 페이지 수가 아무리 부족하더라도(e.g., ICRA의 6장 제한이나 RA-L의 8장 제한) Related works을 생략하지 말자. 예전에 페이지가 부족해서 'Introduction and Related Works'라고 논문을 제출한 적이 있었는데, reviewer가 이 둘을 분리해라는 코멘트를 준 적이 있음. 반면, Introduction과 Related Works를 별도로 작성한 경우, 이를 다시 합치라는 피드백을 받을 가능성은 거의 없으므로, 가급적이면 두 섹션을 분리하여 구성하는 것이 바람직함. 기억하자. 논문은 **늘 먹던 비슷한 맛으로, 떨어지지 않게** 작성하는 것이 중요하다.
* 페이지 제한이 없다면, 전략적으로 (i) baseline approach의 저자가 쓴 논문을 우겨 넣어서 인용을 하고 (ii) 가장 최신 연도의 학회의 관련 연구를 반드시 reference에 포함해야 한다(모두다 related works에서 열거해라는 의미가 아님!)
  * 예를 들어, static map building 관련 연구인데 [ERASOR](https://arxiv.org/abs/2103.04316)나 [ERASOR2](https://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/lim2023rss.pdf)가 인용에 없는 논문이 만약 나에게 리뷰가 온다면? 바로 빈정 상함 이슈로 '선행 연구가 불충분하다'라고 딴지 걸 수 있다.   

## Methodology


## Experiment results


## Conclusion

