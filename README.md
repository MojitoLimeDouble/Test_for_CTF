# Test_for_CTF
Test_for_CTF

외부에서 파일 읽을 때 사용.

tip)
1. 파일 읽을 때는 raw 하위 주소 이용하여 원본 읽게
2. 파일 수정 후 commit 보다 새 파일 수정해서 새로 올리는 게 deploy시 훨씬 안정적이고 속도도 빠름 (수정은 git commit -> deploy -> apply 단계를 거치는 거 같은데, 새파일 등록은 바로 apply로 건너뛰는 듯)
