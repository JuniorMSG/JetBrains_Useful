# JetBrains_Useful

JetBrains IDE를 잘 써보자

## 이거 진짜 좋아요 2022.12월 버전

### Relate Symbol

| 단축키                | Preference KeyMap Info |
|--------------------|------------------------|
| CMD + CTRL + 위 화살표 | Main Menu              | Code | Code Completion | Cyclic Expand Word                      |

    CMD + B 처럼 코드 탐색(navigation) 탭에 있는 단축키 입니다.

    Main Menu | Navigate | Goto by Reference Actions | Go to Declaration or Usages
    CMD + B 는 현재 사용된 메소드의 상위를 추적하죠?
    
    Main Menu | Edit | Find Usages | Find Usages
    OPT + F7은 현재 사용된 메소드가 어디서 사용된지 추적합니다.
    CMD + OPT + B 로 바로 찾을 수도 있구요

    Main Menu | Navigate | Goto by Reference Actions | Related Symbol...
    Relate Symbol은 관련 추적내용과 관련있는? 비슷한 상징으로 된걸 추적해주는 단축키에요
    route

#### 컨트롤러

    컨트롤러에서 사용시 관련된 모델, 뷰, 레이아웃 위치, 스키마, 라우트 정보, 데이터베이스 조회까지 다양한 정보를 바로 찾아갈 수 있습니다.

![image](https://user-images.githubusercontent.com/22822369/209290146-1949f633-a733-45b6-85f0-865e52667469.png)

#### Routes.rb에서 추적할 경우

    컨트롤러를 바로 찾아줍니다. / 컨트롤러에서 Routes로 찾으면 바로 찾아는 그곳으로 가지죠!

#### View

    view에서 사용할 경우 해당 화면이 호출된 컨트롤러로 가집니다. 

### Cyclic Expand Word

| 단축키                                             | Preference KeyMap Info |
|-------------------------------------------------|------------------------|
| OPT + / 정방향 (앞) / && OPT + SHIFT + / 역방향 (뒤) 복사 | Cyclic Expand Word     |

    무언가 썻던 글을 반복하고 싶을떄 사용하는 단축키로써~~ 
    단축키로써를 다시 다시2 입력해야한다면 복사해야 하는 귀찮음이 있겠죠?~
    단 + OPT + / 를 입력한다면 반복 입력을 하지 않아도 됩니다! 영단어도 마찬가지! 

## MD 파일 작성 팁

| 단축키          | 기능                 | 언제쓰면 좋은가요?                           |
|--------------|--------------------|--------------------------------------|
| CTRL + ENTER | 여러가지 편리한 기능이 제공된다. | 링크 / 테이블 / 이미지 / README 파일 구조 자동 생성떄 |

## 복사 / 붙여넣기

| 단축키                       | 기능                     | 언제쓰면 좋은가요?                              |
|---------------------------|------------------------|-----------------------------------------|
| CMD + D                   | 줄 복사 / 현재 줄 그대로 복사함    | IDE 내부에서 줄복사 할 떄  여러줄 지정하면 여러줄 복사됨      |
| CMD + BackSpace / CMD + X | 줄 삭제 / 즐 잘라내기          | 지울때 / 지우고 어딘가에 붙여넣을때                    |
| CMD + C                   | 현재 줄 클립보드에 복사          | IDE 외부에다가 데이터 복사할떄 따로 줄 선택 안해도 한줄 복사 가능 |
| OPT + /                   | 현재 단어로 시작하는 최근 단어 복사하기 | 이것 저것 편리하던데요                            |

## 코드 정리

| 단축키            | 기능                         | 언제쓰면 좋은가요?                      |
|----------------|----------------------------|---------------------------------|
| CMD + OPT + L  | 줄 자동 정렬                    | DB 쿼리를 어딘가에서 가져왔다 혹은 여러 정렬 사용할떄 |
| CMD + G        | 현재 코드랑 똑같은 코드 선택           | 변수 선택할떄?                        |
| CMD + CTRL + G | 현재 코드랑 똑같은 코드 전체 선택        | 변수 전체 수정시                       |
| SHIFT + F6     | 연관된 (호출한) 부분 코드까지 다 고치는 방법 | 연관된 클래스 포함 전체 수정시               |

## Navigation

| 단축키                        | 기능                                 | 언제쓰면 좋은가요?               |
|----------------------------|------------------------------------|--------------------------|
| CTRL + L                   | 특정 줄로 빠르게 이동하고 싶을 떄                | 특정 줄로 빠르게 이동하고 싶을 떄      |
| CMD + [] / CMD + Shift + e | 최근 작업 내역으로 이동 / 최근 작업 내역 보기        | 왔다갔다 하다가 최근 작업 내용으로 이동할때 |
| CMD + Shift + []           | 상단 탭 좌우로 이동하기                      | 상단탭 좌우로 이동하고싶을때..        |
| CMD + `                    | 여러개의 루비마인, 인텔리제이가 떠있을때 서로 전환 하는 기능 | 2개의 프로젝트를 띄워두고 전환할떄?     |

## Search

| 단축키                                       | 기능                        | 언제쓰면 좋은가요?                  |
|-------------------------------------------|---------------------------|-----------------------------|
| CMD + SHIFT + \                           | 전체 검색에서 URL 검색하는 방법       | 특정 URL 경로 찾고싶을 때            |
| CMD + F  / CMD + SHIFT + F                | 해당 화면 검색 / 전체 검색          | 특정 문자열 검색                   |
| SHIFT + SHIFT / CMD + O / CMD + SHIFT + O | 전체 파일 검색 / 클래스 검색 / 파일 검색 | 한개의 화면에 탭만 다름 각 검색용으로 쓰면 좋음 |
|||

## Settings / 정리

| 단축키           | 기능       | 언제쓰면 좋은가요?               |
|---------------|----------|--------------------------|
| CMD + OPT + L | 코드 정렬    | DB / Readme 파일 정리할때 좋습니다 |
| CMD + ,       | 세팅창 바로켜기 | 세팅창을 바로 키고싶을때 사용합니다.     |

## Plugin

    jojoldu - Translation
    Presentaion Assistant
    Rainbow Bracket
    CodeGlance~~~
    GitToolBox

## ETC

Meta Key Icon과 명칭

+ 키 조합 (한 번에 같이 누른다.)    ⇢
+ 다음 단계 키 누르기
+ ⌘ Mac Command Key
+ ⌃ Mac Control Key
  ⌥ Mac Option Key (Alt)
+ ⇧ Mac Shift Key
+ ⇪ Mac Capslock Key
+ ↩ Mac Return
  ⭠ 화살표 왼쪽 ⭢ 화살표 오른쪽 ⭡ 화살표 위 ⭣ 화살표 아래