# sample-reactjs

## Objective

Starting frontend study with react js.

## Requirements

Docker

## Start project

1. Create a temporary docker node container:
```
docker run --rm -it -v $(pwd):/app -w /app -p 8080:8080 node bash
```
> For windows environment replace `$(pwd)` with the absolute path of the repository

2. Install the dependencies:
```
yarn install
```
3. Start the app:
```
yarn dev
```
4. Access: http://localhost:8080/
