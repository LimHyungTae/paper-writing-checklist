## ✅ 논문 검토 요청 전 Checklists

### Title/Subtitle 관련 

1. 제목의 대소문자 사용을 확인할 것
2. 논문 내 Section 및 Subsection 제목에 대소문자 규칙이 일관되게 적용되었는지 확인할 것
3. Method 부분의 제목이 "Method"나 "Methodology"로만 되어 있다면, 보다 구체적인 제목으로 수정할 것


### \ref 관련 

1. Reference를 명사로 표현하지 말 것
    * (❌) "[5] proposed BLABLA" or "BLABLA was proposed in [5]"
    * (🟢) Lim \textit{et al.} [5] proposed BLABLA.
  
2.  Caption에서는 제목 형태로 명사형으로 써야함 + caption 상에서 (a), (b), 등을 명사로 사용하지 말 것 
    * (❌) (a) shows the ground truth map.
    * (🟢) (a) Ground truth map.
  
3. Pdf에서 `Ctrl+F`를 통해
   * Table이나 Fig. 가 제대로 잘 가리키고 있는지(간혹 휴먼 에러로 Fig. #을 Table #로 잘 못 쓰는 경우가 있음) 
   * Table 뒤에 점이 없는지 (.은 약어이기 때문에 Fig 뒤에 찍는 것임. 그러니 Table 뒤에는 Table. #라고 적으면 안 됨)
   * Table, Fig.의 대소문자가 제대로 되어 있는지
   * Fig #(a)와 같이 잘 되어 있는지 (Fig. # (a)로 space를 넣으면 ❌)
   확인
4. \Cref 사용
### 오탈자 관련

1. Grammarly / ChatGPT 등으로 최종 오탈자를 확인했는지?
    * 초안 작성보다 오히려 수정 과정에서 대소문자나 수일치 오류가 더 자주 생김. 따라서 문법 체크는 한 번으로 끝내지 말고, 수정할 때마다 반복해서 확인해야 함. 그렇지 않으면 아래와 같은 실수를 종종 저지름

![typos](https://github.com/user-attachments/assets/5a008196-3c87-467d-9709-8cc456f20e2f)

### 수식 관련  

\begin{equation}을 linebreak 없이 이전 line과 붙여 썼는지
\end{equation} 부분에 linebreak 없이 문장을 붙여 썼는지


 
---

N. For template
   * (❌) 
   * (🟢) 
