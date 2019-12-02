FROM python:2.7-alpine
RUN apk add --no-cache git
RUN git clone https://github.com/moengage/moe-truffleHog.git --branch dev
RUN pip install -r moe-truffleHog/requirements.txt
