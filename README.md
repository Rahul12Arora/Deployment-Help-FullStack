# Deployment-Help-FullStack

<h2>DATABASE</h2>

1.) Make a new Project on MongoDB
2.) Make a new cluster
3.) Add ip address from server side host into mongoDB from Network access tab(comes later).
4.) Create a username & password & save that password with you, you will have to use it later on server rendering.
5.) Last step is to connect to cluster & copy the database link; now replace the <password> with your cluster passwork & you will enter this link in server deployment

![image](https://user-images.githubusercontent.com/108695777/231209138-1d79010e-e0fa-4b47-8f1d-52087f354f66.png)

<h2>Server hosting</h2>
1.) Start a web service
2.) Select a repository & proceed
3.) Give a name, root directory, build command(npm install), start command(npm run start)
4.) Enter enviornment variables used in your server, server port will be replaced by mongoDB link from cluster in step 5 of databse hosting, also add any api keys here

![image](https://user-images.githubusercontent.com/108695777/231212240-52f4bb9f-b32b-46af-b09f-6c0dbff0d911.png)

<h2>Front end hosting</h2>
1.) Select a static service
2.) Select a repository & proceed
3.) Give a name, root directory, build command(npm run build), publish directory(build)
4.) Add enviornment variable, serverurl = backend url from server hosting.
