FROM python:3.7.3-stretch

## Complete Step 1:
WORKDIR /app

## Complete Step 2:
COPY * ./app/

## Complete Step 3:
RUN pip freeze > requirements.txt && pip install -r requirements.txt
## Complete Step 4:
EXPOSE 80

## Complete Step 5:
CMD [ "python", "./app.py" ]