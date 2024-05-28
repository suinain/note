# 수업내용 필기

이곳에는 수업내용 필기를 위한 마크다운(Markdown)을 작성하는 방법을 살펴보겠습니다.

## 랜덤(Random)

랜덤은 뭐가 나올지 예측이 불가능한 값을 말합니다.  
랜덤을 만드는 방법은 여러가지가 있습니다.

1. Random이라는 도구를 생성하여 사용
2. Math.random() 명령을 사용
3. SecureRandom 도구를 생성하여 사용

여기서는 Random도구를 생성합니다.  

```java
Random r = new Random();
```

이 도구를 사용하기 위해서는 import가 필요합니다

```java
import java.util.Random;
```

import는 직접 작성하지 않고 **단축키**인 `ctrl + shift + o` 를 누릅니다  
(ctrl + shift + o같이 강조하고 싶은 블록은 인라인 코드 블록)

##랜덤 정수  추첨

생성한 도구를 이용해서 랜덤한 정수를 추첨할 수 있습니다.
단, 생성을 위해서는 범위를 정해야 합니다.

- 사람은 범위를 이야기할 때 `a`부터 `b`까지라고 합니다.
- 자바는 범위를 이야기할 떄 `a`부터 `b`개라고 합니다.

주요 랜덤값들의 범위는 다음과 같이 표현될 수 있습니다.

|항목|범위|
|:---:|:---|
|주사위|`1`부터 `6`개|
|로또|`1`부터 `45`개|
|두자리 정수|`10`부터 `90`개|  

자세한 설명은 [난수](https://ko.wikipedia.org/wiki/%EB%82%9C%EC%88%98)에서 확인할 수 있습니다  

![이미지가 엑박뜰 때 나오는 카지노이미지](https://img.freepik.com/free-vector/realistic-casino-gambling-illustration_52683-99917.jpg?size=626&ext=jpg&ga=GA1.1.1292351815.1710028800&semt=ais)


오늘도 연봉이 10원 올랐습니다.
![좋아 역시 최고야!](./.gif)
