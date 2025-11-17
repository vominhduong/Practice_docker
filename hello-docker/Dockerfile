#Chọn Python base image
FROM python:3.10-slim
#chon folder lam viec
WORKDIR /app
#copy code vao container
COPY . /app
#cai dat thu vien
RUN pip install --no-cache-dir -r requirements.txt
#expose port de host truy cap
EXPOSE 5000
#buil app
CMD ["python","app.py"]
