<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=28&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=800&lines=Software+Engineer+%7C+Backend+Systems;Machine+Learning+Engineer+%7C+AI+Pipelines;Building+Scalable+%26+Intelligent+Solutions" alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <h3>Hi, I'm Nidish Kumar (NIDIXH) 👋</h3>
  <p>
    <i>Computer Science Undergraduate specializing in <b>Full Stack Engineering</b> and <b>Machine Learning</b>. <br> 
    I build end-to-end systems that bridge the gap between robust software architecture and predictive intelligence. My work focuses on reproducibility, scalability, and operational impact.</i>
  </p>
  
  <a href="mailto:your-email@example.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-blue?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/your-linkedin">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</div>

<br />

---

## 🛠️ Technical Arsenal

<table align="center">
  <tr>
    <td align="center" width="90"><b>Languages</b></td>
    <td align="center" width="90"><b>Frontend</b></td>
    <td align="center" width="90"><b>Backend</b></td>
    <td align="center" width="90"><b>AI / ML</b></td>
    <td align="center" width="90"><b>Data / Tools</b></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=python,cpp,js,dart,html&theme=dark" />
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=react,nextjs,bootstrap,tailwind,css&theme=dark" />
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=nodejs,express,flutter&theme=dark" />
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=tensorflow,pytorch,scikitlearn,opencv&theme=dark" />
    </td>
    <td align="center">
      <img src="https://skillicons.dev/icons?i=mysql,sqlite,git,github,vscode&theme=dark" />
    </td>
  </tr>
</table>

---

## 🧠 Intelligent Systems & Data Science

### ☀️ [Solar Power Generation Forecasting](https://github.com/NIDIXH/Solar-Power-Prediction)
**Overview:** A robust regression analysis pipeline designed to predict DC power output and detect hardware faults in solar inverters. The project addresses the challenge of forecasting renewable energy by integrating environmental sensor data with historical generation logs.

* **Tech Stack:** Python, Pandas, Scikit-learn, Seaborn, Matplotlib
* [cite_start]**Data Strategy:** * Integrated multi-source sensor data recorded at **15-minute intervals**[cite: 61].
    * [cite_start]Engineered **Physics-Informed Features** (Interaction Terms: Irradiance × Temperature) to model the non-linear thermal efficiency loss of PV panels[cite: 63].
* **Key Results:**
    * [cite_start]**Accuracy:** Improved Root Mean Squared Error (RMSE) by **~40%** through outlier removal and feature engineering[cite: 63].
    * [cite_start]**Validation:** Confirmed model robustness using **5-Fold Cross-Validation** to ensure stability across varying weather conditions[cite: 63].
    * [cite_start]**Operational Impact:** Utilized residual analysis to identify "zero-power" anomalies during peak sunlight hours, effectively serving as an automated **Fault Detection System** for maintenance teams[cite: 64].

### 💳 [Credit Default Prediction (Deep Learning)](https://github.com/NIDIXH)
**Overview:** An end-to-end Deep Neural Network (DNN) pipeline optimized for identifying high-risk credit defaulters. This project tackles a massive class imbalance to minimize financial risk.

* **Tech Stack:** Python, TensorFlow, Keras, Scikit-learn, Keras Tuner
* **Methodology:**
    * [cite_start]**Imbalance Handling:** Addressed a critical **78:22 class imbalance** by implementing calculated Class Weights, forcing the model to penalize false negatives **3.5x harder**[cite: 54].
    * [cite_start]**Architecture Search:** Automated hyperparameter optimization using **Keras Tuner**, searching through 112-neuron architectures and Dropout rates to maximize Validation AUC[cite: 56].
* **Key Results:**
    * [cite_start]**Performance:** Achieved a Validation AUC of **0.77+**[cite: 56].
    * [cite_start]**Strategic Tuning:** Shifted the classification threshold from 0.50 to 0.60, prioritizing a **Recall of 61%** to align model sensitivity with the bank's risk appetite[cite: 55, 58].

### 🧬 [Autonomous Bipedal Robot Simulation](https://github.com/NIDIXH)
**Overview:** An evolutionary robotics project that uses Genetic Algorithms to teach a bipedal robot how to walk in a physics-based environment.

* **Tech Stack:** Python, PyBullet (Physics Engine), Genetic Algorithms
* **Core Logic:**
    * [cite_start]Designed a custom genome structure and fitness function to optimize for three conflicting variables: **Speed**, **Stability**, and **Distance Traversed**[cite: 46].
* [cite_start]**Scale:** Conducted experimentation over **500+ generations**, analyzing population statistics to refine mutation rates and selection pressure for optimal evolutionary convergence[cite: 47].

### 🏥 [Biomedical Text Classification (NLP)](https://github.com/NIDIXH)
**Overview:** A Natural Language Processing pipeline designed to skim biomedical literature and classify abstract sentences (e.g., "Objective", "Methods", "Results").

* [cite_start]**Dataset:** PubMed 20k RCT (Randomized Controlled Trials)[cite: 37].
* [cite_start]**Approach:** Benchmarked a Baseline Naive Bayes model against a Deep Neural Network[cite: 38].
* [cite_start]**Engineering:** Built a reproducible preprocessing workflow including text cleaning, tokenization, one-hot encoding, and custom embedding layers[cite: 39].
* [cite_start]**Outcome:** Optimized for **F1-score** to ensure balanced precision and recall across all abstract categories[cite: 38].

---

## 💻 Software Engineering & Full Stack Development

### 🎟️ [Event Management Web Application](https://github.com/NIDIXH)
**Overview:** A full-stack web platform enabling users to browse events, book tickets, and manage listings via a role-based dashboard.

* **Tech Stack:** Node.js, Express, EJS, SQLite, bcrypt, HTML/CSS
* **Features:**
    * [cite_start]**Security:** Implemented secure login functionality using **bcrypt** for password hashing and express-session for state management[cite: 8].
    * [cite_start]**Architecture:** Built RESTful routes and modular Express.js controllers for scalability[cite: 9].
    * [cite_start]**Database:** Designed a normalized SQLite database to support complex CRUD operations and relational data consistency[cite: 10].
    * [cite_start]**UX:** Styled with a consistent, responsive design theme using vanilla CSS and media queries[cite: 11].

### 📱 [Food Diary Mobile App](https://github.com/NIDIXH)
**Overview:** A feature-rich Android application for nutritional tracking and personal health monitoring.

* **Tech Stack:** Flutter (Dart), SQLite, Shared Preferences
* **Capabilities:**
    * [cite_start]**Hardware Integration:** Camera capture for meal logging with timestamped entries[cite: 31].
    * [cite_start]**Persistence:** Implemented local data storage using SQLite for offline-first functionality and Shared Preferences for user settings[cite: 32, 34].
    * [cite_start]**Analytics:** Integrated local analytics to track screen visits and user entry metrics[cite: 34].

### 🎬 [Film Festival Database System](https://github.com/NIDIXH)
**Overview:** A comprehensive relational database system designed to manage the complex ecosystem of films, festivals, and awards.

* **Tech Stack:** MySQL, SQL, Entity-Relationship (ER) Modeling
* **Design:**
    * [cite_start]Engineered a **3NF normalized schema** to handle many-to-many relationships between films, festivals, and awards[cite: 41].
    * [cite_start]Modeled multi-valued metadata and temporal constraints to ensure data integrity[cite: 42].
* [cite_start]**Analysis:** Developed complex SQL queries using multiple `JOIN`s, subqueries, and aggregation to analyze festival trends and validate consistency[cite: 43].

---

## 🕹️ Creative Coding & Game Development

* **Physics Snooker Game:** An interactive simulation using **p5.js** and **Matter.js**. [cite_start]Engineered precise collision detection and physics-based interactions to mimic real-world dynamics[cite: 16, 17, 18].
* [cite_start]**2D Art Platformer:** A custom game engine built in **p5.js** featuring sprite animations, key-collection mechanics, and collision logic[cite: 21, 22, 23].

---

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NIDIXH&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Nidish's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NIDIXH&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" />
</div>

<br />

<div align="center">
  <i>Built with ❤️ and code.</i>
</div>
