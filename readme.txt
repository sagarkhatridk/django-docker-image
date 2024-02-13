cd django-docker-image
docker build .
docker-compose up
go to: https://127.0.0.1



*************************************************
if gives error like below :
    non-200 OK status code: 401 Unauthorized body: "{\"message\":\"This endpoint requires you to be authenticated.\",\"documentation_url\":\"https://docs.github.com/graphql/guides/forming-calls-with-graphql#authenticating-with-graphql\"}"

run folloing command and login with github:
    gh auth login
