# Hocks-App
Lesson 2 module 3

```
docker build -t hocks-app .

# needs it to keep running
docker run -it -d --name hocks-app-container -p 3000:1234 -v $(pwd):/App hocks-app

# need interactive
docker exec -it hocks-app-container bash

# add the start script to the package.json file
# start: .....
yarn start
```

