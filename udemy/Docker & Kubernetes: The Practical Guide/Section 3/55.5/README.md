# 퀴즈 3: Volumes & Bind Mount

Q1. Docker에서의 "볼륨"이란 무엇인가?

A1. 컨테이너 외부의 특정 폴더에 연결된 Docker 컨테이너 내부의 폴더/파일 이다.

<br>

Q2. 어떤 구문이 맞는가?

A2. 볼륨은 Docker에서 관리하므로, 호스트 폴더(컨테이너 내부 경로에 매핑됨)가 어디에 있는지 반드시 알 필요는 없다.

<br>

Q3. 익명 볼륨에 대한 설명으로 옳은 것은?

A3. `--rm` 으로 시작된 컨테이너가 중지되면 제거된다.

<br>

Q4. '명명된 볼륨' 의 장점은 무엇인가?

A4. 컨테이너를 제거해도 살아남는다.

<br>

Q5. '바인드 마운트'란 무엇인가?

A5. 사용자가 알고 있으며 특정한 호스트 머신 상의 경로이며, 일부 컨테이너 내부 경로에 매핑된다.

<br>

Q6. '바인드 마운트'의 일반적인 사용 사례는 무엇인가?

A6. 컨테이너에 '라이브 데이터'를 제공하려고 한다. (리빌드 필요 없음)

<br>

Q7. 익명 볼륨은 쓸모 없는 것인가?

A7. X, 외부 경로보다 컨테이너 내부 경로의 우선 순위를 높이는데 사용할 수 있다.