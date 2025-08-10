## Firebase / Google Anaylitics

#### [화면 조회수 추적 사용 중지](https://firebase.google.com/docs/analytics/screenviews?hl=ko#disable_screenview_tracking)
Single Activity 기반의 애플리케이션이다. 액티비티를 기준으로 추적하는 화면 전환 이벤트 기능을 끄고 수동으로만 추적할 순 없을까?

## Deep link, App link, Universal link, Web link, Dynamic link  

링크 클릭 시 특정 화면으로 이동하거나, Android에서는 플레이 스토어로, iOS에서는 앱 스토어로 이동 시키는 요구사항이 종종 등장한다. Android 및 iOS에서는 이를 충족시키는 여러 종류의 링크를 구현할 수 있다. 링크 종류에 대해 명확히 이해하고 사용하는 것은 소통 및 사용성 향상에 도움이 된다.

#### [Android 앱 링크 처리하기](https://developer.android.com/training/app-links?hl=ko)
Android에서 Deep link, Web link, App link 의 기본 개념과 사용 방법에 대해 설명한다.

#### [링크의 모든것(feat. App Link, Universal Link, Deferred DeepLink)](https://medium.com/prnd/%EB%94%A5%EB%A7%81%ED%81%AC%EC%9D%98-%EB%AA%A8%EB%93%A0%EA%B2%83-feat-app-link-universal-link-deferred-deeplink-61d6cf63a0a5)  
[박상권님 블로그] Uri scheme 방식 및 link 가 변화해 온 과정. 

## Android build system

#### [안드로이드, 어디까지 아세요 [1] - Build process](https://medium.com/mj-studio/%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C-%EC%96%B4%EB%94%94%EA%B9%8C%EC%A7%80-%EC%95%84%EC%84%B8%EC%9A%94-1-build-process-df6a69f73337)

## Compose

#### [LayoutNode: What Actually Happens When You Write @Composable](https://proandroiddev.com/layoutnode-what-actually-happens-when-you-write-composable-05c0275875fa)
레이아웃을 표현하는 Composable (Text, Column, ...) 함수는 결국 LayoutNode로 표현된다. 그렇다면 이 Layout은 내부적으로 어떻게 동작할까? 나는 이 글을 이해했다는 가장 확실한 증거는 커스텀 레이아웃 즉, MeasurePolicy를 구현해보는 것이라 생각한다.

#### 

## Recomposition

#### [Jetpack Compose 성능 최적화를 위한 Stability 이해하기](https://velog.io/@skydoves/compose-stability#immutable-collections)
[엄재웅님 블로그]

#### [Compose stability tips and tricks](https://leedwon.github.io/posts/Compose-stability-tips-and-tricks/)
팀원으로부터 이 컴포저블은 이미 Stable한 것이 아닌가? 하는 질문을 받았다. LayoutInflator를 확인하는 것 말고도 이것을 확인할 수 있는 방법이 있을까? 이 글에서는 안정성을 체크하고 수정하는 방법에 대해 설명한다.

#### [mutableStateOf(list) vs mutableStateListOf()](https://tigeroakes.com/posts/mutablestateof-list-vs-mutablestatelistof/)  
불변 리스트를 다루는가? 아니면 가변 리스트를 다루는가? 상황에 따라 적절한 상태를 사용해야 한다.

## UX/UI
#### [실전 UI/UX - 약관 동의를 설계할 때 고려해야 할 것](https://yozm.wishket.com/magazine/detail/1174/)
이용 약관 동의를 어떻게 배치할 것인가에 대해 고민을 담은 글이다. 체크 박스, 필수 항목 표기법에 따른 사용자가 느끼는 UX를 상세하게 설명한다.

#### [거꾸로 입력하는 가입 화면, 처음에 어떻게 떠올렸을까?](https://toss.tech/article/toss-signup-process)
모바일 화면에서 input이 많아지면 키보드에 의해 콘텐츠가 가려지게 된다. 한 화면에서 하나의 TextField를 두는 게 최선일까? 이에 대한 토스의 해결 과정을 보여준다.
