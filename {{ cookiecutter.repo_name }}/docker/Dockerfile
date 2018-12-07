FROM jupyter/datascience-notebook
MAINTAINER Yu Adachi


# 必要なファイルをローカルからコンテナにコピー
ARG project_dir=/app/
ADD ./requirements.txt $project_dir

# requirements.txtに記載されたパッケージをインストール
WORKDIR $project_dir
RUN pip install -r requirements.txt
