<!-- ═══════════════════════════════════════════════════════════════════ -->
<!--                    RONI MAHABUB — AI ENGINEER                      -->
<!--               GitHub Profile README  ·  Advanced Edition           -->
<!-- ═══════════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- ░░ HERO BANNER ░░ -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,30:0d1117,60:161b22,100:1f6feb&height=280&section=header&text=RONI%20MAHABUB&fontSize=72&fontColor=58a6ff&fontAlignY=40&desc=AI%20Engineer%20%E2%80%A2%20ML%20Researcher%20%E2%80%A2%20Deep%20Learning%20Architect&descSize=20&descAlignY=62&descColor=8b949e&animation=fadeIn&stroke=1f6feb&strokeWidth=2" />

<!-- ░░ DYNAMIC TYPING ░░ -->
<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=24&duration=2500&pause=600&color=58A6FF&center=true&vCenter=true&multiline=false&width=750&height=55&lines=Building+Intelligent+Systems+from+Scratch+%F0%9F%A7%A0;LLMs+%7C+Computer+Vision+%7C+NLP+%7C+MLOps+%F0%9F%A4%96;Turning+Raw+Data+into+AI-Powered+Products+%E2%9A%A1;Researcher+%7C+Engineer+%7C+Educator+%40+Core+Campus+%F0%9F%94%AC;Open+Source+AI+Contributor+from+Bangladesh+%F0%9F%8C%8D" alt="Typing SVG" />

<br/><br/>

<!-- ░░ BADGES ROW ░░ -->
<a href="https://bd.linkedin.com/in/ronimahabub/bn">
  <img src="https://img.shields.io/badge/AI%20Engineer-Available%20for%20Hire-1f6feb?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<img src="https://img.shields.io/badge/Focus-LLMs%20%26%20GenAI-161b22?style=for-the-badge&logo=openai&logoColor=white" />
&nbsp;
<img src="https://komarev.com/ghpvc/?username=ronimahabub2021&style=for-the-badge&color=1f6feb&label=PROFILE+VIEWS" />

</div>

<br/>

---

<!-- ░░ NEURAL NETWORK ASCII ART ░░ -->
```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║     ██████╗  ██████╗ ███╗   ██╗██╗    ███╗   ███╗ █████╗ ██╗  ██╗          ║
║     ██╔══██╗██╔═══██╗████╗  ██║██║    ████╗ ████║██╔══██╗██║  ██║          ║
║     ██████╔╝██║   ██║██╔██╗ ██║██║    ██╔████╔██║███████║███████║          ║
║     ██╔══██╗██║   ██║██║╚██╗██║██║    ██║╚██╔╝██║██╔══██║██╔══██║          ║
║     ██║  ██║╚██████╔╝██║ ╚████║██║    ██║ ╚═╝ ██║██║  ██║██║  ██║          ║
║     ╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═══╝╚═╝    ╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝          ║
║                                                                              ║
║          [ INPUT ] ──► [ HIDDEN LAYERS ] ──► [ OUTPUT ] ──► [ IMPACT ]      ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## `$ whoami`

```python
#!/usr/bin/env python3
# ─────────────────────────────────────────────────────────────
#  identity.py  ·  Roni Mahabub  ·  AI Engineer Profile v2.0
# ─────────────────────────────────────────────────────────────

from dataclasses import dataclass, field
from typing import List, Dict

@dataclass
class AIEngineer:
    name:       str = "Roni Mahabub"
    title:      str = "AI Engineer & Machine Learning Researcher"
    education:  str = "BSc · Computer Science & Engineering"
    location:   str = "Rajshahi, Bangladesh 🇧🇩"
    teaching:   str = "Data Science & AI  @  Core Campus (YouTube)"
    contact:    str = "ronimahabub2021@gmail.com"

    specializations: List[str] = field(default_factory=lambda: [
        "Large Language Models (LLMs) & Prompt Engineering",
        "Computer Vision  ·  Object Detection  ·  Image Segmentation",
        "Natural Language Processing  ·  Transformers  ·  BERT/GPT",
        "MLOps  ·  Model Deployment  ·  CI/CD for AI Systems",
        "Deep Learning Architecture Design  ·  Neural Networks",
        "Data Engineering  ·  Feature Engineering  ·  EDA",
    ])

    currently_building: Dict[str, str] = field(default_factory=lambda: {
        "🔭 Research"   : "RAG-based Q&A systems with LangChain",
        "🌱 Learning"   : "Diffusion Models & Multimodal AI",
        "🛠️  Building"  : "End-to-end ML pipelines with MLflow + Docker",
        "📡 Exploring"  : "Agentic AI workflows with AutoGen & CrewAI",
    })

    fun_fact: str = "I debug neural nets the same way I debug life — one layer at a time 🧠"

    def __repr__(self) -> str:
        return f"<AIEngineer: {self.name} | Building the future with AI>"

me = AIEngineer()
print(me)
# ➜  <AIEngineer: Roni Mahabub | Building the future with AI>
```

---

## `$ cat ai_stack.json`

```json
{
  "ai_engineer_stack": {
    "🧠 foundations": {
      "languages"     : ["Python 3.x", "SQL", "Bash"],
      "math_core"     : ["Linear Algebra", "Calculus", "Probability", "Statistics"]
    },
    "🤖 machine_learning": {
      "classical_ml"  : ["Scikit-Learn", "XGBoost", "LightGBM", "CatBoost"],
      "automl"        : ["AutoSklearn", "TPOT", "Optuna"]
    },
    "🔥 deep_learning": {
      "frameworks"    : ["PyTorch", "TensorFlow", "Keras", "JAX"],
      "architectures" : ["CNNs", "RNNs", "LSTMs", "Transformers", "GANs", "VAEs"]
    },
    "💬 nlp_llm": {
      "libraries"     : ["HuggingFace 🤗", "LangChain", "spaCy", "NLTK"],
      "models"        : ["BERT", "GPT", "T5", "LLaMA", "Mistral"],
      "techniques"    : ["RAG", "Fine-tuning", "PEFT", "LoRA", "Prompt Engineering"]
    },
    "👁️  computer_vision": {
      "libraries"     : ["OpenCV", "Pillow", "Albumentations", "TIMM"],
      "tasks"         : ["Classification", "Detection", "Segmentation", "OCR"]
    },
    "📊 data_engineering": {
      "analysis"      : ["Pandas", "NumPy", "Polars"],
      "visualization" : ["Matplotlib", "Seaborn", "Plotly", "Dash"],
      "databases"     : ["SQLite", "PostgreSQL", "MongoDB", "Pinecone (Vector DB)"]
    },
    "🚀 mlops_deployment": {
      "experiment"    : ["MLflow", "Weights & Biases", "DVC"],
      "serving"       : ["FastAPI", "Flask", "Streamlit", "Gradio"],
      "containers"    : ["Docker", "Docker Compose"],
      "cloud"         : ["AWS SageMaker", "AWS EC2", "AWS S3", "GCP Vertex AI"],
      "ci_cd"         : ["GitHub Actions", "Pre-commit Hooks"]
    },
    "🔧 dev_tools": {
      "ide"           : ["VS Code", "Jupyter Lab", "Google Colab"],
      "version_ctrl"  : ["Git", "GitHub"],
      "os"            : ["Ubuntu / WSL2", "Windows"]
    }
  }
}
```

---

## `$ skills --visual`

### 🧠 Core AI / Deep Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![JAX](https://img.shields.io/badge/JAX-A8B9CC?style=for-the-badge&logo=google&logoColor=black)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

</div>

### 💬 LLMs & NLP

<div align="center">

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FF9D00?style=for-the-badge&logo=huggingface&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)

</div>

### 📊 Data Science & Visualization

<div align="center">

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

### 🚀 MLOps & Deployment

<div align="center">

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=for-the-badge&logo=gradio&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

</div>

### 🔧 Dev Tools

<div align="center">

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

---

## `$ ai_roadmap --current`

```
AI ENGINEERING MASTERY PATH — 2024/25
══════════════════════════════════════════════════════════════════

  FOUNDATIONS          DATA LAYER          MODEL LAYER
  ┌───────────┐        ┌───────────┐        ┌───────────────────┐
  │  Python   │───────▶│  Pandas   │───────▶│  Classical ML     │
  │  NumPy    │        │  SQL      │        │  Deep Learning    │
  │  Math/Stats│        │  ETL/EDA  │        │  Transformers     │
  └───────────┘        └───────────┘        └─────────┬─────────┘
                                                       │
  PRODUCTION           DEPLOYMENT          SPECIALIZATION
  ┌───────────┐        ┌───────────┐        ┌───────────────────┐
  │  GitHub   │◀───────│  Docker   │◀───────│  LLMs & RAG       │
  │  Actions  │        │  FastAPI  │        │  Computer Vision  │
  │  DVC/MLflow│        │  AWS/GCP  │        │  MLOps Pipeline   │
  └───────────┘        └───────────┘        └───────────────────┘

  ✅ Completed  │  🔄 In Progress  │  📌 Planned

  ✅ Python · NumPy · Pandas · Scikit-Learn · Deep Learning
  ✅ CNN · RNN · LSTM · TensorFlow · PyTorch · OpenCV · NLP
  🔄 LLM Fine-tuning · RAG Systems · LangChain · Vector DBs
  🔄 MLflow · Docker · FastAPI · GitHub Actions · AWS
  📌 Diffusion Models · Multimodal AI · Agentic Workflows
  📌 Kubernetes · Distributed Training · RLHF
```

---

## `$ github --stats`

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=ronimahabub2021&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&title_color=58a6ff&icon_color=1f6feb&text_color=8b949e&bg_color=0d1117" />
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=ronimahabub2021&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=ff7b72&currStreakLabel=58a6ff" />

</div>

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ronimahabub2021&layout=compact&theme=github_dark&hide_border=true&title_color=58a6ff&text_color=8b949e&bg_color=0d1117&langs_count=8" />

</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=ronimahabub2021&bg_color=0d1117&color=58a6ff&line=1f6feb&point=58a6ff&area_color=1f6feb&area=true&hide_border=true&custom_title=Contribution%20Graph" />
</div>

---

## `$ trophies --show`

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=ronimahabub2021&theme=algolia&no-frame=true&column=7&margin-w=6&title=Stars,Commits,Repositories,Followers,Issues,PullRequest,Reviews" />
</div>

---

## `$ projects --pinned`

<div align="center">

| ⚡ Project | 🔬 Description | 🛠️ Stack | ⭐ |
|:----------|:--------------|:---------|:--:|
| [🧠 ML Repository](https://github.com/ronimahabub2021/ML) | End-to-end Machine Learning implementations & experiments | Python · Sklearn · Jupyter | ★2 |
| [📊 NSDA Suggestive](https://github.com/ronimahabub2021/NSDA-SUGGESTIVE-PROJECT) | Data-driven analytical suggestive system | Python · Pandas · Jupyter | ★2 |
| [📚 Book ML](https://github.com/ronimahabub2021/Book_ML) | Curated ML/AI research books & learning resources | — | ★1 |
| [🚀 ML Deployment](https://github.com/ronimahabub2021/ML_Model_Deployment) | Production-ready ML model deployment pipeline | Flask · HTML · Docker | ★1 |

</div>

---

## `$ connect --social`

<div align="center">

<a href="https://bd.linkedin.com/in/ronimahabub/bn">
  <img src="https://img.shields.io/badge/LinkedIn-Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="https://www.kaggle.com/ronimahabub21">
  <img src="https://img.shields.io/badge/Kaggle-View%20Notebooks-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" />
</a>
&nbsp;
<a href="https://www.youtube.com/@CoreCampus">
  <img src="https://img.shields.io/badge/YouTube-Core%20Campus-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
</a>
&nbsp;
<a href="mailto:ronimahabub2021@gmail.com">
  <img src="https://img.shields.io/badge/Email-Hire%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://www.facebook.com/md.roni.mahabub.2025">
  <img src="https://img.shields.io/badge/Facebook-Follow-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
</a>

</div>

---

<!-- ░░ FOOTER ░░ -->
<div align="center">

```python
while alive:
    eat()
    sleep()
    code_ai()
    repeat()
```

<br/>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" />

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,50:161b22,100:0d1117&height=130&section=footer&text=Building%20Intelligence%20%7C%20One%20Model%20at%20a%20Time&fontSize=18&fontColor=58a6ff&fontAlignY=65" />

</div>
