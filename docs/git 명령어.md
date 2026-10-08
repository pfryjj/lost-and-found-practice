# git 기본 명령어

## 최초 설정 (한 번만 수행)
### 이름 및 이메일 설정
```
git config --global user.name "이름"
git config --global user.email "github 이메일 주소"
```
* github 이메일 주소를 사용해야, 깃헙에 이력 쌓임

### 적용된 설정 확인
```
git config --list       # 모든 설정 확인
git config user.name    # 설정된 이름만 확인
git config user.email   # 설정된 이메일 주소 확인
```

---
## 저장소 생성 및 복제
### 로컬 저장소에서 저장소 생성
```
git init
```
* 현재 폴더를 git 저장소로 초기화

### 원격 저장소 > 로컬 저장소로 복제
```
git clone <저장소 url>
```
* 원격 저장소를 복제할 위치에서 수행

---
## 저장소 기본 사용법


---
## 기본 명령어
```
git status      # git 상태 확인
git diff        # git 차이점 확인 (woking 디렉토리와 Staging Area 비교)
git log         # git commit 이력 확인
```



