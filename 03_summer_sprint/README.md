ml-portfolio-2026/
└── 03_summer_sprint/
    ├── README.md                  ← главный файл этапа (вставь ниже)
    ├── project_4_news_classifier/ ← Классификатор новостей (RuBERT)
    │   ├── data/
    │   ├── notebooks/
    │   │   └── 01_fine_tune_rubert.ipynb
    │   ├── app.py                 ← FastAPI
    │   ├── Dockerfile
    │   ├── requirements.txt
    │   └── deploy_render.yaml
    ├── project_5_rag_chatbot/     ← RAG-чатбот (Llama-3)
    │   ├── data/
    │   ├── rag/
    │   │   └── rag_chain.py
    │   ├── app.py                 ← Streamlit
    │   ├── Dockerfile
    │   └── .streamlit/config.toml
    ├── project_6_recommender/     ← LightFM + Redis
    │   ├── api/
    │   ├── docker-compose.yml
    │   └── hetzner_deploy.sh
    ├── kaggle/
    │   ├── competition_1/
    │   └── competition_2/
    ├── open_source/
    │   ├── pr_xgboost/
    │   ├── pr_catboost/
    │   └── ml_utils_by_твой_ник/  ← твой PyPI-пакет
    │       ├── ml_utils/
    │       │   ├── __init__.py
    │       │   ├── clean_text.py
    │       │   └── save_experiment.py
    │       ├── tests/
    │       ├── pyproject.toml
    │       └── README.md
    └── content/
        ├── habr_articles/
        └── youtube_videos/
