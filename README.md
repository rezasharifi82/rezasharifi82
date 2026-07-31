<!-- ============================================================
     Mohammadreza Sharifi  —  GitHub Profile README
     ============================================================ -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=soft&color=0:0d1117,50:1f6feb,100:0d1117&height=210&section=header&text=Mohammadreza%20Sharifi&fontSize=46&fontColor=ffffff&fontAlignY=42&desc=Computer%20Engineer%20%C2%B7%20ML%20Researcher%20%C2%B7%20Site%20Reliability%20Engineer&descSize=16&descAlignY=68&animation=fadeIn" alt="header"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3400&pause=900&color=58A6FF&center=true&vCenter=true&width=820&height=42&lines=%24+whoami+%E2%86%92+researcher+in+software+quality+for+ML+systems;%24+cat+interests.txt+%E2%86%92+technical+debt%2C+data-efficient+DL%2C+empirical+SE;%24+uptime+%E2%86%92+shipping+reliable+ML+pipelines+to+production;%24+echo+%22Libert%C3%A0!%22" alt="typing"/>
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=rezasharifi82&label=views&color=1f6feb&style=flat-square" alt="views"/>
<img src="https://img.shields.io/badge/Q1_Journal-Springer_Nature-2ea043?style=flat-square" alt="q1"/>
<img src="https://img.shields.io/badge/IEEE_%2B_Conference-2_papers-1f6feb?style=flat-square" alt="conf"/>
<img src="https://img.shields.io/badge/Focus-Software_Quality_for_ML-8b5cf6?style=flat-square" alt="focus"/>
<img src="https://img.shields.io/badge/TOEFL_iBT-100-f0883e?style=flat-square" alt="toefl"/>
<img src="https://img.shields.io/badge/Status-Open_to_PhD_%26_Research_Collab-ff6b6b?style=flat-square" alt="status"/>

</div>

---

## `~/whoami`

```bash
┌──(maresha㉿research)-[~]
└─$ cat profile.md
```

```yaml
name         : Mohammadreza Sharifi
role         : Computer Engineer · ML Researcher · Site Reliability Engineer
degree       : B.Sc. Computer Engineering — Ferdowsi University of Mashhad (2026)
gpa          : 3.36 / 4.00
location     : Mashhad, Iran
language     : English (TOEFL iBT 100 · R29 L23 S24 W24) · Persian (native)
research     :
  - software quality engineering for ML-integrated systems
  - technical debt detection & prevention in ML pipelines
  - data-efficient and reliable deep learning
  - empirical software engineering for AI products
motto        : "Libertà!"
status       : open to Ph.D. and research collaborations
```

**One-liner.** I sit at the boundary between empirical ML research and the software systems that carry it to production. First author of a Q1 journal paper and two conference papers on data-efficient deep learning and entity resolution. Day-to-day I build reproducible ML pipelines as an SRE — which is exactly where I first ran into the gap between *"the model passes the tests"* and *"the model still works next week."* That gap is what I want to study next.

---

## `~/publications`

<table>
<tr>
<td width="98" valign="top" align="center">
<img src="https://img.shields.io/badge/Q1-Springer-2ea043?style=flat-square" alt="q1"/><br/>
<sub><b>May&nbsp;2026</b></sub>
</td>
<td>

**Efficient Training of Deep Networks using Guided Spectral Data Selection: A Step Toward Learning What You Need**  
<sub>**M. Sharifi**, A. Harati &nbsp;·&nbsp; *Data Mining and Knowledge Discovery* — Springer Nature</sub>  
<sub>[`arXiv:2507.04269`](https://arxiv.org/abs/2507.04269) &nbsp;·&nbsp; first author</sub>

</td>
</tr>
<tr>
<td valign="top" align="center">
<img src="https://img.shields.io/badge/IEEE-ICCKE-1f6feb?style=flat-square" alt="iccke"/><br/>
<sub><b>2025</b></sub>
</td>
<td>

**Transformer-Gather, Fuzzy-Reconsider: A Scalable Hybrid Framework for Entity Resolution**  
<sub>**M. Sharifi**, D. Ahmadzadeh &nbsp;·&nbsp; *IEEE ICCKE 2025*</sub>  
<sub>[`arXiv:2509.17470`](https://arxiv.org/abs/2509.17470) &nbsp;·&nbsp; first author</sub>

</td>
</tr>
<tr>
<td valign="top" align="center">
<img src="https://img.shields.io/badge/Conference-MLKD-8b5cf6?style=flat-square" alt="mlkd"/><br/>
<sub><b>2024</b></sub>
</td>
<td>

**Optimizing Data Curation through Spectral Analysis and Joint Batch Selection (SALN)**  
<sub>**M. Sharifi** &nbsp;·&nbsp; *MLKD 2024*</sub>  
<sub>[`arXiv:2412.17069`](https://arxiv.org/abs/2412.17069) &nbsp;·&nbsp; sole author</sub>

</td>
</tr>
</table>

<sub>Full record on <a href="https://scholar.google.com/citations?user=R2dc3msAAAAJ&hl=en">Google Scholar</a> · <a href="https://orcid.org/0009-0003-8059-4792">ORCID 0009-0003-8059-4792</a></sub>

---

## `~/research`

> The line I keep returning to: *a model that passes every test on Monday can be silently wrong by Friday.*

- **Software quality for ML-integrated systems.** Empirically validated ML components accumulate silent technical debt as data and system conditions drift. Standard SE testing does not catch this. I want to formalize methods that do.
- **Data-efficient deep learning.** Spectral analysis of training data as a lever for cheaper, more reliable training. Line of work: **SALN** (MLKD 2024) → **GSTDS** (Springer Q1, 2026).
- **Entity resolution at scale.** Transformer-gather + fuzzy-reconsider hybrid deployed in real distributed server clusters (IEEE ICCKE 2025).
- **Applied deep learning.** Currently building a visual diagnostic agent for crop-disease identification from leaf images at a knowledge-based agri-tech company.

---

## `~/experience`

**Site Reliability Engineer** &nbsp;·&nbsp; GreenWeb — SRE Department &nbsp;·&nbsp; *Feb 2024 – present*  
Designed and maintained reproducible training pipelines and automated evaluation workflows using Docker, Docker Compose, and CI/CD. Reduced deployment cycle time by automating training, testing, and packaging. Integrated monitoring and logging for experiment traceability. Applied Kubernetes orchestration, Linux administration, and cloud infrastructure for distributed ML workflows and high-availability deployments. Turned an entity-resolution research result into a shipping production component — where I saw firsthand that *"shipping"* is not *"done."*

**Technical Developer** &nbsp;·&nbsp; Baghat Part Microtechnology Company &nbsp;·&nbsp; *2023 – present*  
Personally designed and built the company's e-commerce platform and internal microservices. Currently developing a deep-learning visual diagnostic agent for crop-disease identification, linked to the product catalogue. Encountered ML-specific technical debt when a frozen feature-extraction component silently degraded across weekly retraining cycles despite passing every unit test. Elected **Alternate Auditor** at the general assembly (August 2025).

**Independent Researcher** &nbsp;·&nbsp; Ferdowsi Univ. of Mashhad / GreenWeb &nbsp;·&nbsp; *Sep 2024 – present*  
Started while TA'ing Linear Algebra — noticed connections between spectral linear algebra and training efficiency. Proposed and developed **GSTDS**; extended it into a full spectral data-selection framework. Independently designed an entity-resolution solution for distributed server clusters. Three publications from this line of work.

---

## `~/teaching`

**Head Teaching Assistant** &nbsp;·&nbsp; Ferdowsi University of Mashhad &nbsp;·&nbsp; *Sep 2022 – Feb 2026*

| Course | Instructor | Role |
|---|---|---|
| Linear Algebra | Dr. Modjtaba Rouhani | Head TA, 3 semesters — coordinated 60+ students / sem, designed Python projects on PageRank, spectral learning, SVD-based image processing. This TA work directly inspired MLKD 2024 and the Q1 journal. |
| Advanced Programming | Dr. Ramin Zarei | Team Leader — Java / Spring Boot / Tomcat / JavaFX crypto-exchange projects with RL & statistical market prediction |
| Fundamentals of Programming | Dr. Ramin Zarei | Team Leader — 120+ ECE students; final projects covering A\* and Minimax in C |
| Data Structures | Dr. Haleh AminToosi | ICPC-style contest problem design |
| Design & Analysis of Algorithms | Dr. Mostafa Nouri-Baygi | Competitive-programming style problem sets |

🏆 &nbsp; **Outstanding Student Researcher**, Faculty of Engineering, Ferdowsi University of Mashhad (2025).

---

## `~/stack`

```bash
$ ls -la ~/stack/
```

**Languages**

<p>
<img src="https://skillicons.dev/icons?i=python,cpp,c,java,go,bash&perline=10" alt="languages"/>
</p>

`Python` · `C/C++` · `Bash` · `SQL` · `Java` · `Go`

**ML / Deep Learning**

<p>
<img src="https://skillicons.dev/icons?i=pytorch,sklearn,opencv&perline=10" alt="ml"/>&nbsp;
<img src="https://img.shields.io/badge/TorchVision-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Gymnasium-0081A5?style=flat-square"/>
</p>

**MLOps & Infrastructure**

<p>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,linux,git,githubactions&perline=10" alt="infra"/>&nbsp;
<img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square"/>
<img src="https://img.shields.io/badge/Monitoring_%26_Logging-4c1?style=flat-square"/>
<img src="https://img.shields.io/badge/Reproducible_Pipelines-informational?style=flat-square"/>
</p>

**Backend & Web**

<p>
<img src="https://skillicons.dev/icons?i=flask,django,react,html,css&perline=10" alt="web"/>
</p>

**Databases & Tools**

<p>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,vscode,idea&perline=10" alt="db"/>
</p>

---

## `~/stats`

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=rezasharifi82&show_icons=true&count_private=true&include_all_commits=true&theme=github_dark&hide_border=true&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&bg_color=0d1117" alt="stats"/>
<img height="170" src="https://streak-stats.demolab.com?user=rezasharifi82&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=f0883e&currStreakLabel=58a6ff" alt="streak"/>

<br/>

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rezasharifi82&layout=compact&langs_count=8&theme=github_dark&hide_border=true&title_color=58a6ff&text_color=c9d1d9&bg_color=0d1117" alt="langs"/>

</div>

---

## `~/contact`

```bash
$ ./contact --help
```

<p align="center">
<a href="mailto:sharifi.mohammadreza@mail.um.ac.ir">
  <img src="https://img.shields.io/badge/Academic-um.ac.ir-BB2528?style=for-the-badge&logo=maildotru&logoColor=white"/>
</a>
<a href="mailto:sharifi.mohammadreza2002@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://scholar.google.com/citations?user=R2dc3msAAAAJ&hl=en">
  <img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white"/>
</a>
<a href="https://orcid.org/0009-0003-8059-4792">
  <img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/maresha82/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://t.me/Maresha82">
  <img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/>
</a>
</p>

<div align="center">
<sub>📞 &nbsp; +98 902 546 3660 &nbsp;·&nbsp; 📍 &nbsp; Mashhad, Iran</sub>
</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=soft&color=0:1f6feb,100:0d1117&height=90&section=footer&text=exit%200&fontSize=18&fontColor=ffffff&fontAlignY=60&animation=fadeIn" alt="footer"/>

<sub><i>Open to Ph.D. and research collaborations in software quality engineering for ML-integrated systems.</i></sub>

</div>
