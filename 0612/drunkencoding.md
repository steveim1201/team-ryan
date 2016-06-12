# 06/12 번역 리뷰

R팀 (Ryan) 최연호(drunkencoding)

## 1. Review 내용들

-   [Chapter 1:From zero to deploy -> `./beginning.pdf`](beginning_by_drunkencoding.pdf)

## 2. Review 를 진행하며 책의 내용과 무관한 개인적인 소견으로..

1.  c9 에서 수정을 해도 저장을 하지 않으면 놓치는 부분들이 많은 듯 합니다.

    보통 local에서 사용하는 IDE들은 Auto save 기능이 자동으로 On 되어 있습니다.
    Experimentals => Auto save 기능을 통해 c9에서도 Auto save 를 사용할 수 있으며 이에 대한 소개를 곁들이면 좋을 것 같습니다.

2.  그림들의  Browser 를  통일하는 것이 어떨까요?

    Chapter.1 에서는 Firefox가, Chapter.2 에서는 Chrome이 그림들의 Browser로 표현되어 있습니다. 이를 하나의 Browser로 통일 혹은 다른 Default Browser를 선택해 사용하는 것이 좋을 것 같습니다.

3.  Command line 을 표현하는 Box에서 에서 현재 directory 이름이 나왔으면..

    보통 workspace/{proejct_name} 일테니 혼동이 없겠지만, 정말 초심자들은 workspace 에서 bundle install을 하는 경우가 있습니다. 오래전이기는 하지만 제가 그랬었구요.. ^^; (i.e. workspace/hello_app $ bundle install)
