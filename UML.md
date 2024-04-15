# UML
- 시스템 분석, 설계 구현 등 시스템 개발 관점에서 개발자/유저 또는 개발자 상호간 원활한 의사소통을 위해 표준화한 대표적 객체지향 모델링 언어
- 사물 / 관계 / 다이어그램

## 사물
- 모델을 구성하는 가장 중요한 기본 요소.
- 다이어그램 안에 관계가 형성될 수 있는 대상들을 뜻한다.
  
> 구조사물 : 시스템의 개념적, 물리적 요소 (클래스, 유즈케이스, 컴포넌트)  
> 행동사물 : 시간과 공간에 따른 요소들의 행위 (상호작용)  
> 그룹사물 : 요소들을 그룹으로 묶은 것 (패키지)  
> 주해사물 : 부가적 설명이나 제약 조건 (노트)

## 관계
- 사물과 사물 사이 연관성을 뜻한다.

> 연관관계 : 2개 이상 사물이 서로 관련된 관계. 사물 사이를 실선으로 연결, 방향성은 화살표로 표현
> 
> 집합관계 : 한 사물이 다른 사물에 포함된 관계. 포함하는 쪽(전체)과 포함되는 쪽(부분)은 서로 독립적이며, 전체에서 부분으로 속 빈 마름모로 연결하여 표현
> 
> 포함관계 : 포함하는 사물(전체)의 변화가 포함되는 사물(부분)에게 영향을 미치는 관계. 전체와 부분은 서로 독립될 수 없고 생명주기를 함께하며, 부분에서 전체로 속이 채워진 마름모를 연결하여 표현
> 
> 일반화관계 : 한 사물이 다른 사물에 비해 더 일반적 또는 구체적인지 표현. 보다 일반적인 개념을 상위(부모), 구체적인 개념을 하위(자식으로 부르며, 하위에서 상위 쪽으로 속 빈 화살표 연결하여 표현
> 
> 의존관계 : 사물 사이에 연관은 있으나 필요에 의해 짧은 시간 동안만 서로에게 영향을 주고 유지하는 관계. 소유관계는 아니지만 사물의 변화가 다른 사물에도 영향을 미치며, 영향 주는 사물이 영향 받는 사물 쪽으로 점선 화살표를 연결하여 표현
> 
> 실체화관계 : 사물이 할 수 있거나 해야 하는 기능으로 서로를 그룹화할 수 있는 관계. 사물에서 기능 쪽으로 속 빈 점선 화살표를 연결하여 표현

## 다이어그램
- 사물과 관계를 도형으로 표현. 여러 관점에서 시스템을 가시화한 뷰를 제공.
- 정적 모델링 : 구조적 다이어그램
- 동적 모델링 : 행위 다이어그램

### 구조적 다이어그램
> 클래스 다이어그램 : 클래스의 속성과 클래스 사이의 관계를 표현하며, 시스템 구조 파악 및 구조상 문제점을 도출한다.  
>
> 객체 다이어그램 : 클래스에 속한 객체(인스턴스)를 특정 시점의 객체와 객체 사이 관계로 표현  
>
> 컴포넌트 다이어그램 : 컴포넌트 사이 관계나 인터페이스를 표현하며, 구현 단계에서 사용  
>
> 배치 다이어그램 : 결과물, 프로세스, 컴포넌트 등 물리적 요소들의 위치를 표현하며, 노드와 통신 경로를 표현한다. 구현 단계에서 사용  
>
> 복합체 다이어그램 : 클래스나 컴포넌트가 복합구조를 가질 시 그 내부 구조를 표현  
>
> 패키지 다이어그램 : 유즈케이스나 클래스 등 모델 요소들을 그룹화한 패키지들의 관계 표현  

### 행위 다이어그램
> 유스케이스 다이어그램 : 유저의 요구를 분석하며 기능 모델링 작업에 사용. 유저와 유스케이스로 구성되어 유스케이스 간에는 여러 형태의 관계로 이루어짐
>
> 시퀀스 다이어그램 : 상호작용하는 시스템이나 객체들이 주고받는 메시지 표현
>
> 커뮤니케이션 다이어그램 : 동작에 참여한 객체들이 주고받는 메시지와 객체 간 연관까지 표현 (시퀀스의 상휘호환)
>
> 상태 다이어그램 : 객체가 자신이 속한 클래스의 상태 변화 및 다른 객체 간 상호작용에 따라 상태 변화 표현
>
> 활동 다이어그램 : 시스템이 어떤 기능을 수행하는지에 따라 객체 처리 로직이나 조건에 따른 처리 흐름을 순서에 따라 표현
>
> 상호작용 다이어그램 : 상호작용 다이어그램 간 제어 흐름 표현
>
> 타이밍 다이어그램 : 객체 상태 변화와 시간 제약 명시적 표현