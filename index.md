---
layout: default
---

I am Longtao Zhang (張龍韜), a second-year Ph.D. student at the CS Department, Florida State University, under the supervision of [Prof. Kai Zhao](https://ayzk.github.io). 

## Research Interests
- Hign Performance Computing
- Data Compression
- Algorithms and Data Structures

## Recent News

- **Nov. 2024** Received a travel award to SIGMOD'25 at Berlin

<!-- - **Nov. 2024** Received a travel grant to SC'24 at Atlanta -->

- **Oct. 2024** One paper about lossy compression for particles is accepted by SIGMOD'25 


## Publications
- **[SIGMOD'25]** [LCP: Enhancing Scientific Data Management with Lossy Compression for Particles](https://arxiv.org/abs/2411.00761)<br>
**Longtao Zhang**, Ruoyu Li, Congrong Ren, Sheng Di, Jinyang Liu, Jiajun Huang, Robert Underwood, Pascal Grosset, Dingwen Tao, Xin Liang, Hanqi Guo, Franck Capello, Kai Zhao

- **[Submitting]** [An Error-Bounded Lossy Compression Method with Bit-Adaptive Quantization for Particle Data](https://arxiv.org/abs/2404.02826)<br>
Congrong Ren, Sheng Di, **Longtao Zhang**, Kai Zhao, Hanqi Guo


## Education Background
- **Aug. 2023 - Curr.** Ph.D. Student at *Florida State University* 
- **Aug. 2019 - Jun. 2023**  B.Eng. Student at *Hunan University* 

<!-- ## Industry Experience -->

<!-- ## Paper Review

TBD -->

## Selected Awards

- FSU Computer Science Student Conference Travel Award 

[I/C]CPC = [International/China] Collegiate Programming Contest

- Florida State University Programming Contest, Tallahassee<br>
**First Place**              Nov. 2023

- CCPC National Invitational Contest, Xiangtan<br>
**Gold Medal, Third Place**  May 2023

<!-- - ICPC Aisa East Continent Final, Shanghai<br>
**Bronze Medal**             Mar. 2023 -->

- ICPC Regional, Hangzhou<br>
**Silver Medal**             Dec. 2022

- ICPC Regional, Hefei<br>
**Silver Medal**             Nov. 2022

- CCPC Regional, Weihai<br>
**Silver Medal**             Nov. 2022

<!-- - ICPC Aisa East Continent Final, Xi'an<br>
**Bronze Medal**             Jul. 2022 -->

<!-- - Hunan Collegiate Programming Contest, Yiyang<br>
**Gold Medal**               Dec. 2021 -->

<!-- - ICPC Regional, Shenyang<br>
**Bronze Medal**             Nov. 2021 -->

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Color Text Example</title>
    <style>
        .bronze { color: #cd7f32; }
        .silver { color: #c0c0c0; }
        .gold { color: #ffd700; }
        .first { color: #FF0000; }
        .second { color: #008000; }
        .third { color: #0000FF; }
    </style>
</head>
<body>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const paragraphs = document.querySelectorAll("p");
            const keywords = {
                "Bronze": "bronze",
                "Silver": "silver",
                "Gold": "gold",
                "First": "first",
                "Second": "second",
                "Third": "third"
            };
            paragraphs.forEach(paragraph => {
                for (const [keyword, className] of Object.entries(keywords)) {
                    const coloredSpan = `<span class="${className}">${keyword}</span>`;
                    paragraph.innerHTML = paragraph.innerHTML.replace(new RegExp(`\\b${keyword}\\b`, "g"), coloredSpan);
                }
            });
        });
    </script>
</body>
</html>

<!-- ## Question Writer

- 2024 The 20th Programming Contest of Hunan University
- 2024 Spring Programming Contest of Florida State University
- 2023 ACM Freshmen Cup of Hunan University
- 2023 The 19th Programming Contest of Hunan University
- 2021 ACM Freshmen Cup of Hunan University -->

<img src="/assets/img/hnu.jpg" alt="HNU" width="150" height="auto">
<img src="/assets/img/fsu.svg" alt="FSU" width="200" height="auto">