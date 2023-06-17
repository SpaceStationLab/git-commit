
<p align="center">
  <img src="https://cdn.inflearn.com/public/files/courses/328008/291d3a74-4c8a-434c-b2e3-73112724da17/328284-1.png" height="150">
</p>


## Github

지금까지 깃허브(github)는 프로젝트 코드나 블로그 글을 작성하는 혼자만의 공간이었습니다.

그렇다보니 커밋(commit) 메세지에 대한 내용을 신경쓰질 않았는데, <br>
최근 친구와 함께 일하게 되면서 커밋 메세지 통일에 대한 필요성을 느끼게 되었습니다

같이 일할 때 커밋 메세지에 신경을 쓰지 않으니 다음과 같은 문제점이 있었습니다.

  - **서로 무슨 작업을 했는지 한 눈에 보이지 않음.**
  - **상대방이 작업한 내용을 위해 코드를 반드시 읽어봐야 함.**

사람마다 메세지가 완벽하게 일치할 필요는 없지만, <br>
통일성 있게 작성하여 메세지만으로 무슨 작업을 진행했는지 확인할 수 있도록 작성하는 것이 중요합니다.

## 1. Importance of Commit Message Rules

커밋 메세지를 작성할 때 규칙이 필요한 이유는 다음과 같습니다.

- 팀원과의 소통
- 편리한 과거의 기록 추적
- 이슈(issue) 관리

## 2. Formats for Commit Messages

커밋 메세지를 작성할 때 필요한 내용들을 하나씩 정리해보겠습니다. <br>
전체적인 포맷은 다음과 같습니다.


<p align="center">
  <img src="https://blog.kakaocdn.net/dn/xteMz/btskha3GV9d/jJOTTbW8lzcKExUDpri7EK/img.png" height="250">
</p>


## 2.1. Type

해당 커밋은 무엇에 대한 작업인지 키워드를 통해 표시합니다.

<p align="center">
  <img src="https://blog.kakaocdn.net/dn/cse5PQ/btskhB1fjW4/gwAcrvaJvIdtkyf3MsB3fK/img.png" height="390">
<p>

  
## 2.2 Subject
커밋 메세지의 제목입니다.

- 제목은 50자를 넘기지 않고, 마침표를 붙이지 않습니다.
- 제목에 커밋 타입을 함께 작성합니다.
- 과거 시제를 사용하지 않고 명령조로 작성합니다.
- 제목과 본문은 한 줄 띄워 분리합니다.
- 제목의 첫 글자는 반드시 대문자로 씁니다.
- 이슈에 관련된 내용이라면 이슈 번호를 붙힙니다.

### Example of Subject

```
Feat: 신규 RFID 인식 기능 추가
```

## 2.3. Body
커밋 메세지의 본문입니다. 

- 선택 사항이므로 모든 커밋에 작성할 필요는 없습니다.
- 한 줄에 72자를 넘기면 안 됩니다.
- 어떻게(how)보다 무엇(what), 왜(why)에 집중하여 내용을 작성합니다.
- 설명뿐만 아니라 커밋의 이유를 작성할 때도 작성합니다.

### Example of Subject
```
신규 RFID 기능 인식 기능 추가
  - RFIDReader.java: 사용자 요건 사항으로 인한 RFID 인식 기능 추가
```
## 2.4. Footer
커밋 메세지의 맺음말입니다. <s>딱히 이슈없다면 뭐..</s>

- 선택 사항이므로 모든 커밋에 작성할 필요는 없습니다.
- 이슈를 추적하기 위한 ID를 추가할 때 사용합니다.
- 해결 - 해결한 이슈 ID
- 관련 - 해당 커밋에 관련된 이슈 ID
- 참고 - 참고할만한 이슈 ID

### Example of Footer
```
해결: #123
관련: #321
참고: #222
```

### Exmample of Full Commmit Message

```
Feat: 신규 RFID 인식 기능 추가(#123)

신규 RFID 기능 인식 기능 추가
  - RFIDReader.java: 사용자 요건 사항으로 인한 RFID 인식 기능 추가

해결: #123
```

### 결론 
  
커밋 메세지를 잘 작성하는 것은 협업에서 기본적인 습관입니다.

내가 다른 사람의 작업 내용을 한눈에 파악할 수 없다는 것을 알고 있다면 <br>  
다른 사람 역시 내가 작성한 커밋에 대한 내용을 파악하기 어렵다는 것을 인지해야합니다.

팀에서 함께 위와 같은 컨벤션으로 일할 수 있다면 히스토리를 파악하고 코드 리뷰도 짧은 시간 내에 해결할 수 있을 것 같다.
  

### 예시 

<p align="center">
  <img src="https://blog.kakaocdn.net/dn/dtCL21/btsklmCgFie/QDPW3LejAG0htEsJ3N628k/img.png" height="600">
</p>
