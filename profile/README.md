# 2024 Solution Challenge: TrueTree
[![섬네일2](https://github.com/2024-FactChecker-SolutionChallenge/.github/assets/80513699/d0634267-3f41-4f88-ba58-84caad146473)](https://youtu.be/caAKMsfhS1A?si=YCi3jgXgVWx-P3XT)

<br>

### ❗️ Introduction

Fake news has become a global social problem, spreading misinformation and causing harm. It's fueled by AI-generated content and deep-fake technology, disrupting the information ecosystem. This issue is particularly evident during critical events like the Russian invasion of Ukraine, the Israeli-Palestinian conflict, and US elections.
In response, the US media plans to combat misinformation by disseminating fake videos of Russia attacking its own country during the Ukraine conflict. This tactic aims to expose the invasion's reality. However, fake news exacerbates confusion and anxiety, contributing to international conflict.
The spread of fake news is also alarming domestically, especially among students whose literacy suffers due to digital media exposure. Korean students exhibit low proficiency in identifying digital information authenticity, the lowest among OECD countries. Primary school teachers attribute this to students' reliance on video platforms like YouTube and deficient reading skills.
To address this, several solutions have been proposed:
1. Providing Reliable Information: AI can evaluate article reliability based on users' interests, offering protection against biased information and fake news.
2. YouTube Fact Check: Users can input YouTube video URLs to assess their credibility using AI-based systems. This helps users navigate the platform's vast content and find trustworthy sources.
3. Improving Grammar and Vocabulary: Enhancing language skills is crucial for understanding information accurately. Introducing word quizzes and incentivizing learning through gamification and rewards can help users improve literacy.
By implementing these measures, users can better discern accurate information, fostering a healthier society.
<br>

### 📲 How to run our app service
- Click [here](https://drive.google.com/file/d/1DTCVnC_HgaEpXLwpEMLQHlceZf4jSuKA/view?usp=drive_link) to download an apk file.
- Install the apk file and **Please Run it on Android**
- After signing up ,  log in to access the app.
- The ml server and Spring server must be operational for the app to function properly.
<br>

### ✔ UN SDGs Goals & Target
| Peace & Justice & Strong Institutions | Quality Education  | 
| --- | --- |
|<img src="https://github.com/2024-FactChecker-SolutionChallenge/.github/assets/61193581/aff497a5-b035-429a-a02b-a91864d6dfbf" width="100"/> | <img src="https://github.com/2024-FactChecker-SolutionChallenge/.github/assets/80513699/e92fc805-92d7-4b13-96cf-a989b4393c4d" width="100"/>


<br>

### 🔧 Google Technology Used
| GCP | Gemini  | Tensorflow |
| --- | --- | --- |

### 🛠 Project Architecture
![SoftWareArchitecture](https://github.com/2024-FactChecker-SolutionChallenge/.github/assets/61193581/3c25d8f0-076e-4234-98df-3fc2207256fe)

### Feature Overview
### 01 Initial Screen
| Android Screen                                                                                                                 | Explanation                              |
|--------------------------------------------------------------------------------------------------------------------------------|------------------------------------------|
| ![initial](https://github.com/2024-FactChecker-SolutionChallenge/.github/assets/61193581/43e82a29-7ed9-4364-912f-0f453b443a18)| You can log in after signing up for membership. (Sign up process is omitted)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|

### 02 Home Screen
| Screen                                                                                                                        | Explanation                                           |
|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|
| ![home](https://github.com/2024-FactChecker-SolutionChallenge/.github/assets/61193581/2b9d5c2d-0298-48a9-9db0-42e426e19ca3)| On the home screen, users can check the list of recommended articles in the field of interest.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|

### 03 Article Screen
| Screen                                                                                                                        | Explanation                                           |
|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|
|![Article](https://github.com/2024-FactChecker-SolutionChallenge/.github/assets/61193581/fe47f2bd-b3f5-4c19-96f9-3006e2a1a87c)| If you touch the article, you can summarize the points of the article and learn the words. At this time, you can toggle the top left button to go into summary mode, and you can write and evaluate the topic of my thought in summary mode. Click the right highlighter button to enter word catch mode, and touch the word to know the meaning of the word. Then touch Save Words the words will save in your vocabulary list &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|

### 04 Fact check Screen
| Screen                                                                                                                         | Explanation                                                                                                                                                                                                                          |
|--------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| On this screen, you can enter the link to the YouTube news you were watching and receive reliable articles about the related content. If you insert the link and verify it, you can call up the related news in 5 minutes through the Reload verified video button. You can go to the article learning screen the same way.
| <img src="https://user-images.githubusercontent.com/61380136/229195752-052e0931-496b-45fc-ae42-26657fd90da6.gif" width="250"/> |&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br/> <br/> [ |

### 05 Learn Screen - Quiz
| Screen                                                                                                                        | Explanation                                           |
|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|
|![quiz-word](https://github.com/2024-FactChecker-SolutionChallenge/.github/assets/61193581/a4f04ed6-20f8-4fe3-b5fa-886d6650c126)|  You can check out the remaining opportunities and challenge yourself to a current affairs word quiz. Your quiz score will be saved and you can save the wrong words in the vocabulary&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|

### 05 Learn Screen - Vocabulary list, flip card & My Page Screen
| Screen                                                                                                                        | Explanation                                           |
|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|
|![mypage](https://github.com/2024-FactChecker-SolutionChallenge/.github/assets/61193581/810a6182-7836-416b-9bcc-1de1450222da)|  You can check the wordbook. The word you highlightered on the article learning page and the wrong word in the word quiz will be saved. You can press it yourself to see what it means and change the current know/don't know through the toggle button/ You can learn words through the Flip card. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|

<br>

### Demo Video Link
[![섬네일2](https://github.com/2024-FactChecker-SolutionChallenge/.github/assets/80513699/d0634267-3f41-4f88-ba58-84caad146473)](https://youtu.be/caAKMsfhS1A?si=YCi3jgXgVWx-P3XT)


<br>

### Contributors
| ML & Frontend | Backend | Backend | 
|:----------:|:----------:|:----------:|
| [<img src="https://avatars.githubusercontent.com/u/81565724?v=4" alt="" style="width:100px;100px;">](https://github.com/yulleta)<br/><div align="center">김민경</div> | [<img src="https://avatars.githubusercontent.com/u/61193581?v=4" alt="" style="width:100px;100px;">](https://github.com/Yeon-chae)<br/><div align="center">박채연</div> | [<img src="https://avatars.githubusercontent.com/u/80513699?v=4" alt="" style="width:100px;100px;">](https://github.com/ahyeon-github) <br/><div align="center">임아현</div>
