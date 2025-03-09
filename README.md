# Latex Writing Checklists 

이 글은 향후 내가 임용된 후 대학원생들의 논문을 검토할 때, 같은 말을 각 학생에게 반복해서 설명하는 행위를 그나마 덜 하기 위해 작성하게 되었다. 시간이 날 때마다 지금까지 배워온 writing 관련 내용을 정리하여 하나씩 추가해 갈 예정이다.

이는 철저히 **나의 취향이 반영된 writing 체크리스트**이다. 사실, 일부 항목은 right/wrong(반드시 따라야 할 것)이고, 일부는 better/worse(따르면 좋은 것)의 영역이지만, 아는 만큼 보인다고 하지 않는가. 
논문을 쓰기 전에 한 번 읽고, 교수님께 논문 드리기 전에 한 번 읽고 스스로 다시 찬찬히 살펴본 후 교수님께 v1 논문을 드리면 🎓✨당신도 할 수 있다! @박사 3년 졸업★ ✨🎓 ~(아님 말고)~

---

# 논문을 쓸 때의 마음가짐

1. 인간은 누구나 manuscript를 쓸 때 실수를 하게 되어 있다. '나는 아닐거야'라는 어리석은 생각을 내려 놓자.
2. 논문은 절대로, 학부과정 때까지의 시험을 100점 맞는 것처럼 **'만점'의 상태가 될 수 없다**.  그러니 'reject되지 않게 쓰는 것'이 가장 중요하다
    * Accept을 노린다는 마인드가 아니라, reject의 complement를 노린다는 마인드를 장착해야 한다.
3. 논문은 엄격한 **template이 존재하는 글**이다. 논문을 처음 쓰는 이라면 **제발 창의적으로 글이나 figure를 표현하지 말라**. 논문을 처음 쓰는 이라면, 95%의 확률도 당신만 알아볼 수 있는 기괴한 representation을 사용할 확률이 높기 때문.
    * 내가 읽어본 논문 중 인용수가 그래도 100에 가까운 논문에서 쓰인 표현 방식이나 문장 구조를 기반으로 글을 쓰거나 figure를 따라 그리는 것을 추천한다. 

---

## 당장 도움되는 English Writing Tips

* 논문 쓰는 것 자체가 처음이라면? 사실 영어 writing이 중요한 게 아니라, '논문'이라는 것의 이해도를 먼저 높이는 게 중요함. [한글로 설명된 이 글](https://brunch.co.kr/@85a651d484d84f2/2)을 한 번 읽어보는 것을 추천.
* 한 문단에서는 하나의 key message만 존재해야 함
   * 글을 다쓰고 각 문단 별 길이를 살펴보자. 문단의 길이가 너무 길거나 (> 10) 짧으면 (< 3) 무엇을 key sentence로 다시 얘기해야할지 글의 flow를 점검해보자.    
* 영어는 명사형으로 쓰는 게 자연스러움
   * He cooks well (x)이라고 하지 않고, He's a good cook (o)라고 하는 게 외국인 입장에서 자연스러움.
   * 적용 예시: *Our approach is robust, accurate and fast*라고 쓰는 거 보다 *we propose a robust, accurate, and fast approach*라고 쓰는 게 더 자연스러움
* 자기가 잘 모르는 영어 단어를 쓰고자 한다면 반드시 영영 사전에서의 의미를 읽어보고, 실제로 어떻게 사용되는지 구글이나 사전에서 예시 문장을 통해 확인할 것 
   * 한글로 비유하자면, 검열, 검수, 검토, 검사가 다 타인이 무언가를 살펴보고 확인한다는 의미를 지닌 단어이지만 각기 다르게 쓰이는 걸 한국인이라며 알 것이다. 그 누구도 교수님께 '교수님 검열 부탁드립니다'하고 논문을 보내지 않지 않는가? 하지만 한글을 어중간하게 아는 외국인 입장에서는 '오우, 검열? Such a novel word for me'하고 쓸 수도 있다. 이처럼 언어 마다 각 단어가 지니는 늬앙스가 존재하기 때문에, 이를 잘 살펴봐야 함(특히 우리같은 non-English spoken world의 연구자라면 더더욱...). 
* 영어에서 약어는 simultaneous localization and mapping (SLAM)과 같이 쓰면 소문자로 쓰면 됨
    *  simultaneous localization and mapping (SLAM)
* ChatGPT가 'ensure', 'faciliate'와 같은 단어를 추천해주는데, 이와 같은 단어보다 좀 더 구체적인 단어를 쓰길
  * 도대체 ensure consistency, ensure robustness가 무슨 뜻임?
  * (영) *ensure: to make (something) sure, certain, or safe*
    * 즉, 어떤 입력의 크기를 N개로 fix하는 등, 100이면 100 다 합당한 상황에서만 ensure을 쓰고, 그 이외에는 maintain consistency나 enhance robustness와 같이 독자가 직관적으로 이해할 수 있는 단어를 사용할 것
* 논문에서 'outperform'이라는 단어를 **절대로** 쓰지 말자
    * 그냥 'showed lower error'나 'showed higher success rate', 'showed a substantial increase in performance'와 같이 완곡한 표현을 쓸 것. 
* 'significant'나 'significantly'는 t-test 이후 통계적으로 유의미하다고 검증이 되었을 때만 쓸 수 있음
* 한국에서는 특히 passive voice로 글을 써라고 많이들 가르치는데, 'we'를 써도 괜찮다. 너무 많이 쓰지만 말 것
* 위인 이름은 첫 글자 대문자로!
  * e.g., **K**alman filter, **G**auss-**N**ewton optimization, **L**yapunov stability, **F**ourier transform, **E**uler angle, **T**alyor series, **R**odrigues' rotation formula, etc 

### 영어 공부할 때 읽어보면 좋은 글/논문들 (To 나의 미래 대학원생들에게)

* [RSS Pioneers들의 research statement](https://sites.google.com/view/rsspioneers2025/archive)
    * 날고 기는 Robotics/Robotic Vision 분야 박사 말년차 친구들이 오로지 2장짜리 글만으로 선정되는, 매우 경쟁이 치열한 글들임. 따라서 수준이 낮은 글은 모두 탈락하고, 좋은 글만 살아남아서 영어 공부할 때 문장들을 통째로 외워보는 것을 추천함. 특히, 이 research statement들의 intro에서는 robotics의 다른 분야 사람들도 이해를 할 수 있게 쉽게 쓰려고 노력한 흔적들이 많이 엿보이는데, 그런 테크닉들을 줍줍해보면 좋을듯      
* [ERASOR2, RSS'23](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/lim2023rss.pdf)
* [HeLiMOS, IROS'24](https://arxiv.org/abs/2408.06328)
* [KISS-Matcher, ICRA'25](https://arxiv.org/abs/2409.15615)

"아니 ㅋㅋ 나르시시스트 뭐냐고" 할 수도 있겠지만, 위의 논문들은 두 명 이상의 교수님이 여러 번 검토해 준 글이라 특정 개인의 편향이 상대적으로 적다고 생각함. 
또한, 나의 scientific writing에 대해 말하자면, 명현 교수님께 논문을 엄밀하게 쓰는 테크닉들을 직/간접적으로 많이 배워서 어느정도 글을 잘 쓴다고 생각하고 있었는데, 22년에 Cyrill 교수님 랩에 visiting scholar로 가서 '독자가 읽기 편한 글을 쓰는 법'에 대해서 트레이닝을 했음:

<img width="282" alt="image" src="https://github.com/user-attachments/assets/4833729c-df28-4928-908e-688ae539b7ce" />
(Cyrill 교수님의 이 [scientific writing 강좌](https://www.youtube.com/watch?v=QYbAvOPcy0s&t=1153s)를 꼭 볼 것을 추천)

그래서 2023년 이후의 글들에서는 두 가지 요소를 모두 잡으려고 노력했으며, 그래서 대체로 잘 쓰여졌다고 생각한다(물론 내 기준임) + 내가 논문 figure에 굉장히 진심이기 때문에, figure 그리는 법에 대해서도 참고해보면 좋을 것.

---

## Basic

* **중요**: Latex에서 한 문장 당 한 줄에 쓸 것. Latex은 **Word처럼 문단 단위로 주저리주저리 쓰는게 아님!**.
  * C++과 같은 compile 언어를 사용한다는 생각으로 '코딩'하는 거임 [#1](https://github.com/LimHyungTae/paper-writing-checklist/issues/1)
  * 실제로 저는 24년부터 논문 writing도 vim으로 하는 걸로 완전히 정착함...*Latex은 '코딩'이다*!
      * (향후 이 관점에서 왜 overleaf을 쓰는게 fxxking shit인지 설명 예정)
    ![image](https://github.com/user-attachments/assets/aa76e84a-9b02-4fab-a153-6d419bdb6426)

## Misc

* %가 오르는 건지, %p가 오르는 건지 잘 분간해야 함.
  * 10%에서 20%로 오르면 10% 오른 게 아니라 100%오른 거고, 10%p가 오른 것임.
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

* 페이지 수가 아무리 부족하더라도(e.g., ICRA의 6장 제한이나 RA-L의 8장 제한) Related works을 **생략하지는 말자**. 예전에 Patchwork를 쓸 때 페이지가 부족해서(8장 제한) 'Introduction and Related Works'라고 한 section에 둘을 다 적어서 제출한 적이 있었는데, reviewer가 이 둘을 분리해라는 코멘트를 준 적이 있음. 반면, Introduction과 Related Works를 별도로 작성한 경우, 이를 다시 합치라는 피드백을 받을 가능성은 거의 없으므로, 가급적이면 두 섹션을 분리하여 구성하는 것이 바람직함. 기억하자. 논문은 **늘 먹던 비슷한 맛으로, 떨어지지 않게** 작성하는 것이 중요하다.
* 페이지 제한이 없다면, 전략적으로 (i) baseline approach의 저자가 쓴 논문을 우겨 넣어서 인용을 추가로 더 하고 (ii) 가장 최신 연도의 학회의 관련 연구를 반드시 reference에 포함해야 한다(모두다 related works에서 열거해라는 의미가 아님!)
  * 예를 들어, static map building 관련 연구인데 [ERASOR](https://arxiv.org/abs/2103.04316)나 [ERASOR2](https://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/lim2023rss.pdf)가 인용에 없는 논문이 만약 나에게 리뷰가 온다면? 바로 빈정 상함 이슈로 '선행 연구가 불충분하다'라고 딴지 걸 수 있다.

## Methodology


## Experiment results


## Conclusion

