## KOMORAN 문서

### 소개

https://docs.komoran.kr

* 이 저장소는 [KOMORAN 문서와 튜토리얼 등을 위한 정적 사이트(Static site)](https://docs.komoran.kr)를 생성/관리하기 위해 만들었습니다.
* [Sphinx](http://www.sphinx-doc.org/en/master/)과 [GitHub Pages](https://pages.github.com/)를 이용하고 있습니다.


### 실행하기

이 저장소를 직접 실행해보기 위해서는 다음과 같은 과정을 거쳐야 합니다.

#### 환경 준비
* Python 3.x
* pip (for Python 3.x)

#### 저장소 복제
먼저 저장소를 복제합니다. Git 사용법은 [여기](https://git-scm.com/book/ko/)를 참고해주시기 바랍니다.
```sh
  git clone https://github.com/komoran/docs
  cd docs
```

#### 의존성 설치
pip를 이용하여 의존성을 갖는 패키지들을 설치합니다.
```sh
  pip install -r requirements.txt
```

#### 문서 수정
Sphinx는 reST(reStructuredText)를 사용하고 있습니다.
간단한 reST 문법은 [여기](http://docutils.sourceforge.net/docs/user/rst/quickref.html)에서 확인하실 수 있습니다.

#### 빌드하기
수정한 문서를 확인하기 위해서는 다음과 같이 정적 사이트를 빌드해야 합니다.
```sh
  make html
```
생성된 결과물은 `_build/html` 경로에서 확인하실 수 있습니다.


### 기여하기

[KOMORAN 문서](https://docs.komoran.kr)를 보시다가 고쳐야 할 부분이 있다면 위 내용을 참고하시어 문서를 수정, 확인 하신 후 [Pull Request](https://help.github.com/en/articles/about-pull-requests)를 남겨주세요.
