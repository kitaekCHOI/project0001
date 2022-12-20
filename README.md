

## 마크다운(MarkDown)이란

마크다운은 산문을 읽고, 쓰고, 편집ㅎ기 쉬운 목적으로 만들어진 문서 작서을 위한 형식으로 사용되며, 간결하고 html삽입이 가능합니다.        
또한 마크다운을 작성한 문서의 표현방식은 CSS의 설정에 따라 달라집니다.    

본 강좌는 깃헙 마크다운 css 기준으로 진행합니다.    

따라서 벨로그 마크다운 프리뷰와 약간의 차이가 있을 수도 있습니다.
* * *
### [마크다운 장점]
1.문법이 간결하고 쉽다
2.마크다운은 모든것에 사용할 수 있습니다. (웹사이트 문서 메모 기술 문서 등)    
3.마크다운은 지원하는 플랫폼이 많습니다 ( Github, Discord 등)    
4.마크다운은 대부붑의 환경에서 편집, 작성이 가능합니다. (메모장에서도 가능)  
5.텍스트로 저장되기 때문에 용량이 적어 보관이 용이합니다.     

### [마크다운 단점]
1.모든 HTML의 문법을 대신하지 못합니다.   
2.표준이 없기 때문에 도구에 따라 변환방식 또는 생성물이 다릅니다.    
3.마크다운으로 파일 업로드하는 경우 저장한 다음 **파일 경로**를 입력해야되는 불편함   
4.tistory, naver blog, notion과는 다르게 문법들을 하나하나 입력해야되는 경우가 있어 귀찮음이 조금 있습니다.    
 * * *
 
 ## 마크다운(MarkDown) 문법
 * * *
 
### Headers 헤더
* #으로 사작하는 텍스트
* #은 하나부터 여셋개까지 가능
* #이 늘어날떄마다 제목의 스케일 낮아집니다.
* H1는===로도 만들수 있습니다.
* H2는---로도 만들수 있습니다.      

### HORIZONTAL Roules 수평선
* -또는 * 또는 _을 3개이상 작성.        
* 단, -을 사용할 경우 header로 인식할 수 있으니 이 전 라인을 비워두어야 합니다.

### Line Breaks 줄바꿈
* \<br>를 활용해서 줄바꿈을 할 수 있습니다.
* 엔터로 칸을 띄면 다음 행으로 넘어가게 됩니다. \<br>은 하나의 문장에서 줄바꿈    
 
### Emphasis 강조
* 기울여 쓰기(italic): \* 또는 \_ 로 감싼 텍스트.
* 두껍게 쓰기(bold): \** 또는 \__ 로 감싼 텍스트.    
* 취소선: \~~로 감싼 텍스트.   
* 이탤릭체와 두껍게를 같이 사용할수 있습니다
 
 
### Blockquotes 인용
* \>으로 사작하는 텍스트
* \>는 3개까지 가능합니다.
     
 **참고로 인용구 안네는 제목이나 리스트,텍슽박스 등도 넣을 수 있습니다.**
 
### List 목록
 ***
      
### Unordered lists 순서가 없는 목록
 * *,+,-를 이용해서 순서가 없는 목록을 만들 수 있습니다. 
 * 들여쓰기를 하면 모양이 바뀝니다.

### Unordered lists 순서가 있는 목록
* 숫자를 기입하면 순서가 있는 목록이 됩니다.
* 들여쓰기를 하면 모양이 바뀝니다.
* 숫자를 무엇을 쓰느냐는 그다지 큰 의미가 없고 순서대로 알아서 숫자를 매깁니다.

- **리스트 안 리스트를 사용하려면 tab과 함께 숫자 1번 서부터 나열해야 적용이 됩니다.**

### 혼합 리스트
1. 말;
    1. 소4ㅁㄴㄹㅇㅁㄴㄹㅇ
    2. 닭ㅁㄴㅇㄻㄴㅇㄹ
       * 퇘지ㄴㅁㅇㄻㄴㄹㅇㄴㄹㅇ
          + 염소ㅁㄴㄹㅇㅁㄴㅇㄻㄴㅇㄹ
          + 늑대* 3. 
2. 호랑이ㅁㄴㅇㄻㄴㅇ
3. 사람
4. 툭배기
7.      

### Backslash Escapes
* 특수문자를 표현할 때, **표시될 문자앞에 \를 넣고 특수문자를 쓰면** 됩니다.

### 이미지 
* 링크와 비수하지만 앞에 !가 붙습니다.
* 인라인 이미지 ![alt text](/test.png)
* 링크 이미지 ![alt text](image_URL)
* 이미지의 사이즈를 변경하기 위해서는 <img width="OOOpx"height="OOOpx"></img>와 같이 표현합니다.

**이미지 파일에 마우스를 올렸을 때 커서 옆에 나오는 텍스트 설정**
![텍스트](이미지파일경로.jpg "이미지이름")
![텍스트](이미지파일URL "이미지이름")

**링크와 이미지를 합친 문법(이미지를 링크로 사용**
[ 텍스트](이미지파일URL ]( 링크URL )

**<img>태그를 이용한 이미지 크기 조절**
* <img src="https://i1.sndcdn.com/avatars-000639959556-jhitcq-t500x500.jpg" width="200" height="200" />
* <!-- a태그를 이용한 이미지 링크 생성법-->
<a href="#">
	<img src="https://github.com/images/markdown_syntax.jpg" width="400px" alt="sample image">
</a>

##Links (Anchpr) 
**외부링크**
* [Google](http://www.google.com "구글")

* [Naver](http://www.naver.com "네이버")

* [Github](http://www.github.com "깃허브")

구글 www.google.com

네이버 <www.naver.com>

My mail <jinkyukim.dev@gmail.com>

TIP) 꺽쇠 괄호 없어도 자동으로 링크를 사용

**링크 이를 변경**
[링크는 젤다의전설 주인공 이름](http://zeldahagoshipda.com)

**내부(해시) 링크**

[보여지는 내용](#이동할 헤드(제목))
괄호 안의 링크를 쓸때는 띄어쓰기를 \-로 연결, 영어는 모두 소문자로 작성
[1. Headers 헤더](#1-headers-헤더)

[2. Emphasis 강조](#2-emphasis-강조)

[3. Blockquotes 인용](#3-blockquotes-인용)

**코드블럭**
* 간다하 ㄴ인라인 코드는 텍스트를 앞뒤로 \'기호를 감싸면 됩니다.
* ''' 혹은 /~~~ 코드.
* 코드가 여러 줄인 경우, 줄 앞에 공백 네 칸을 추가로하면 됩니다.
* '''옆에 언어를 지정해주면 syntax color가 적용됩니다.
```javascript
function test() {
 console.log("look ma’, no spaces");
}
```

###체크리스트
* 줄 앞에 /- [X]를 써서 완료된 리스트 표시.
* 줄 앞에 /- [ ]를 써서 미완료된 리스트 표시.
* 체크 안에서 강조 외에 여러 기능을 사용할 수 있습니다.

- [x] this is a complete item
- [ ] this is an incomplete item

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported

###Table 테이블
* 헤더와 셀을 구분할 때 3개이상의 -(hyphen/dash) 기호가 필요합니다.
* 헤더 셀을 구분하면서 :(Colons) 기호로 셀(열/칸) 안에 내용을 정렬할 수 있습니다.
* 가장 좌측과 가장 우측에 있는 |(vertical bar) 기호는 생략 가능합니다.

테이블 생성

헤더1|헤더2|헤더3|헤더4
---|---|---|---
셀1|셀2|셀3|셀4
셀5|셀6|셀7|셀8
셀9|셀10|셀11|셀12

테이블 정렬

헤더1|헤더2|헤더3
:---|:---:|---:
Left|Center|Right
1|2|3
4|5|6
7|8|9

##머크다운 에디터
***
마크다운 문법은 메모장을 켜서 작업을 해도 무리없이 자겅 가능하다만 작업 속도향상을 위해 에디터를 사용하는 것을 추천합니다.
에디터는 사용한 마크다운을 랜더리아여 에디터 상에 실시간으로보여주며, 단축키 등을 사용하여 마크다운 문법을 빠르게 사용할 수 있습니다.

Typora
VSCode - Dark Github Makdown Pack



