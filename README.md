## Créer l'image avec un tag :
`docker build --tag neuroliminalys02/frontend-dockerfile-react-2 .`

## Run l'image :
`docker run --name frontend-test -p 4242:5173 frontend-dockerfile-react-2`

## Push l'image :
`docker push neuroliminalys02/frontend-dockerfile-react-2`
