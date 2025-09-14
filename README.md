# Название Проекта
CAR DIRTINESS AND DAMAGE DETECTION WITH SPECIFICATION

# Для чего может использоваться
Когда ползователи InDriver заказывают такси по высокой цене а 
машина может не соответсвовать цены поездки и компания может получить много негативных отзывов 
либо ещё хуже потерять клиента, наша программа позволит предотвратить такие проблемы с помощью исскуственного интеллекта
# Requirements
- Tensorflow
- Flask
- PIL
- matplotlib
- requests
- scipy
- torch
- pandas

# Как запустить программу
git clone https://github.com/Winzyss-code/car-damage-detector
cd cd .\car-damage-detector-main\
pip install requirements.txt
python flask_app.py

# output
![Screenshot (14)](https://user-images.githubusercontent.com/75625675/212541145-287ca291-f6ef-4f7b-8e09-f379cb03f828.png)
![Screenshot (24)](https://user-images.githubusercontent.com/75625675/212541862-b306dca6-2b0d-4969-9967-e598c29597e8.png)
![Screenshot (28)](https://user-images.githubusercontent.com/75625675/212541874-a0a5292f-84cb-4197-b640-bf7c9f60b242.png)

# Какие виды повреждений может показать исскуственный интеллект 
YOLOv5 выведет 4 возможных варианта повреждений
- Scratch - Царапина
- Glass broken - Разбитое Стекло
- Deformation - Вмятена
- Broken - Разбитая часть Машины (например зеркало,шина,фары и тд..)

VGG16-модель вернёть статус машины грязный или чистый в терминал сервера (в нашем случае localhost) 
