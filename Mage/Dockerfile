FROM mageai/mageai:latest

ENV TZ="Europe/Madrid"

ARG USER_CODE_PATH=/home/src/${PROJECT_NAME}

COPY requirements.txt ${USER_CODE_PATH}/requirements.txt 

RUN pip3 install -r ${USER_CODE_PATH}/requirements.txt
