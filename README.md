# music-player
사용자가 음악 플레이리스트를 감상할 수 있는 웹페이지로<br> 재생/정지/처음부터 재생/다음 노래/이전 노래 기능이 있습니다.<br> flex 기반으로 레이아웃을 제작하고 JavaScript로 음악 파일을 제어하였습니다.<br>
- 참고 서적: `Do it! 인터랙티브 웹 페이지 만들기`
- 개발 환경: <img src="https://img.shields.io/badge/Windows-0078D6?style=flat&logo=Windows&logoColor=white"/> <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=VisualStudioCode&logoColor=white"/>
- 개발 언어: <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white"/>

## Preview
![music](https://user-images.githubusercontent.com/60216512/156379777-537e9ea8-0d6c-4ee9-9a12-1ccb68356786.png)


## Comments
책에 없는 내용이지만 Prev, Next 버튼을 눌러 다른 음악으로 넘어가더라도 재생/정지 상태를 유지하고 싶었습니다. isPlaying 변수를 추가하여 상태 변화를 연동하고, Prev, Next 버튼을 눌렀을 때 실행되는 activation 함수 내부에 이에 따른 재생 코드를 추가하였습니다.
