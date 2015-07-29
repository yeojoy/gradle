# gradle project
Android Project를 생성할 때 Android Studio(이하 AS)는 project 전체에 적용하는 build.gradle과 각 module에 적용하는 build.gradle를 생성한다. 이 build.gradle을 잘 이용하면 ANT때 했던 빌드 자동화를 손쉽게 할 수 있다는 생각이 든다.

# build.gradle
앞에서 언급했듯이 build.gradle은 프로젝트에 1개, 각 모듈 당 1개씩 생성된다. 일반적으로 Android Project를 생성하면 project 하나와 app module 하나 총 두 개가 생성된다. project는 repository에 대한 정보와 gradle에 대한 정보가 있고 module에 있는 것은 signing 정보, flavor, 필요한 dependency에 대한 정볻가 들어가 있다. 앞으로 수정할 것은 module에 있는 build.gradle이 될 것이다.

# CUSTIOMIZING
## change ouput file name
