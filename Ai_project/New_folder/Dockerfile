FROM python:3.10

WORKDIR /app

COPY . requirements.txt 

RUN pip install -r requirements.txt

EXPOSE 8501

CMD ["streamlit", "run", "dairy_temperature_app.py", "--server.port=8501", "--server.address=0.0.0.0"]
