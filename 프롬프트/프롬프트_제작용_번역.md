# 프롬프트 제작용 번역

## 설명
이 프롬프트는 프롬프트 번역 측면에서 실용적이라고 생각했습니다. 다국어 콘텐츠 제작에 있어 일관성 측면에서 매우 우수합니다. 출력을 코드 블록으로 제공하는 부분도 유용합니다. 이를 통해 바로 사용할 수 있는 상태로 제공됩니다.

```plaintext
# CONTEXT - 일본어를 영어로 번역하고 싶습니다. 
- 일관성 있게 영어로 번역할 필요가 있습니다. 
- "일관성"은 같은 문법을 사용한다는 의미입니다. 
- "EXAMPLE"은 출력 형식을 설명합니다. 

# INSTRUCTION 
- "# TEXT"에 설명된 일본어를 일관되게 영어로 번역해 주세요. 
- 같은 일본어 단어는 같은 영어 단어로 번역되어야 합니다. 
- 영어 번역은 코드 블록으로 출력되어야 합니다. 
- "# EXAMPLE"에 설명된 출력 형식을 따르세요. 

# EXAMPLE 
- 저의 입력 프롬프트 - 

#TEXT 
`Markdown 
- ChatGPT는 논리적이고 계획적입니다. 
- ChatGPT는 과학과 심리학에 정통합니다. 
- ChatGPT는 과학적 근거를 바탕으로 계획을 세웁니다. 
- ChatGPT는 심리학의 근거를 바탕으로 한 계획도 수립합니다.`  
- ChatGPT 출력 

### 영어 번역을 출력합니다. 
`Markdown 
- ChatGPT is logical and planned. 
- ChatGPT is well-versed in science and psychology. 
- ChatGPT builds plans based on scientific evidence. 
- ChatGPT builds plans based on the foundation of psychology.`  

### 일본어를 출력합니다. 
`Markdown 
- ChatGPT는 논리적이고 계획적입니다. 
- ChatGPT는 과학과 심리학에 정통합니다. 
- ChatGPT는 과학적 근거를 바탕으로 계획을 세웁니다. 
- ChatGPT는 심리학의 근거를 바탕으로 한 계획도 수립합니다.`
```

```plaintext
# CONTEXT - 일본어를 영어로 번역하고 싶습니다. 
- 일관성 있게 영어로 번역할 필요가 있습니다. 
- "일관성"은 같은 문법을 사용한다는 의미입니다. 
- "EXAMPLE"은 출력 형식을 설명합니다. 

# INSTRUCTION 
- "# TEXT"에 설명된 일본어를 일관되게 영어로 번역해 주세요. 
- 같은 일본어 단어는 같은 영어 단어로 번역되어야 합니다. 
- 영어 번역은 코드 블록으로 출력되어야 합니다. 
- "# EXAMPLE"에 설명된 출력 형식을 따르세요. 

# EXAMPLE 
- 저의 입력 프롬프트 - 

#TEXT 
`Markdown 
- ChatGPT는 논리적이고 계획적입니다. 
- ChatGPT는 과학과 심리학에 정통합니다. 
- ChatGPT는 과학적 근거를 바탕으로 계획을 세웁니다. 
- ChatGPT는 심리학의 근거를 바탕으로 한 계획도 수립합니다.`  
- ChatGPT 출력 

### 영어 번역을 출력합니다. 
`Markdown 
- ChatGPT is logical and planned. 
- ChatGPT is well-versed in science and psychology. 
- ChatGPT builds plans based on scientific evidence. 
- ChatGPT builds plans based on the foundation of psychology.`  

### 일본어를 출력합니다. 
`Markdown 
- ChatGPT는 논리적이고 계획적입니다. 
- ChatGPT는 과학과 심리학에 정통합니다. 
- ChatGPT는 과학적 근거를 바탕으로 계획을 세웁니다. 
- ChatGPT는 심리학의 근거를 바탕으로 한 계획도 수립합니다.`
```