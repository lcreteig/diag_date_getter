Get the files:

```zsh
git clone https://github.com/lcreteig/diag_date_getter.git
cd diag_date_getter
```

Make and activate virtual environment:

```zsh
python3 -m venv .venv
source .venv/bin/activate
```

Install packages:

```zsh
pip install -U pip setuptools wheel
pip install -U spacy
pip install dateparser
python -m spacy download nl_core_news_sm
```