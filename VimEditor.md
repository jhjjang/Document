vi 학습

>Linux 터미널 환경에서는 GUI를 이용할 수 없기 때문에 
>터미널에서 텍스트 편집을 할 수 있는 +*vi(vim)*+ 를 사용해야한다.

### vi(vim) 개요

*개요*
      
    UNIX 계열 운영체제에서 주로 쓰이는 유서깊은 오픈 소스 텍스트 에디터. " _*Visual editor*_ "라는 뜻이다. 
원칙적으로 텍스트 모드에서 작동하도록 만들어졌기 때문에 어떠한 플랫폼 용 버전을 사용해도 기본적으로 모든 GUI가 텍스트 문자로 이루어져 있다.
" _*vim*_ " 은 유닉스 계열에서 전통적으로 널리 사용도던 vi 의 improve 즉 undo, syntax coloring, split windows 등의 기능을 
포함시킨 vi 의 보강된 프로그램이다.

*장점*

    커서 이동을 비롯하여 대부분의 편집 명령어가 키보드 중심에 몰려있고, 모드를 이용하여 키조합을 하지 않아도
 되는 경우가 많기 때문에 같은 작업을 해도 타 에디터에 비해 손동작이나 타수가 크게 줄어든다.
*단점*

    많은 명령어들을 외워야 한다.

### vi 학습

* *일반 모드*  
  다양한 편집기능을 적용할 수 있는 모드이다. 입력모드에서 ESC키를 눌러 전환

* *입력(텍스트) 모드*  
  데이터를 입력하는 에디팅을 위한 모드이다. 명령모드에서 특정키를 눌러 전환  

* *명령 모드*    
  편집을 끝낸 vi에디터의 저장 및 종료를 위한 모드이다. 명령모드에서 콜론(:)을 눌러 전환

* *옵션* (_10/31 update_)

bq. vi 환경에서 작업할 때 사전에 설정해 두면 편리한기능을 'set'으로 설정할 수 있습니다.

      [vi 옵션](http://kuroikuma.tistory.com/27)

|_.명령어               |_.설명                                                             |
|=.:set ai(autoindeant) | 윗라인과 같이 자동으로 들여쓰기                                   |
|=.:set ts=4(tabstop)  | 'tab'키를 입력 하였을 때 이동하는 키기를 조정                      |
|=.:set et(expandtab)  | 'tab'키를 입력 하였을때 'tab'에 대응하는 'space'만큼 이동          |
|=.:set si              | if 또는 for문을 입력하고 다음라인 이동시 들여쓰기                  |
|=.:set sw=4           | "set si"를 했을 경우 들여쓰기 하는 깊이 설정                       |
|=.set encoding=cp949 or utf-8 | 기본 인코딩 타입을 설정                                    |


* *vimtutor를 이용학 학습* (_10/31 update_)


bq. *vimtutor* 를 이용하여 vim환경에서 vim 튜토리얼을 실행해볼 수 있다.

    "vimtutor":http://www.withover.com/2008/03/vimtutor-vi%EB%A5%BC-vi%EB%A1%9C-%EC%97%B0%EC%8A%B5%ED%95%98%EC%9E%90.html


#### vi 학습 관련 링크

* "[vi 개요](https://namu.wiki/w/vi)
* "[vi 명령어 모음](http://slayer95.tistory.com/entry/Tip%EB%A6%AC%EB%88%85%EC%8A%A4-vi%ED%8E%B8%EC%A7%91%EA%B8%B0-%EB%AA%85%EB%A0%B9%EC%96%B4-%EB%AA%A8%EC%9D%8C)
* "[vi 필수 명령어](http://www.dreamy.pe.kr/zbxe/CodeClip/148114)
* "[자주 사용하는 명령어](http://www.insford.com/wiki/Wiki.jsp?page=%EC%9E%90%EC%A3%BC%EC%93%B0%EB%8A%94%20vi%EC%97%90%EB%94%94%ED%84%B0%20%EB%AA%85%EB%A0%B9%EC%96%B4)
* "[vim 상세 정보](http://www.joinc.co.kr/w/Site/Vim/Documents/UsedVim)
