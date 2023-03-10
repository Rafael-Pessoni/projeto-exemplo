# projeto-exemplo
Projeto em .net para servir de exemplo 

docker build -f ./Dockerfile -t rafaelpessoni/projeto-exemplo:1.0 .
docker login -u rafaelpessoni -p 12321321321
docker push --all-tags rafaelpessoni/projeto-exemplo
