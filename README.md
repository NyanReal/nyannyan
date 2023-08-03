# nyannyan
냥냥대작전

![](https://github.com/NyanReal/nyannyan/blob/main/AI%20Concept/KakaoTalk_20230728_233626000.png?raw=true)



# Stable Dittusion
## Prompt
### 강조 수식어
* Extreme 
* Ultimate
* Hyper
* Unprecedented : 전례없는
* Best
* Supreme
* Ultra
* Intense : 강렬한
* Powerful
* Unmatched : 무적의
* Unrivaled : 경쟁에서 압도하는
* Exceptional : 탁월한
* Unsurpassed : 압도적인
* Remarkable : 주목할 만한
* Strong : 강한
* Mighty : 강력한
* Vigorous : 활기찬
* Robust : 튼튼한
* Normal : 정상의
* Weak : 약한
* Feeble : 연약한
* Inadequate : 부족한
* Insufficient : 부족한
* Powerless : 무력한
* Impotent : 힘이 없는
* Frail : 연약한
* Fragile : 깨지기 쉬운
* Delicate : 섬세한
* Debilitated : 쇠약한


### 품질
* masterpiece : 심혈을 기울인(?!) 명작.
* best quality : 최고 품질
* highres : 고해상도
* dslr : DSLR 카메라로 찍은 듯한 품질
* photorealistic : 사진처럼 리얼한
* 4k
* 8k
* uhd : 각각 해상도급 대응
* extremelyy detailed CG : 극도로 정교한
### 스타일
* realistic : 사실적인
* photograph : 사진
* painting : 그림, 회화 
* game cg : 게임같은
* cartoon : 만화
* oil painting : 유화
* 3d, 3d render : 3D 렌더링 이미지

### 조명
* tyndall effect : 후광이나 발광 같은... (검색해보는게 빠름)
* soft lighting : 부드러운 조명
* volumetric lighting : 체적의(?!) 조명광
* beautiful lighting : 아름다운 조명
* warm lighting : 따뜻한 조명 

### 캐릭터
#### 캐릭터의 시선 (feat 나밍센세)
* looking_up
* looking_down
* looking_away : 시선을 멀리
* looking_far
* looking_at_viewer : 카메라를 바라봄

#### 캐릭터 표현 부위
* face : 얼굴만
* upper_body : 상체
* lower_body : 하체
* portrait : 초상화
* full body : 전신
* wide_shot : 멀리서 전신 (이미지가 가로로 길 경우)

#### 캐릭터 체형
* muscle : 근육질
* fat : 뚱뚱한 체형
* skinny : 마른 체형

#### 머리
* short hair : 단발
* medium hair : 중단발
* long hair : 긴머리 (보통 허리까지 오더이다)
* ponytail
* twin vraided : 양갈래 땋은머리
* Drill Hair
* Wavy Hair : 웨이브진 머리
* twintail
* Two side up : 땋아서 올린 머리
* bangs : 앞머리
* forhead : 넘긴머리

#### 표정 (fead 나밍센세)
* blank : (센세 참고 이미지상 경멸하는듯한?)
* happy
* suprised
* distressed
* sleppy
* sad
* angry
* embrassed


#### 옷
우선 생략....


## Negative
* nsfw (Not safe for work) : 후방주의
* simple background : 단순한 이미지는 제외할 때
* lowres : 저해상도
* bad hands : ai 유일하게 손 모양이 이상하게 나오는 경우가 많음. 이상한 손이 안 나오게 하는 단어.
* text : 이미지내에 text가 섞이는 경우가 많음
* error : 에러 차단
* missing fingers :  bad hands처럼 손가락의 모양과 수 오류가 많음.
* fewer fingers :  손가락 수가 적은
* strange fingers :  이상한 손가락
* extra digit :  missing fingers와 비슷한 개념 너무 많은 손가락 제외할 때
* fewer digits :  너무 적은 손가락 제외할 때
* cropped :  이미지 잘리지 않게 하기 위해서…
* worst quality :  저퀄리티가 아니게 출력하기 위해서…
* signature :  그림 서명은 제외할 때…
* watermark :  워터마크 또한 제외합니다.
* username :  사용자 이름
* blurry :  (이미지가) 희미하거나 더러운…
* bad anatomy :  해부학에 맞지 않은
* jpeg artifacts :  jpeg 이미지에 생기는 가장자리의 노이즈(깨지는) 부분
* ugly :  추한
* pregnant :  임신한
* vore :  ‘어떤 캐릭터가 다른 캐릭터를 먹는다’는 의미로 잔인하거나 혐오스런 이미지가 나올 수 있음
* duplicate :  복제(복사)한
* mutilated :  훼손된..
* missing legs :  다리가 없는
* missing arms :  팔이 없는
* extra arms :  여러개의 팔
* pubic hair :  음모
* plump :  통통한
* bad legs :  이상한 다리
* error legs :  잘못된 다리
* bad feet :  이상한 발가락
* mutation :  돌연변이
* transexual :  성전환의
* bad proportions :  (나쁜)크기 , 비율에 안 맞는…
* nipples :  젖꼭지
* glans :  귀두
* bare thighs :  발가벗은, 노출시키는
* naked :  발가벗은, 노출시키는
* disfigured :  흠이 있는
* bad art :  나쁜 그림
* deformed :  변형된
* extra limbs :  추가된 팔다리
* long neck :  긴 목
* cross-eye :  교차, 중복된 눈
* moles :  사마귀, 검은점(들)

## 가중치

* (프롬프트) : 괄호안의 내용 가중치 1.1배. ((프롬프트)) 의 경우 1.21배.
* (프롬프트:n) : 괄호안의 내용 가중치 n배. 0.8~1.5 권장.
* [프롬프트] : 괄호안의 내용 가중치 1.0 / 1.1 배. (0.909...배)
* [프롬프트1|프롬프트2|....|프롬프트n] : 혼종 만드는 용도.... 매 스탭 진행할 때마다 해당 프롬프트들이 섞임.
* [word1:word2:0.5] : 전체 20스텝이면 word1을 10스텝(50%)을 그리고 나머지 스텝은 Word2를 그리는 것을 전환합니다.
* [word1:word2:11] : 전체 스텝 상관없이 word1을 11스텝을 그리고 그 다음부터 word2를 그립니다.
* [word1::13] : word1을 13스텝을 그리고 그 다음은 프롬프트없이 그립니다.
* 프롬프트1 AND 프롬프트2 : ''대문자 AND'' 를 기준으로 개념을 섞어서 이미지 생성. (이것도 혼종용)

## Lora Trigger
* <lora:체크포인트명:계수> : 해당 체크포인트 Lora를 계수만큼 적용.



