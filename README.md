# fake-news-detection

fake-news-detection/
├── data/
│   ├── raw/
│   │   ├── isot/            # Fake.csv, True.csv
│   │   └── liar/            # train.tsv, valid.tsv, test.tsv
│   └── processed/           # الداتا بعد التنضيف والتقسيم
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_baseline.ipynb
│   └── 03_results_analysis.ipynb
├── src/
│   ├── __init__.py
│   ├── data.py              # تحميل وتنضيف وتقسيم
│   ├── train.py             # تدريب الموديلات
│   ├── evaluate.py          # التقييم وcross-dataset
│   └── utils.py             # seed، metrics، وغيرها
├── outputs/
│   ├── models/              # checkpoints
│   ├── results/             # ملفات json بالنتايج
│   └── figures/             # confusion matrix والرسومات
├── configs/                 # (اختياري) إعدادات كل تجربة
├── requirements.txt
├── .gitignore
└── README.md
