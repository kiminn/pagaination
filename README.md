
## 프로젝트 진행기간: [12/3 ~ 12/8]

-----------------

### 12/3 (일)

#### 컴포넌트 구조를 나누고, 피그마를 만들고, 구글 투두리스트 작성했습니다.
#### vite를 사용해보았습니다!

```
가영 회고) vite 빠르고 버튼도 꾸며져있었지만,  LiveShare에서 문제가 ... -> 해결하지 못하여 협업이 살짝 어려웠습니다.
```

### 12/4 (월)

#### faker를 사용하여 userData를 생성하였습니다.
#### 토글 컴포넌트 구조를 만들었습니다.

```
가영 회고) 이땐 예상도 못했죠.. 새로고침시 계속 랜덤한 데이터가 나올 것이란 것을..

주현 회고) 페이커 데이터를 사용하니 연락처가 특정 형태로 나오지 않고 각각 다르게 나옴
연락처 데이터 다시 생성하기 및 특정 번호 자리 가리기 적용했습니다
토글 슬라이드 적용했으나 새로고침 시 닫힘 뒤로가기는 당연히 구현이 되지 않았습니다
```


### 12/5 (화)

#### 페이지네이션을 진행하였습니다.

#### 토글 슬라이드 데이터 유지하고 적용하였습니다. (새로고침해도 유지되도록)

```
가영 회고) useSearchParams가 get해서 가져오는 key값이나 이런 거에 대한 개념이 부족했음을 알게되었습니다.
이상한 걸 적용하다보니 옛날에 썼었다던 useLocation Hooks까지 적용했다가 나중에 뺐습니다^^
(+useHistory => 동작을 안하더라구요 잘못되었음을 감지)

주현 회고) 토글 슬라이드 css 적용
localstorage 토글 슬라이드 새로고침 적용 시 데이터 유지할 수 있도록 적용했습니다
localstorage 사용법을 구글링하고 적용했습니다..
```

### 12/6 (수)

#### 페이지네이션을 계속 진행하였습니다. 새로고침 시 유지가 안됩니다....버튼 색 유지성공

#### 필터링 구조 만들기 및 필터링 적용하였습니다.

```
가영 회고) 버튼색 포커스 까지도 되고, 양 옆누르는 버튼 까지는..다 잘눌리는데.. 꼬이고있었습니다..
이때 useSearchParams로 갈아탔습니다

주현 회고) 게시물 개 수, 및 조회 목록 순으로 핉터링 만들기
필터링 클릭하면 데이터는 잘 나오나 .. 뒤로가기 막힘...ㅠ
```


### 12/7 (목)

#### 새로고침이되는 페이지네이션이 되었습니다. userData를 static하게 바꿨습니다.

#### 필터링 내림차순, 오름차순 적용진행하였습니다.

```
가영 회고) 랜더링되는 구조에 문제가 있었습니다.
계속 랜더링이 될 때마다 초기 1page로 세팅을해주니 될리가 없었습니다.
useEffect를 사용하여 해결하였고, 랜덤한 fakerData는 새로고침이 되어도 옮겨도 이게 계속 바뀌니
확인이 안돼서 콘솔창의 userData 200개를 가져와서 고정시켰습니다.

주현 회고) 필터링 내림차순으로 적용했습니다 오름차순은 아직 진행중 입니다 ㅜ
```


### 12/8 (금)

#### 리드미 작성 및 페이지네이션 마무리, 아이콘 넣기, 회원등록페이지 만들었습니다.

#### 필터링 내림차순, 토글슬라이드 아이콘 적용하였습니다

```
가영 회고) 구글 시트를 잘 활용하지 않은 것을 알게되었습니다.. 반성.. 새로고침 유지하면서.. stirng === number 조건비교 하나로 애를 많이 먹었습니다. 조금 더 기초적인 것을 공부하여야 이런 시간낭비를 줄일 수 있을 것 같습니다ㅜㅜ..
주현 회고) 오름차순 내림차순 코드를 작성하면서 이러면 코드가 가독성도 그렇고 하드코딩같은데 
조건식을 활용하는데 있어 어려움을 느꼈습니다. 
		
```

전체 회고)
깃허브 push를 하면서 리드미를 먼저 작성했더니, 히스토리가 달라졌습니다. 그러면서 안일하게 -f로 푸시를 했다가 리드미와 커밋내역을 다 날렸습니다. => -f왜 쓰지 말라는지 너무나도 뼈저리게 알았습니다, 되돌리는 방법에 대해서 배웠습니다.
1. 커밋내역이 사라져도 상관없을 경우, -f 전 리드미를 무조건 복사해놓거나
2. 조금 더 안전한 방법으로 pull을 받아서 진행해야겠습니다.
막히는 부분에서 너무 오랜 시간을 끌어서 뒤에 콘텐츠를 제때 진행하지 못하였습니다. 때가되면 전체적인 프로젝트의 진행을 위해 포기하는 방법도 배워야할 것 같습니다... 기초보충의 필요성도 배웠습니다.


--------------

## 폴더구조
<img width="339" alt="스크린샷 2023-12-08 오후 1 36 45" src="https://github.com/mobi-community/mobi-2th-begginer-1/assets/134191815/27d6e4b1-b53c-4d01-aec2-406b078e376e">


## 구현목표
<img width="1100" alt="스크린샷 2023-12-08 오후 1 38 11" src="https://github.com/mobi-community/mobi-2th-begginer-1/assets/134191815/50e75468-6112-4b15-810b-338547b993d3">


------

[ 12/25 ] 
페이지네이션을 구현하지 못했기 때문에, 기능 구현을 위해 혼자 다시시작합니다!!
