# KRAFT5
## Итоговый проект пятого модуля

# Подготовка 
1. Клонировать репозиторий
2. Создать виртуальное окружение
```bash
python -m venv venv
```
3. Активировать виртуальное окружение
```bash
venv\Scripts\Activate.ps1
```
4. Установить зависимости
```bash
pip install -r requirements.txt
```
5. Получить сертификат
```bash
mkdir -p ./secrets/ && \
curl -o ./secrets/YandexInternalRootCA.crt "https://storage.yandexcloud.net/cloud-certs/CA.pem" && \
chmod 0655 ./secrets/YandexInternalRootCA.crt
```
--5. Настройка Yandex Cloud CLI

# Задание 1.Развёртывание и настройка Kafka-кластера в Yandex Cloud



# Задание 2. Интеграция Kafka с внешними системами (Apache NiFi / Hadoop)