# JHP

재획할 떄 사용할만한 것들을 모아보고 있습니다.
* youtube의 경우 화면이 일정 크기 이하일 경우 재생바, 자막 잘림이 발생합니다 (네이버 웨일에서도 발생하는걸로 봐서는 유튜브쪽 이슈인듯...)

## 현재 구현된 기능

- 영상플레이어
- 재획비 타이머

# 사용법

## HRESULT: 0x80070002 에러가 뜨는경우

https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section

설치

## 영상플레이어

![1](https://github.com/d3vdev/JHP/assets/68425571/47de287b-0afa-4ced-868f-835bce40bb17)

전반적인 UI 입니다.

![2](https://github.com/d3vdev/JHP/assets/68425571/f173b15d-d769-437e-8f3f-695cf8b8702b)

사이트 이동을 누르게 되면 위와 같은 메뉴들이 나타나게 됩니다.
기본적으로 많이 사용하는 사이트들은 추가해 놓았으며 사이트 추가 기능을 이용하면 다른 사이트들도 이용 가능합니다

![2 5](https://github.com/d3vdev/JHP/assets/68425571/5528655c-48b8-4faa-bcd1-5928227e9182)

사이트 추가를 누르면 이름과 URL 을 입력 할 수 있습니다.

## 재획비 타이머

재획비 타이머 버튼은 좌/우클릭에 따라 동작이 달라집니다
좌클릭의 경우에는 타이머를 시작/정지 하는 기능이 있으며 우클릭의 경우 알람이 필요한 버프를 선택할 수 있습니다.

### 타이머 설정

![제목 없음-6](https://github.com/d3vdev/JHP/assets/68425571/0bfd633a-4d72-4e2e-ba77-63be29a74447)

알람이 필요한 것들을 체크하면 해당 주기마다 알람이 울립니다. 
우선 기본적인 알람음은 포함되어 있으며 필요한 경우 alarm 폴더에 넣어주시고 재시작하면 목록에 나타나니 선택해서 사용하시면 됩니다.

TTS기능의 경우 해당 시점에 설정창의 위에서 부터 먼저 만족하는 버프의 이름을 알려줍니다.

# TODO
추가 되었으면 하는 기능이나 사용에 불편함이 있는 경우 issue 를 이용해 작성하여 주시거나 
im.d3v.dev@gmail.com 로 메일 보내주시면 반영해보도록 하겠습니다.