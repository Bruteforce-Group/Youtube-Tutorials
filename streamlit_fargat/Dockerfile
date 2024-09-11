FROM python:3.12.5

WORKDIR /app

COPY ./requirements.txt requirements.txt
COPY ./app.py app.py

RUN pip install -r requirements.txt 
    
EXPOSE 8501

CMD streamlit run app.py
