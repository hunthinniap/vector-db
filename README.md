.
├── build                   # Compiled files (alternatively `dist`)
├── docs                    # Documentation files (alternatively `doc`)
├── src                     # Source files (alternatively `lib` or `app`)
├── test                    # Automated tests (alternatively `spec` or `tests`)
├── tools                   # Tools and utilities
├── LICENSE
└── README.md
/vector-db-project/
│
├── data/
│   ├── raw/             # Store raw text data files here
│   └── processed/       # Store preprocessed and vectorized data
│
├── models/
│   └── sentence_transformer/  # Model files for Sentence Transformer
│
├── indexes/
│   └── faiss_index/     # Faiss index files
│
├── scripts/
│   ├── preprocess.py    # Script for data preprocessing and vectorization
│   ├── index.py         # Script for creating and updating Faiss index
│   └── query.py         # Script for querying the Faiss index
│
├── notebooks/
│   └── exploration.ipynb  # Jupyter notebooks for exploration and testing
│
├── results/
│   └── query_results/   # Store query output files
│
└── config/
    └── config.yml       # Configuration files (e.g., paths, model settings)
`
