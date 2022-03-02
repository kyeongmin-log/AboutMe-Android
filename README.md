## AboutMe

-  강의 : https://developer.android.com/codelabs/kotlin-android-training-linear-layout#0

# 목표

-  나에 대해 설명하는 앱 만들기

-  텍스트가 길어질 경우, 스크롤 기능을 넣어 스크롤로 볼 수 있게 한다.

# 결과

[Virtual Device] - Nexus 5X (API LEVEL 30)

![project_result.gif](readme_files/project_result.gif)

# 코딩 챌린지

-  이미지를 스크롤 안에 넣기

-  이전 결과와 달리 스크롤 시 이미지와 텍스트가 같이 움직인다. 즉, 아래로 스크롤 할 경우 이미지가 안보인다.

[Virtual Device] - Nexus 5X (API LEVEL 30)

![code_challenge_result.gif](readme_files/code_challenge_result.gif)

# Add user interactivity

-  강의 : https://developer.android.com/codelabs/kotlin-android-training-interactivity#0

-  유저 이름 추가하기

-  추가한 유저 이름 변경하기

# 결과

[Virtual Device] - Nexus 5X (API LEVEL 30)

![Add_user_interactivity_result.gif](readme_files/Add_user_interactivity_result.gif)

# Data binding basics

-  강의 : https://developer.android.com/codelabs/kotlin-android-training-data-binding-basics#0

-  data binding 을 이용하여 앱을 Fix

# 결과

-  결과는 이전과 동일하다. 코드 안에서 데이터 사용 방식이 바뀌었다.

# 왜 사용하는가?

-  이전까지 views를 참조하기 위해서는 findViewById()를 사용하였다. 만약 모든 view들을 findViewById()를 이용하여 참조한다면 앱이 작을 경우 문제가 안되지만, 앱에 다양한 기능, view들이 nested(중첩)되어있을 경우 앱을 사용하고 있는 동안 각 view에 접근할 때마다 위에서부터 순차적으로 각 view에 접근하기에 처리하는 양이 점점 많아져서 느려지는 현상이 발생한다.

-  data binding을 사용하게 되면 각 view를 불러올 때, 순차적으로 접근하는 것이 아닌 Binding Object를 이용하여 해당 view를 가져오기에 속도가 down 되는 현상이 없다. 또한, findViewById()를 사용하는 코드보다 코드가 짧고 읽기 쉬우며 유지 관리에 용이하다.
