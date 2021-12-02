iOS 라이트닝 토크

2021.12.02 목

swift ui 특징

- swift ui는 iOS 13 출시와 함께 제공된 ui 프레임워크로 선언적 구문과 통합플랫폼을 지향한다는 특징이 있습니다.



swift ui 장점

- 배우기 쉽고 코드는 간단하고 깔끔함
- uiHostingcontroller을 사용하여 uiKit와 혼합하여 사용할 수 있음 (UIHostingController는 Swift를 관리하는 UIKit 뷰 컨트롤러UI 보기 체계이다.)
- 앱에 다크모드를 추가하는 등 테마를 쉽게 관리할 수 있음
- 실시간 미리보기를 제공함



swift ui 단점

- iOS 13 및 Xcode 11 이후만 지원함(이전 버전 지원x)
- 관련 데이터가 많지 않음



UIKit와의 차이점

- UIKit는 명령형 프레임워크지만 SwiftUI는 선언적 프레임워크이다
- UIKit는 사용자 인터페이스의 상태를 추적해야 하지만, SwiftUI에서는 데이터가 사용자 인터페이스 요소와 자동으로 결합될 수 있으므로 사용자 인터페이스의 요소를 추적할 필요가 없다.
- UIKit의 뷰는 UIView 라는 클래스의 자식이지만, SwiftUI는 뷰가 클래스가 아닌 구조체이기 때문에 상속된 추가 값이 없다.