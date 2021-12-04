# oss_assignment_2
## vimgolf

> `<CR> == enter`


1번문제
`GWi"<End>"<Esc>ZZ` --> 9번 \
![vimgolf1](https://user-images.githubusercontent.com/31243549/144703271-921b527f-e216-4d86-aa1a-cc7242fe1499.gif)

G-끝줄
W-다음단어시작위치로
i-현재위치에 삽입
end줄의 끝으로
ZZ-저장


2번문제
`:%s/sublime\|emacs/vim/g<CR>ZZ` --> 29번 \
![vimgolf2](https://user-images.githubusercontent.com/31243549/144701786-57c630d0-d518-495d-9a56-77a51ef7f612.gif) 

`:%s(치환)/sublime\|emacs(치환할문자열)/vim(치환한문자열)/g(전부)`


3번문제
`/V<CR>ywO// <Esc>paTODO<Esc>/D<CR>ywO// <Esc>paTODO<Esc>ZZ` -->36번 \
![vimgolf3](https://user-images.githubusercontent.com/31243549/144703612-ec7d2c89-5393-42d9-b5ea-2644a21fad3f.gif) 

/문자열 - 문자열 검색
yw - 단어 복사
O - 위에 새로운 줄 추가 후 입력 시작
p - 붙여넣기


4번문제
`:%s/y1/abs(y1)/g<CR>/1<CR>r4n.n.Nr3N.N.Nr2N.N./k<CR>rbnrrnrgZZ` --> 53번 \
![vimgolf4](https://user-images.githubusercontent.com/31243549/144703052-1a5f9c07-7d44-432e-af8b-8afb5a38cb4b.gif) 

r - 한단어 교체
n - 다음 검색
. - 이전 액션 다시실행


5번문제
`5ggyw/"<CR>pa,name,age,score<Esc>ZZ` --> 28번 \
![vimgolf5](https://user-images.githubusercontent.com/31243549/144703242-39bc314e-fd79-40ba-9e41-05270e192b1a.gif) 

5gg - 5번째줄로 이동
(뭔가를 하려 해봤지만 제일 처음 student_ID를 제외한 나머지는 이동에 쓰이는게 더 많아서 이게 오히려 더 숫자가 작게나옴)
