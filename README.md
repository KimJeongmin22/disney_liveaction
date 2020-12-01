# 디즈니 실사영화 분석: 뮬란의 몰락

학번: 201801040 이름: 김정민

#### 진행상황
- 데이터수집(完) + 형태소분석(完) + 피벗테이블(完) 
- 'Q1_디즈니의 실사 영화는 흥행 보증수표인가?'에 대한 답변으로 이상한나라의앨리스/정글북/미녀와야수/알라딘의 흥행요소 분석 (完)
- 'Q2_실사 영화에 대한 관객들의 기대요소' (完)

#### 앞으로의 과제
- Q3_디즈니 실사 영화의 차별점 (ex. 캐릭터의 매력도, 인물관계 ...)
- Q4_뮬란은 왜 실패했는가 (기존 영화들과 비교)
- Q5_차기 실사 영화 제작의 주의점

----------------------------------------------------------------------------------------------

#### 대상데이터 (네이버 영화 평점 및 리뷰)
- 뮬란 (4,500개) 
- 알라딘 (27,100개)
- 미녀와 야수 (17,800개)
- 정글북 (7,700개)
- 라이온킹 (9,200개)
- 이상한 나라의 앨리스 (5,800개)

----------------------------------------------------------------------------------------------

#### 분석방법
: KoNLPY 한글 현태소 분석기 + 피벗테이블 생성

----------------------------------------------------------------------------------------------

### Q1_디즈니 실사 영화는 홍행 보증 수표? (각 영화의 흥행요인 분석)
*순서는 흥행순으로 나열

#### 알라딘 (2019.05.23 / 평점 9.42 / 1,272만명)
- 캐릭터와 캐스팅

  알라딘 배역 중 당연 돋보이는 것은 파란색 피부와 자유자재로 모양새를 움직이는 지니일 것이다. 관람객들 역시 지니의 역할에 주목했고, 특히나 이 역할을 맡은 윌 스미스의 캐릭터 소화력을 언급하며 높은 점수를 주었다. 그 밖에도 공주역의 나오미 스캇과 악당 자파 또한 역할에 동기화 된 연기력으로 영화의 몰입에 영향을 주었다.
 
- 노래

  영화 알라딘은 21개의 OST가 실린 앨범이 따로 발매될 정도로 한국에서 OST로 큰 사랑을 받았다. 관람객들의 리뷰에서 'Whole new world' 와 'Speechless'는 가장 높은 언급률을 보였는데, 알라딘의 흥행 요인에 OST 얼마나 큰 영향을 미쳤는지 알 수 있다. 특히 공주의 캐릭터에 입체감을 주어 더욱 사랑을 받았던 'Speechless'는 따로 해시태그(#speechless)까지 만들어졌음을 알 수 있다.

#### 미녀와 야수 (2017.03.16 / 평점 8.99 / 515만명)
- 뻔하다, 지루하다, 허무했다

  미녀와 야수는 고전적인 공주 이야기 중 하나이다. 이러한 이유 때문인지 뻔한 스토리와 결말, 흥미에 대해 아쉬움을 토로한 관람객들이 많았다.
  
- 엠마왓슨

  해리포터의 헤르미온느 역할로 유명한 '엠마왓슨'의 공주 역할은 이목을 끌기 충분했다. 예상 가능한 이야기에도 불구하고 엠마왓슨의 미모는 공주와 거의 100% 일치된 싱크로율을 보였다. 또한 관람객들이 생각하는 엠마왓슨의 선한 성격을 공주의 역할에 투영해 만화와 실사의 괴리를 줄여주었다.  
  
- OST

 오케스트라, 클래식 (추후 추가)

#### 라이온킹 (2019.07.17 / 평점 8.64 / 474만명)
- 신선함

  오롯이 동물만이 주인공이 되어 이야기를 펼쳐가는 라이온킹은 3년 전 개봉했던 정글북과 비슷한 결을 지니고 있다. 그러나 라이온킹은 한층 더 구체적인 실사를 그려내 관람객들에게 신선함을 가져다 주었다. 

- 감동과 추억

   이 영화는 다른 영화들과 다른 점이 하나 있다. KoreanParticle에서 'ㅠㅠ'의 비율이 압도적으로 많았다. 이는 애니메이션 라이온킹을 보고자란 세대의 추억과 향수를 불러일으킴과 함께 그들의 감정을 자극하는 데 성공했음을 알 수 있따.
 
 - OST

#### 정글북 (2016.06.09 / 평점 8.57 / 253만명)
- 힐링, 흐뭇함

  정글북은 작은 소년과 자연을 배경으로 하고 있다. 한 소년의 성장기를 담은 이야기인 만큼 이야기의 다이나믹한 변동은 없지만 동화 내용을 흐뭇하게 떠올리게 해준 영화에 관람객들은 훈훈함을 느꼈다. 

- 호랑이, 흑표범, 흑곰

  이전까지 동물이 큰 비중을 차지하며 실사화 된 영화가 많지 않았기 때문에 관람객들은 실사화 된 동물의 모습에 관심을 보였다.

- 추억

  정글북과 같이 자연을 배경으로 한 애니메이션은 다른 실사화 영화에 비해 긴장감과 박진감은 다소 부족할 수 있다. 따라서 지루하다는 의견과 추억을 상기시켜 재미있었다는 평가, 이 두가지가 극명하게 갈려 호불호가 큰 편이다.

#### 이상한 나라의 앨리스 (2010.03.04 / 7.55 / 214만명)
- 팀 버튼과 조니뎁

  많은 관람객들은 최정상 감독과 최정상 배우의 만남에 기대를 보였다. 

- 캐릭터

  이상한 나라의 앨리스는 제목처럼 독특한 캐릭터들이 많이 등장한다. 그 중 하트여왕과 모자장수의 신비한 생김새는 기괴한 내용과 잘 어우러져 가상세계의 분위기를 더욱 심화시켰다.
  
- 판타지, 상상력

  유달리 판타지적 요소가 많은 이 영화는 다양한 색감과 색채로 상상력을 자극시켰다. 


### Q2_디즈니 실사 영화에 대한 관객들의 기대? (영화 간 공통점)
*각 영화의 평론들을 분석해 본 결과 공통적으로 나타나는 부분들이 존재했다.  

1. 동화 속의 내용을 영화화하는 것인 만큼 관람객들은 미리 대본을 알고 있는 것이나 마찬가지이다. 이 때문인지 리뷰 속 오글거린다, 뻔하다는 의견을 항상 빠지지 않고 등장했다. 그러나 다른 시각으로 동심을 회상하게 한다는 의견도 자주 발견했다.
2. 뻔한 이야기가 되느냐 동심을 회상하는 이야기 되느냐는 당연 그래픽의 영향을 받는다. 아마 디즈니 실사 영화에서 관객들이 가장 기대하는 부분이 이 부분일 것이다. 내가 동화속에서 읽었던 그 장면이 화면에서는 어떻게 나타날 건지, 어떻게 CG로 구현될 것인지 궁금해 한다.
3. 이러한 기대는 바로 막대한 디즈니의 제작비와도 상관이 있다. 대부분의 리뷰에서는 '이 영화에 얼마가 투자되었는데...'하는 제작비를 거론하는 평론들을 쉽게 찾아볼 수 있다. 그래도 디즈니인데, 이만큼이나 투자를 했는데 하는 마음에 관람객들으 실사 영화에 더욱 기대를 갖는다. 
4. KoreaParticle을 분석해 본 결과 'ㅋㅋ'과 'ㅠㅠ'가 가장 빈번하게 사용되었다. 빈도수와 동사(verb, verbperfix)를 함꼐 적용해 해석하면 디즈니 영화는 재미와 감동을 모두 선사한다. 따라서 기본적으로 디즈니 실사 영화를 보는 관람객들은 재미는 물론 감동까지 받을 수 있길 기대한다.
