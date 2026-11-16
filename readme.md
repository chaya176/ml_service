# เว็บแอปพลิเคชันทำนายราคาบ้านด้วย Machine Learning (Random Forest Regressor) สร้างด้วย Flask และบรรจุใน Docker Container


# 1. วิธีการ Build Docker Image
docker build -t ds-ml-service .

# 2. วิธีการ Run Docker Container
docker run -d -p 5000:5000 --name ml-service-app ds-ml-service