# Hocks-App
Lesson 2 module 3

For docker
```
docker build -t hocks-app .

# needs it to keep running
docker run -it -d --name hocks-app-container -p 3000:1234 -v $(pwd):/App hocks-app

# need interactive
docker exec -it hocks-app-container bash
```

For tools and libraries.  

````
npm i -g parcel-bundler
yarn init -y
yarn add react react-dom
apt install vim -y
# edit package.json to include `yarn start` script
```


