# serverless-stack

Repo to track progress in http://serverless-stack.com/  tutorial


Service Information
service: notes-app-api
stage: prod
region: us-west-2
stack: notes-app-api-prod
api keys:
  None
endpoints:
  POST - https://89yf4uc96i.execute-api.us-west-2.amazonaws.com/prod/notes
  GET - https://89yf4uc96i.execute-api.us-west-2.amazonaws.com/prod/notes/{id}
  GET - https://89yf4uc96i.execute-api.us-west-2.amazonaws.com/prod/notes
  PUT - https://89yf4uc96i.execute-api.us-west-2.amazonaws.com/prod/notes/{id}
  DELETE - https://89yf4uc96i.execute-api.us-west-2.amazonaws.com/prod/notes/{id}
functions:
  create: notes-app-api-prod-create
  get: notes-app-api-prod-get
  list: notes-app-api-prod-list
  update: notes-app-api-prod-update
  delete: notes-app-api-prod-delete
