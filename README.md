# airbnb-clone
Vanila Javascript 사용하여 aribnb 클론 해보기 프로젝트


## Web 이론
  - DOM (Document Object Model)
    -- 웹 문서(html)의 객체모델 인터페이스
    -- 돔은 자바스크립트로 수정될수 있는 api 제공해줌
    -- method example
       document.querySelectorAll(), ~~

## css 많이 사용되는 요소
  
  - display: flex 란?
   
    가로 정렬에 많이 사용됨
    하위 item은 flex: (크게비율) (작게비율) (초기값)  
                        grow       shrink    basis

    -- 정렬기준 => justify-content: space-between 요소간의 간격을 일정
                              space-around 요소간의 간경을 일정(컨테이너와도)

    --flex 사용시 => item 사이값 조절 :  gab 사용 편리!

  - view 영역 밖으로 object가 넘칠때 
    = overflow: auto;
    사용하면 스크롤로 해당 영역 표시가능

    아래 코드 사용하면 bar가 보이지 않음
    #catagory-bar::-webkit-scrollbar {
      display: none;
    }

  - CSS Position = 문서상에 요소를 배치하는 방법

## css reset 코드

  브라우저에서 기본으로 css를 설정해놓은 것을 reset 할 수 있도록 도와준다
    
    /* http://meyerweb.com/eric/tools/css/reset/ 
    v2.0 | 20110126
    License: none (public domain)
    */

    html, body, div, span, applet, object, iframe,
    h1, h2, h3, h4, h5, h6, p, blockquote, pre,
    a, abbr, acronym, address, big, cite, code,
    del, dfn, em, img, ins, kbd, q, s, samp,
    small, strike, strong, sub, sup, tt, var,
    b, u, i, center,
    dl, dt, dd, ol, ul, li,
    fieldset, form, label, legend,
    table, caption, tbody, tfoot, thead, tr, th, td,
    article, aside, canvas, details, embed, 
    figure, figcaption, footer, header, hgroup, 
    menu, nav, output, ruby, section, summary,
    time, mark, audio, video {
      margin: 0;
      padding: 0;
      border: 0;
      font-size: 100%;
      font: inherit;
      vertical-align: baseline;
    }
    /* HTML5 display-role reset for older browsers */
    article, aside, details, figcaption, figure, 
    footer, header, hgroup, menu, nav, section {
      display: block;
    }
    body {
      line-height: 1;
    }
    ol, ul {
      list-style: none;
    }
    blockquote, q {
      quotes: none;
    }
    blockquote:before, blockquote:after,
    q:before, q:after {
      content: '';
      content: none;
    }
    table {
      border-collapse: collapse;
      border-spacing: 0;
    }
