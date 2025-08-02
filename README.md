<div align="center">
  <div>
    <img width="250" src="./images/quotations-book.png"/>
    <h2>📕 명언 백과사전</h2>
    <p>감명 깊은 명언, 문장 등을 수집합니다.</p>
  </div>
  <div>
    <img src="https://img.shields.io/badge/version-1.0.0-blue?style=flat-square" alt="template version"/>
    <a href="https://github.com/onealand/quotations-book/blob/main/LICENSE" target="_blank">
      <img src="https://img.shields.io/github/license/onealand/quotations-book?style=flat-square"/>
    </a>
  </div>
</div>

<br>

# 📕 명언 백과사전

살면서 와닿은 문장이나 명언이 있으셨나요? 감명 깊었던 문장이 있다면 이 곳, 명언 백과사전에 추가해보세요.  
여러분의 눈길을 멈추게 한 소중한 문장이 다른 누군가의 눈길을 멈추게 할 수 있어요.

<br>

## 🙌 명언 백과사전에 기여하는 방법

### 1. 해당 레포지토리를 Fork하고 Clone하기

- 해당 레포지토리를 먼저 Fork 합니다.
- Fork한 레포지토리를 Clone하여 작업 준비 상태를 만듭니다.

### 2. 브랜치 만들기

- `<theme>/<name>` 형식으로 브랜치를 만듭니다.
- `<theme>`은 문장의 주제와 관련된 단어를 작성합니다.
- `<name>`은 작성하고자 하는 문장을 말한 인물 또는 문장의 핵심적인 단어를 사용합니다.
- 띄어쓰기를 구분할 때는 대시(`-`)를 사용합니다.

```
ex) heart/i-ask-you
```

### 3. 명언을 작성할 README.md 파일 만들기

- `theme` 디렉터리에 작성할 명언의 주제에 해당하는 하위 디렉터리를 선택합니다.
- 만약 명언에 해당하는 주제가 없다면 영문으로 새로 디렉터리를 만듭니다.
- 하위 디렉터리에 `<name>.md` 형식으로 파일을 만듭니다.
- `<name>`은 명언의 제목 또는 핵심적인 단어로 정합니다.
- 띄어쓰기를 구분할 때는 대시(`-`)를 사용합니다.

```
ex)
├── .github/
├── images/
├── theme/
│   ├── heart/
│   │   └── i-ask-you.md
│   ...
...
```

### 4. 명언 작성하기

- 생성한 README.md 파일에 명언(또는 감명 깊은 문장)의 제목 그리고 명언을 말한 사람(출처)을 괄호 안에 작성합니다. 없거나 모른다면 작성하지 않습니다.
- 제목 아래에 나머지 문장을 한글로 작성하고 커밋합니다.
- 한글로 작성한 명언 아래에 영어로 번역한 문장을 입력하고 커밋합니다.
- 문장이 여러 줄이면 한 줄 단위로 커밋을 실행하여 최대한 여러 개의 커밋을 시도합니다.
- 다음은 커밋 메시지 규칙입니다. 해당 규칙에 따라 커밋 메시지를 입력합니다.

```bash
커밋 메시지 규칙
[ADD]: message # 텍스트 추가했을 때 커밋메시지
[FIX]: message # 텍스트 수정했을 때 커밋메시지
[DELETE]: message # 불필요한 텍스트를 삭제했을 때 커밋메시지
[CHORE]: message # 위 해당 사항이 아닌 경우

ex)
[ADD]: 너에게 묻는다 제목 추가
[ADD]: 너에게 묻는다 문장 추가
[FIX]: 오탈자 수정
[DELETE]: 불필요한 단어 제거
[CHORE]: 파일 제목 변경
...
```

### 5. Main의 README.md에 작성한 명언 남기기

- 아래 [명언 미리보기](#-명언-미리보기)에 해당하는 주제 아래에 본인이 작성한 문장의 파일을 링크로 연결합니다.

```
ex)
'마음' 밑에 다음과 같이 작성하고 커밋합니다. (문장 마지막에 마침표는 찍지 않습니다)
- [연탄재 함부로 발로 차지 마라. 너는 누구에게 한번이라도 뜨거운 사람이었느냐](./theme/heart/i-ask-you.md)
```

### 6. Pull Request 생성하기

- 커밋을 모두 마쳤다면 `git push origin <branch-name>`을 입력하여 Fork한 레포지토리에 업로드합니다.
- 해당 레포지토리의 `main` 브랜치로 병합을 시도하는 PR을 생성합니다.
- 커밋 메시지, 파일 등 본인 작업물을 최종 점검합니다.
- PR 본문의 규칙을 확인하고 따릅니다.

### 7. 최종 반영 기다리기

- 조금만 기다려 주세요! 코드리뷰 이후에 더 이상 고칠 게 없다면 `Approve`를 드립니다.
- 이후 최종적으로 `main` 브랜치에 병합(Merge)할 수 있습니다.

<br>

# 👀 명언 미리보기

## 마음

- [연탄재 함부로 발로 차지 마라. 너는 누구에게 한번이라도 뜨거운 사람이었느냐](./theme/heart/i-ask-you.md)

<br>

## 사랑

<br>

## 우정

<br>

## 인생

- [자신을 변화시키는 가장 빠른 방법은 이미 자신이 원하는 모습으로 변한 사람들과 어울리는 것입니다.](./theme/life/change-yourself.md)

 [하루하루를 어떻게 사느냐가 인생을 결정한다.](./theme/life/Annie-Dillard.md)

<br>

## 조화

- [행복한 가정은 모두 비슷한 이유로 행복하지만 불행한 가정은 저마다의 이유로 불행하다](./theme/harmony/anna-karenina.md)

<br>

## 투자

- [방망이를 짧게 잡아라](./theme/investment/hold-the-bat-short.md)

<br>

# 👥 Contributors

<a href="https://github.com/onealand/quotations-book/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=onealand/quotations-book"/>
</a>

<br>

# 라이센스

해당 프로젝트는 MIT 라이센스를 따릅니다.
