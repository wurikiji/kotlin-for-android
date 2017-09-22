# 안드로이드 개발을 위한 Kotlin
> https://kotlinlang.org/docs/reference/android-overview.html

Kotlin은 안드로이드 플랫폼을 위한 현대의 여러 프로그래밍 언어들의 장점을 모아,
안드로이드 앱개발에 매우 적합하며, 언어 사용에서 있어서의 제약 사항도 존재하지 않는다.:
- 호환성 (Compatibility): Kotlin은 JDK 6와 완벽히 호환되고 오래된 기종의 안드로이드
기기에서 아무런 문제 없이 동작할 수 있는 환경을 제공한다. **Android Studio**에서
Kotlin을 완벽히 지원하며 안드로이드 빌드 시스템과 호환가능하다.
- 성능 (Performance): Kotlin을 사용한 앱은 자바로 만들어진 앱과 동일한 성능을 보인다.
인라인 함수를 지원하는 Kotlin의 특징으로인해, `lambda`를 사용하는 코드들의 경우 자바로 
쓰여진 코드보다 더 빠른 경우도 존재한다. 
- 상호운용가능성 (Interoperability): Kotlin은 자바와 완벽하게 호환되어, Kotlin 앱을
만들 때 이미 존재하는 안드로이드의 자바 라이브러리들을 문제없이 사용할 수 있다. 
- 용량/공간 (Footprint): Kotlin을 운용하는데는 매우 작은 크기의 런타임 라이브러리만
필요하며, `ProGuard`를 통해 크기를 더욱 줄일 수 있다. 실제 애플리케이션에서, Kotlin
런타임 라이브러리는 몇 백개 수준의 적은 메소드만을 추가하여, `.apk` 사이즈의 100K 정도
공간만을 차지한다. 
- 컴파일 시간 (Compliation Time): Kotlin은 점진적 컴파일을 지원하기 때문에,
클린 빌드가 필요한 경우 자바와 동일하거나 더 빠른 컴파일 성능을 나타낸다. 
- 진입 장벽 (Learning Curve): 이미 자바를 사용하고 있는 개발자들에게 Kotlin을 배우는
것은 매우 쉬운 일이다. Kotlin 플러그인은 기본적으로 자바를 Kotlin으로 변환해주는 기능을
가지고 있고, `Kotline Koans`는 다양한 예제를 통해 Kotlin 언어의 핵심 기능들을 쉽게 
배울수 있도록 제공한다. 
