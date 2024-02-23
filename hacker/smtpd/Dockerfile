FROM python:3.9.18

WORKDIR /app

COPY requirements.txt /app/
RUN pip install --no-cache-dir -r requirements.txt

CMD [ "python3", "-m", "aiosmtpd", "-n", "-l", "0.0.0.0:8025"]
