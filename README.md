<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    /* 기본 스타일 */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    /* 헤더 이미지 */
    img {
      width: 100%;
    }

    /* details 및 summary 스타일 */
    details {
      display: flex;
      align-items: center;
      margin: 20px;
    }
    summary {
      display: flex;
      align-items: center;
      cursor: pointer; /* 포인터 커서로 변경 */
      padding: 0; /* 기본 여백 제거 */
    }
    summary::-webkit-details-marker {
      display: inline-block; /* 기본 화살표 표시 */
      margin-right: 8px; /* 화살표와 텍스트 사이 여백 */
    }
  </style>
</head>
<body>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ACDFD8,10:B6D7A8,30:D3FFCE,75:CBD0E3,100:A371F7&height=100&section=header&text=&fontSize=0" alt="Header Image"/>

  <details>
    <summary><div>📜 About Me</div></summary> 

    <p>Hello! I'm a developer specializing in <strong>Artificial Intelligence</strong>, <strong>Optimization</strong>, and applying <strong>AI in the field of architecture</strong>.</p>

    <h2>Education</h2>
    <p>I'm currently a Computer Science major, studying at <strong>Gachon University</strong> (Class of 2022).</p>

    <h2>Focus Areas</h2>
    <ul>
      <li>Artificial Intelligence Development</li>
      <li>Optimization Techniques</li>
      <li>Applying AI in Architectural Design and Processes</li>
    </ul>

    <p>Official email: sulak9935@gachon.ac.kr </p>
  </details>

  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:B6D7A8,10:DA5B0B,30:B6D7A8,75:3572A5,100:A371F7&height=40&section=footer&text=&fontSize=0" alt="Footer Image"/>
</body>
</html>
