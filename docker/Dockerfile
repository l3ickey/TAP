FROM python:3.6.15

RUN apt update \
    && apt install -y \
    php=2:7.4+76 \
    && apt clean \
    && rm -rf /var/lib/apt/lists/*

RUN pip install -U --no-cache-dir \
    tensorflow==2.6.2 \
    gensim==3.8.3 \
    scikit-learn==0.24.2 \
    PyYAML==6.0 \
