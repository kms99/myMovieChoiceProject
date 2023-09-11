# myMovieChoiceProject
영화 데이터 Api(TMDB API)를 이용하여 영화를 검색하고, 검색 결과 중 저장하고 싶은 영화를 선택하여 코멘트와 함께 저장하는 웹사이트

## 정보
**Language** : JavaScript

**Library & FrameWork** : Jquery, BootStrap

**Api** : TMDB api (https://www.themoviedb.org/?language=ko)

**Database** : google FireStore

**웹 호스팅 링크** : https://kms99.github.io/myMovieChoiceProject/


## 웹 디자인

**데스크탑 버전**

![image](https://github.com/kms99/myMovieChoiceProject/assets/29966870/f4c5902a-cdf5-4609-9f9c-7d29edb96675)
![image](https://github.com/kms99/myMovieChoiceProject/assets/29966870/0dd9d337-1870-4773-aa44-4720902d97e0)

**모바일 버전 (반응형)**

![image](https://github.com/kms99/myMovieChoiceProject/assets/29966870/4ce4b105-0ea3-4ae1-aa83-2bafa67e8e56)
![image](https://github.com/kms99/myMovieChoiceProject/assets/29966870/493e2eb0-eed3-439b-b1d2-33c55b7bb21e)


## 기능
**1. 영화 검색 기능**

영화 검색 시 TMDB Search Api를 호출하여 입력한 단어에 따른 영화 리스트를 가져온다.
해당 영화리스트를 BootStrap Carousel Component에 나타내었다.
   
![image](https://github.com/kms99/myMovieChoiceProject/assets/29966870/ed0de5af-a100-4da1-9bde-4e1699cd024d)

**2. 데이터베이스 연동을 통한 원하는 영화 정보 저장**

영화 검색 후 Carousel Item에 있는 Button을 클릭했을 때 선택되었다는 Alert 메세지나 나오며, 
이후 코멘트 작성 후 완료 버튼 클릭 시 완료되었다는 Alert 메세지와 함께 영화 정보가 데이터 베이스로 추가된다.

![image](https://github.com/kms99/myMovieChoiceProject/assets/29966870/665b578a-6612-4383-9e70-33e7f999abbd)

![image](https://github.com/kms99/myMovieChoiceProject/assets/29966870/26c354ba-d4c8-4311-9c13-1792738bd0f1)



**3. 데이터베이스 연동을 통한 저장된 영화 데이터 가져오기**

데이터베이스 연동을 통해 Reload 될 때 마다 데이터베이스에 저장된 영화 정보가 카드로 나타난다.

![image](https://github.com/kms99/myMovieChoiceProject/assets/29966870/199bdd41-4d1a-40f1-879f-c1a75e3f8cb2)





