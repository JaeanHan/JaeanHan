<p>👋 Hi, I’m Jaean<p>
<p>👀 I’m interested in back end development.</p>
<p>🌱 I’m currently learning <span id="awsome1">Springboot</span> and <span>Javascript</span></p>
<p>💞️ I’m looking to collaborate on ...</p>
<p>📫 How to reach me ... jaean1999@naver.com</p>
<p>🦅 attending Pusan National University</P>
<p>📖 studying Computer Science and Engineering<p>
<br>
<p>🙌 Skills</p>
<div style="display:flex;">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white" />
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white" />
</div>
<br><br>

[![Solved.ac
프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=jaean1999)](https://solved.ac/jaean1999)

<script>
      function textDisplay(element) {
        const textArray = element.innerText.split("");
        const special = ["J", "a", "v", "a"];
        const exception = [" ", "\n", ".", ",", ":", ")"];
        const randomIntBetween = (min, max) => {
          return Math.floor(Math.random() * (max - min + 1) + min);
        };

        const numArray = [];
        textArray.forEach((_) => {
          const num = randomIntBetween(5, 40);
          numArray.push(num);
        });
        let newText;
        let completeCount;
        const timer = setInterval(() => {
          completeCount = 0;
          newText = "";
          numArray.forEach((num, i) => {
            if (exception.includes(textArray[i]) || numArray[i] === 0) {
              newText += textArray[i];
              completeCount += 1;
            } else {
              newText += special[numArray[i] % special.length];
              numArray[i] = --num;
            }
          });
          element.innerText = newText;
          if (completeCount === numArray.length) clearInterval(timer);
        }, 100);
      }

      const p = document.getElementById("awsome1");
      textDisplay(p);
    </script>
<!---
JaeanHan/JaeanHan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
