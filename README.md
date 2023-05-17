# airbnb-clone
Vanila Javascript 사용하여 aribnb 클론 해보기 프로젝트


## css 많이 사용되는 요소
  
  - display: flex 란?
   
    가로 정렬에 많이 사용됨
    하위 item은 flex: (크게비율) (작게비율) (초기값)  
    
    -- 정렬기준 => justify-content: space-between 요소간의 간격을 일정
                              space-around 요소간의 간경을 일정(컨테이너와도)

    --flex 사용시 => item 사이값 조절 :  gab 사용 편리!


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
