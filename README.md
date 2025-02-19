# Chạy dự án nếu còn môi trường ảo
conda activate Medichatbot

steamlit run MediChatbot.py

Open up url theo đường link trong terminal

# Chạy dự án lần đầu

## Bước 1:
*** Mở Anaconda prompt ***

conda create -n Medichatbot python=3.10 -y

conda activate Medichatbot

## Bước 2:
pip install -r requirements.txt

## Bước 3:
*** Tạo API_KEY cá nhân của HUGGINGFACE trong file .env ***

HF_TOKEN= your_hugging_face_token

## Bước 4:
streamlit run MediChatbot.py

--> Open up theo url trong terminal