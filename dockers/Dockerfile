FROM python:3.8.13-slim-buster


WORKDIR /python_app
COPY . .
# COPY test.py /
# COPY test2.py /

RUN pwd
RUN echo "---- hello from dockerfile"
RUN ls
RUN echo "---- hello from dockerfile"

CMD [ "python", "test.py"]

# RUN python test.py