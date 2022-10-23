FROM continuumio/miniconda3

WORKDIR /app1

RUN apt-get update
RUN apt-get install nano unzip
RUN apt install curl -y

RUN curl -fsSL https://get.deta.dev/cli.sh | sh
RUN pip install altair pandas numpy streamlit pydeck sklearn imblearn
COPY . /app1

CMD streamlit run --server.port $PORT prediction.py



