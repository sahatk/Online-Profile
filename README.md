# Online-Profile

<!doctype html>
<META NAME="Generator" CONTENT="Hancom HWP 9.6.1.6189">
<META HTTP-EQUIV="Content-Type" CONTENT="text/html; charset=utf-8">
<TITLE></TITLE>
<STYLE type="text/css">
<html lang="ko">
<head>
	<title>온라인 프로필</title>
	<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet">
  <style>
    table {
      width:90%;  /* 표의 너비 */
      border:1px solid #222; /* 1픽셀짜리 표 테두리 */
      border-collapse: collapse; /* 중복되는 표와 셀의 테두리를 한 줄로 표시 */
    }
    thead {
      background:#eee;  /* 제목 행의 배경 색 */
    }
    th, td {
      border:1px solid #ccc; /* 1픽셀짜리 셀 테두리 */
      padding:5px;  /* 셀 테두리와 셀 내용 사이의 여백(패딩) */
      font-size:0.8em;  /* 셀의 글자 크기 */
    }
    * {
    box-sizing: border-box;
    }
    body {
        background:#222;
        height:100%;
        margin:0;
    }
    li,p {
        line-height: 2.0;
        font-size:0.9em;
    }
    #container {
        position:absolute;
        left:50%;
        margin-left:-450px;
        width:900px;
        /* height:100%; */
        background:#fff;
    }
    aside {
        float:left;
        width:300px;    
        padding:20px 50px;
        /* height:100%;  */
        /* background:rgb(216, 216, 216); */
    }
    /* .pf {
        border-radius:10%;
        box-shadow:3px 3px 10px 2px #222;

    }  */
    #detail {
        position: relative;
        top:80px;    
    }
    #sns
    {
        position:relative;
        top:100px;
    }

    #main {
        float:right;
        width:600px;
        height:100%;
        padding:20px;
    }

    #main > section {
        width:500px;
        padding:20px;
        margin:10px;
        border-bottom:1px dotted #222;
    }

    section > p, section>table {
        margin-left:50px;
    }

    /* 글자스타일 */
    aside h1 {
        font-size:1.8em;
        font-variant: small-caps;
    }
    aside h2 {
        font-size:1.2em;
    }
    #namecard p {
        font-size:0.9em;
        color:rgb(99, 99, 99);
        /* font-style:italic; */
    }

    .subtitle {
        font-size:1.5em;
        /* padding-left:45px; */
        line-height:0.9em;
    }
    .subtitle::before {
        content:"";
        display:block;
        background:url("../images/note.png") no-repeat;
        width:24px;
        height:24px;
        float:left;
        margin:0 15px 0 0;
    }
    section > p {
        font-size:0.9em;
    }
  </style>
</head>

<body>
    <div id="container">
        <!-- 사이드바 -->
        <aside>
            <div id="namecard">
                <img src= "C:\HTML1\html5-css3-master\03\images/pf.jpg" alt = "">
                <h1>박상진</h1>
                <p>오늘은 남은 인생이 시작되는 첫째날</p>
            </div>
            <div id="detail">
                <p>서울 강서구 화곡본동</p>
                <p>sahatk@naver.com</p>                                 
            </div>
            <div id="sns">
                <h2>SNS</h2>
  
            </div>           
        </aside>
        <div id="main">
            <!-- 자기 소개 -->
            <section>
                <h2 class="subtitle">Who am I?</h2>
                <p><mark>프런트엔드 웹 기술(Front-end Web Tech.)</mark>에 관심이 많습니다. <br>현재 제주의 한 시골 마을에서 코딩 중입니다.</p>
            </section>

            <!-- 경력 -->
            <section>
                <h2 class="subtitle">Experience</h2>
                <ul>
                    <li>프론트엔드 개발
                        <ul>
                            <li>업무 내용 업무 내용 업무 내용 </li>
                            <li>업무 내용 </li>
                            <li>업무 내용 업무 내용</li> 
                        </ul>
                    </li>
                    <li>웹 디자인
                        <ul>
                            <li>업무 내용 </li>
                            <li>업무 내용 업무 내용</li>
                        </ul>                        
                    </li>
                </ul>             
            </section>

            <!-- 숙련도 -->
            <section>
                <h2 class="subtitle">Skills</h2>
                <ul>
                    <li>HTML5</li>
                    <li>CSS</li>
                    <li>Javascript</li>
                </ul>

            </section>

            <!-- 학력 -->
            <section>
                <h2 class="subtitle">Education</h2>
                <table>
                  <caption style="margin-bottom: 20px;">학력 사항</caption>
                  <thead>
                      <tr>
                          <th>출신학교</th>
                          <th>전공</th>
                          <th>기간</th>
                          <th>구분</th>
                      </tr>
                  </thead>
                  <tbody>
                      <tr>
                          <td>경기과학기술대학교</td>
                          <td>전자공학과</td>
                          <td>2016.03.01 ~ 2020.08.31</td>
                          <td>졸업</td>
                      </tr>
                      <tr>
                          <td>마포고등학교</td>
                          <td> - </td>
                          <td>2013.03.04 ~ 2016.02.04</td>
                          <td>졸업</td>
                      </tr>
                  </tbody>
                </table>
            </section>
        </div>        
    </div>
</body>
</html>
