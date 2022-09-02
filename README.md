# Simple Chat

Create simple messenger chat application use Nodejs Expressjs, Reactjs for a test project.

## Screenshot:

<img src="https://lh3.googleusercontent.com/bk7OOm_rDDP8TgKK3KYj5lEVBc4FptkWBlGce6_pRjBj2TMTSQD6jgTdxyU0vqI30AaacSntUuhzkiltph_jMJYI4bUrjN3AVcoyDp-HC0aR-iXZ_zoLhR9cfeI9gdifcnPp8TlRpQ=w2548-h1318-no" />

## Server

``` 
cd server 
```
```
npm install
```

```
npm run dev
```
### Reactjs App development

```
cd app
```

```
npm start
```

### Reactjs App development using docker-compose

The docker-compose files are located in the two different application folders app and server. To run all the functions using docker run the follow commands:
``` 
cd server 
```
```
docker-compose up
```
At this moment the server application side will be running.

Now it's time to run application front end. Open a new terminal (window or tab) and in the project folder use the following commands:
``` 
cd app 
```
```
docker-compose up
```

Attention: Deppending on the way you have installed the docker in your compile you may use **sudo** command to run docker, for example:
``` 
sudo docker-compose up
```

For more docker informations and how to install access https://www.docker.com/ .
   
