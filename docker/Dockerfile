#FROM ubuntu:latest
FROM python:3.8.1
ENV VIRTUAL_ENV=/opt/venv
RUN python3 -m venv $VIRTUAL_ENV
ENV PATH="$VIRTUAL_ENV/bin:$PATH"
RUN pip install --upgrade pip
COPY ./* /
RUN pip3 install -r requirements.txt
# CMD ["python", "./plot_digits_classification.py"]
# CMD ["python","./app.py"]
# EXPOSE 8000
