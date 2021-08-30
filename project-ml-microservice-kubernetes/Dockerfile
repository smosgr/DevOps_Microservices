FROM python:3.7.3-stretch

## Complete Step 1:
WORKDIR /

## Complete Step 2:
COPY * .
COPY requirements.txt .

## Complete Step 3:
RUN pip freeze > requirements.txt && pip install -r requirements.txt && pip install flask && pip install pandas && pip install joblib
## Complete Step 4:
EXPOSE 80

## Complete Step 5:
CMD ["python", "app.py"]