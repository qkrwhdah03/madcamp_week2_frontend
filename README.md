# Developers

---

KAIST 전산학부 22학번 박종모

한양대학교 생명과학과 20학번 강다희

# 사용된 기술

---

Language: JAVA,  Python

Server: Flask

Database: MySQL 

OS: Android 8.0 

(minSdk = 24, targetSdk = 34) 

IDE: Android Studio , Visual Studio

Target Device: Galaxy S7

# 프로젝트 소개

---

헬스트레이너와 회원간의 쉬운 매칭과, 트레이너의 편리한 회원 관리, 회원의 운동 등을 돕는 gym 서비스 앱입니다. 

# 기능 소개

---

### 1. 카카오 로그인

- 카카오 SDK를 이용해 카카오 계정으로 로그인 할 수 있습니다.
- 카카오 계정은 본인의 짐과외 프로필에 접근하기 위한 목적으로 사용됩니다.
- <img src="https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/0ff64fd6-d514-44e0-8ef2-72655a4f7d91/Untitled.jpeg" width="300">


### 2. 개인 프로필 생성

- 로그인된 카카오 계정의 고유ID를 이용해 이에 대응되는 프로필을 생성하거나 가져올 수 있습니다.
- 신분 및 앱 사용 목적에 따라 회원, 혹은 트레이너로 프로필을 생성할 수 있습니다. 이에 따라 기능 및 UI 역시 달라집니다.
- 트레이너의 경우에는 검색 탭에서 회원으로 가입된 프로필에만 접근 가능하며, 회원의 경우 오직 트레이너로 가입된 프로필에만 접근할 수 있습니다. 이에 따라 매칭 요청 또한 마찬가지입니다.
- 트레이너, 회원 여부에 따라 필요한 정보와 표시되는 정보에 차이가 있으며 따라서 프로필에 표시되는 정보에도 차이가 있습니다.

### 3. 트레이너-회원 매칭

- 트레이너/회원 계정에서는 가입된 회원/트레이너 리스트를 확인할 수 있고, 원하는 회원/트레이너에게 매칭을 요청할 수 있습니다.
- 회원/트레이너는 매칭 요청을 확인할 수 있으며, 수락 혹은 거절을 선택할 수 있습니다. 수락한 경우 트레이너-회원이 매칭됩니다.
- 트레이너/회원은 매칭된 회원/트레이너를 본인의 매칭 리스트에서 확인할 수 있습니다.

### 4. 매칭 후 통화 및 문자

- 트레이너와 회원 매칭 이후에는 서로의 전화번호 정보를 알 수 있습니다.
- 프로필 창 밑에 있는 전화, 메세지 버튼을 이용해 해당 전화번호로 연결할 수 있습니다.

### 5. 회원 캘린더 관리

- 회원 캘린더에서는 오늘의 식단, 오늘의 운동, 오늘의 인바디를 기록할 수 있습니다. 오늘의 식단의 경우 갤러리에서 사진을 선택하여 이미지로 기록할 수 있으며, 오늘의 운동 및 오늘의 인바디에는 운동 내용 및 인바디를 텍스트 메모로 기록할 수 있습니다.

### 6. 개인 프로필 확인

- 트레이너, 회원 앱의 마지막 탭에서는 본인의 가입된 짐과외 프로필 정보가 표시됩니다 .