# flexbox-practice

## 목차

1. flexbox의 구성
2. flexbox 만드는법
3. flex container 속성
4. flex item 속성

## flexbox의 구성

- flexbox는 자식요소인 flex item과 부모 요소인 flex container로 구성된다.

## flexbox 만드는법

- 정렬하려는 요소의 부모요소에 다음과 같이 선언하면 된다.

<pre><code>
.flex_container{
    display : flex; 
}
</code></pre>

## flex container 속성

### flex-direction

#### 기본 정의

- flexbox의 주축을 설정한다.

#### 속성값

- row: 주축을 행으로 정렬합니다.
- row-reverse: 주축을 행 반대방향으로 정렬합니다.
- column: 주축을 열로 정렬합니다.
- column-reverse: 주축을 열 반대방향으로 정렬합니다.

#### 예시

<pre><code>
.flexbox-container{
  display:flex;
  flex-direction: row; 
}
</code></pre>

### justify-content

#### 기본 정의

- flexbox 정렬되는 위치를 설정한다.

#### 속성값

- flex-start: 아이템들이 주축의 왼쪽으로 간다.
- flex-end: 아이템들이 주축의 오른쪽으로 간다.
- center: 아이템들이 중앙으로 간다.
- space-between: 아이템들 사이사이에 일정한 공백이 주어진다.
- space-around: 아이템들에게 일정한 공백이 주어진다.

#### 예시

<pre><code>
  .flexbox-container{
    display:flex;
    justify-content: flex-start;
  }
</code></pre>
