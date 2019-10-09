# PHP server

## Creating your own repository

In a terminal type

```
git clone https://github.com/cesinice/Php YourProjectName
cd YourProjectName
rm -rf .git
git init
git add .
git commit -m "feat: initial commit"
```

Navigate to your GitHub account to create a new repository and copy the two lines of code located under "…or push an existing repository from the command line".

Paste the copied code in the terminal and type enter.


## Starting the server

In the terminal type

```
docker-compose up -d
```

Navigate to http://localhost:8080

## Stoping the server

In a terminal type

```
docker-compose down
```