# AOSPA[ParanoidAndroid] #

### Repo 설치하기 ###

```bash
# 소스를 다운받을 폴더를 만들고 들어가주세요.
$ mkdir (소스를 다운받을 폴더 이름)
$ cd (소스를 다운받을 폴더 이름)

# Repo를 설치해주세요.
$ repo init -u https://github.com/FullgreenDEVaospa/aospa_android -b kitkat
```

### 소스 다운로드 ###

처음 실행할 경우 오랜 시간이 소요됩니다.

```bash
# 아래의 명령어를 입력해주세요.
$ repo sync
```

## 빌드 시작 ##

```bash
# 소스를 다운받은 폴더로 이동해주세요.
$ cd (소스를 다운받은 폴더 이름)

# 빌드 도구 실행
$ ./rom-build.sh (코드명)
```

## AOSPA 번역하기 ##

[Crowdin](https://crowdin.net/project/aospa-framework) 에서 번역을 할수 있습니다. 프로잭트의 일부를 번역하는 작업에 참여하시려면 가입해야합니다.

## 패치파일 제출 ##

AOSPA는 오픈 소스이고, 패치는 항상 환영합니다!

아래의 주소에서 모든 패치의 상태를 볼 수 있습니다.
[Gerrit Code Review](https://gerrit.paranoidandroid.co/).

## 코드 사용 ##

### 코드 ###

Our codebase is licensed under Apache License, Version 2.0 unless otherwise specified. Apache
License 2.0 allows a variety of actions on the content as long as licensing and copyright
notices are retained and included with the code and your changes to the codebase are stated.

You can read the full license text at http://www.apache.org/licenses/LICENSE-2.0

### 이미지 및 기타 파일 ###

Unless otherwise specified, all out assets, including but not limited to images, are licensed
under Creative Commons Attribution-NonCommercial 4.0 International, or CC BY-NC 4.0 for short.
This means that you are allowed to modify the aforementioned assets in any way you want and
you are free to share the originals and/or the modified work. However, you are not allowed
to use the assets for commercial purposes and you must provide attribution at all times which
means you have to include a short note about the license used (CC BY-NC 4.0), the original
author/authors (Paranoid Android Project or AOSPA) and inform about any changes that have been
made. A link to the [website](http://aospa.co/) should usually be included as well.

You can reach the full legal text at http://creativecommons.org/licenses/by-nc/4.0/
