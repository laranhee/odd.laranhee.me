---
sidebar_position: 0
---

# macOS 한영 전환이 씹히는 현상 막기

### 개요

`Caps Lock`을 눌렀을 때 다른 키가 눌린 것으로 인식하게한다. (`Caps Lock`의 영대문자 고정 기능은 쓰지 않는다)

`Caps Lock`을 눌렀을 때 인식되는 다른 키를 macOS의 한영 전환 단축키로 지정한다.

### 방법

#### Karabiner-Elements 설치

https://karabiner-elements.pqrs.org/

#### Karabiner-Elements > Simple modifications > Add item

`Caps Lock`을 누르면 `F18`이 눌러지도록 설정

(왜인지는 모르나 정상적으로 동작하지 않는 키도 존재, F18은 항상 안정적이었음)

![](./settings01.png)

#### macOS > 시스템 환경설정 > 키보드 > 단축키 > 입력 소스

`입력 메뉴에서 다음 소스 선택`을 `Caps Lock`로 지정하면 `F18`로 설정됨

![](./settings02.png)

