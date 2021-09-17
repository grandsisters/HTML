## HTML YouTube 동영상
HTML로 동영상을 재생하는 가장 쉬운 방법은 YouTube를 사용하는 것입니다.

***
### 비디오 형식으로 어려움을 겪고 계십니까?
비디오를 다른 형식으로 변환하는 것은 어렵고 시간이 많이 소요될 수 있습니다.

더 쉬운 해결책은 YouTube가 웹 페이지에서 동영상을 재생하도록 하는 것입니다.

***
### YouTube 동영상 ID
YouTube는 동영상을 저장(또는 재생)할 때 ID(예: tgbNymZ7vqY)를 표시합니다.

이 ID를 사용하고 HTML 코드에서 동영상을 참조할 수 있습니다.

***
### HTML로 YouTube 동영상 재생
웹 페이지에서 비디오를 재생하려면 다음을 수행하십시오.

- YouTube에 동영상 업로드
- 비디오 ID를 기록해 둡니다.
- \<iframe>웹 페이지에서 요소 정의
- 송출 src비디오에 특성 포인트를 URL
- 사용 width및 height플레이어의 차원을 지정하는 속성
- URL에 다른 매개변수를 추가합니다(아래 참조).

        예시
        <iframe width="420" height="315"
        src="https://www.youtube.com/embed/tgbNymZ7vqY">
        </iframe>

***
### YouTube 자동재생 + 음소거

autoplay=1을 YouTube URL에 추가 하여 사용자가 페이지를 방문할 때 동영상이 자동으로 재생되도록 할 수 있습니다. 

그러나 비디오를 자동으로 시작하는 것은 방문자에게 성가신 일입니다!

    참고: Chromium 브라우저는 대부분의 경우 자동 재생을 허용하지 않습니다. 그러나 음소거된 자동 재생은 항상 허용됩니다.

비디오가 자동으로 재생되기 시작하려면 mute=1뒤에 추가 autoplay=1하세요(음소거됨).

    YouTube - 자동 재생 + 음소거
    <iframe width="420" height="315"
    src="https://www.youtube.com/embed/tgbNymZ7vqY?autoplay=1&mute=1">
    </iframe>

***
### 유튜브 재생목록
재생할 동영상의 쉼표로 구분된 목록(원본 URL 추가).

***
### YouTube 루프
loop=1비디오가 영원히 반복되도록 추가하십시오 .

값 0(기본값): 비디오가 한 번만 재생됩니다.

값 1: 비디오가 (영원히) 반복됩니다.

    YouTube - 루프
    <iframe width="420" height="315"
    src="https://www.youtube.com/embed/tgbNymZ7vqY?playlist=tgbNymZ7vqY&loop=1">
    </iframe>

***
### YouTube 컨트롤
controls=0을 비디오 플레이어에서 컨트롤을 표시하지 않으려면 추가하십시오 .

값 0: 플레이어 컨트롤이 표시되지 않습니다.

값 1(기본값): 플레이어가 디스플레이를 제어합니다.

    YouTube - 컨트롤
    <iframe width="420" height="315"
    src="https://www.youtube.com/embed/tgbNymZ7vqY?controls=0">
    </iframe>