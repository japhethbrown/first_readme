# 첫번째 프로젝트
#### README.md 작성을 위한 마크다운 사용법 정리
└ 마크다운 결과 → 문법(사용법) 순서로 정리됨

|No|Items|Description|
|:--:|--|:--|
| 1 | 글자크기(제목 : Header) | 6단계 |
| 2 | 문자강조(Emphasis) | 6건(이텔릭체, 두껍게,두꺼운 이텔릭체, 취소선,단락구분, 줄바꾸기 |
| 3 | 목록표현 | 2건(순서없는 목록, 순서있는 목록, 기호를 이용한 목록 |
| 4 | 링크 | 1건 |
| 5 | 이미지넣기 | 1건 |
| 6 | 코드블럭 | 2건(코드블럭, 블럭인용)  |

# Ⅰ. 글자크기(제목 : Header)
> # 제목 1: # 제목 1
>> ## 제목 2:  ## 제목 2
>>> ### 제목 3: ### 제목 3
>>>> #### 제목 4: #### 제목 4
>>>>> ##### 제목 5: ##### 제목 5
>>>>>> ###### 제목 6: ###### 제목 6

# Ⅱ. 문자강조(Emphasis)
#### 1. 이텔릭
  1) *이텔렉체* : * 한개 별표(asterisks) *
  2) _이텔릭체_ : _ 한개 언더바(underscore) _
  3) <em>이텔릭체</em> : < em> em < /em>
#### 2. 두껍게 
  1) <strong>두껍게</strong> : < strong> 두껍게 < /strong>
  2) <b>두껍게</b> : < b> 두껍게 < /b>
  3) **두껍게** : ** 두개 별표(asterisks) **
  4) __두껍게__ :  __ 두개 언더바 (underscore) __
#### 3. 두꺼운 이텔릭체
  1) **_두꺼운 이텔릭체_** :  ** _ 두꺼운 이텔릭체 _ **
  2)  ___두꺼운 이텔릭체___ : __ _ 두꺼운 이텔릭체 _ __
#### 4. 취소선
  1) <del>취소선</del> :  < del>취소선< /del>
  2)  ~~취소선~~ : ~~ 두개 물결표시 ~~
  3)   취소선~ : ~ 한개 물결표시 ~
#### 5. 첨자(위첨자/아래첨자)
  1) <sup>위첨자</sup>Letter : < sup>위첨자< /sup>
  2) <sub>아래첨자</sub>Letter : < sub>아래첨자< /sub>
#### 6. 단락구분 (아래위 여백이 커짐 다름)
  1) <p>단락구분: < p> 단락구분 < /p> </p> 
#### 7. 줄 바꾸기 
  1) 줄바꾸기: 띄어쓰기 3칸+줄바꾸기      
     Next letter
  3) 줄바꾸기: < /br>을 이용한 줄바꾸기</br>Next letter


# Ⅲ. 목록표현
#### 1) 순서없는 목록 < ul>< li>< /li>< /ul>
  <ul>
    <li>첫번째</li>
    <li>두번째</li>
    <li>세번째</li>
  </ul>

```
<ul>
  <li>첫번째</li>
  <li>두번째</li>
  <li>세번째</li>
</ul>
```
  
#### 2) 순서있는 목록 < ol>< li></li> li>< /ol>
  <ol>
    <li>첫번째</li>
    <li>두번째</li>
    <li>세번째</li>
  </ol>
  
```
<ol>
  <li>첫번째</li>
  <li>두번째</li>
  <li>세번째</li>
</ol>
```

#### 3) 기호를 이용한 목록 (*,+,-)
* 1단계
  - 2단계
    + 3단계
      + 4단계
```
* 1단계
  - 2단계
    + 3단계
      + 4단계
```



# Ⅳ. 링크
#### 1) 링크연결
마크다운 설명이 잘 정리된 git은 <a href="https://gist.github.com/ihoneymon/652be052a0727ad59601" title="gist.github.com">여기</a>를 참조.

```
마크다운 설명이 잘 정리된 git은 <a href="https://gist.github.com/ihoneymon/652be052a0727ad59601" title="gist.github.com">여기</a>를 참조.
```
# Ⅴ. 이미지 넣기
<img src="https://github.com/japhethbrown/1st/assets/144292488/b2d6d9f8-c826-4210-809a-99feda561482" width="150px" title="px(픽셀) 크기 설정" alt="git logo"></img>

```
<img src="https://github.com/japhethbrown/1st/assets/144292488/b2d6d9f8-c826-4210-809a-99feda561482" width="150px" title="px(픽셀) 크기 설정" alt="git logo"></img>
```

# Ⅵ. 코드블럭
#### 1. 코드블럭
```
#1) 코드블럭 : ``` 코드블럭 ```
```
<pre><code>#2) 코드블럭: < pre>< code> 코드블럭 2 < /code>< /pre> </code></pre>

#### 2 블럭인용
> 블럭인용 1단계 ( >)
>> 블럭인용 2단계 ( >>)

# Ⅶ. 마크다운 Emoji 이모티콘
출처 : <a href="https://inpa.tistory.com/entry/MarkDown-%F0%9F%93%9A-Emoji-%EC%9D%B4%EB%AA%A8%ED%8B%B0%EC%BD%98-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0" title="Inpa Dev"> Inpa Dev </a>

기호( : : ) 사이에 이모티콘명을 넣으면 자동으로 인식</br>
예) :rocket: ← : rocket :

|_**이미지**_|_코드_|_**이미지**_|_코드_|_**이미지**_|_코드_|
|:--:|--|:--:|--|:--:|--|
|😄|: smile:|😆|: laughing:|😊|: blush:|
|😃|: smiley:|😀|: grinning:|😏|: smirk:|
|😍|: heart_eyes:|😘|: kissing_heart:|😚|: kissing_closed_eyes:|
|😳|: flushed :|😌|: relieved:|😆|: satisfied:|
|😁|: grin:|😉|: wink:|😜|: stuck_out_tongue_winking_eye:|


