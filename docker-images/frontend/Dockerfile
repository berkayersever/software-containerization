FROM python:3.8-alpine
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
EXPOSE 5000
RUN chmod +x entrypoint.sh
CMD ["./entrypoint.sh"]