In order to check and build -> 
`docker build -t fastapi .`
For some reason when debugging in local need to run `8000` as hort port. 
and port 80 default doesn't work.

In order to run local -> 
`uvicorn main:app --reload'