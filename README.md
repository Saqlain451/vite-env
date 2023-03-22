# Vite-Env

In this project i used env variable in VITE JS. If you are interested to add env variable in your react vite project.
Then It will give your idea to create and use it.
<br/>
### What Is Env ??
Environment or env is a file that holds variables and some sensitive data about your app.

## Create Your React App using Vite.

To create react app using vite open your vs code and type
```
npm create vite@latest
```

## Create env var

Create new file in your root directory or out of src folder. Give the name of it .env / .env.local

### Declare env var in vite

In the .env file write VITE_VAR_NAME = VAR VALUE
### Example :
```
VITE_API_KEY : xyz
```

## How to read variables values in js files ?
Open your jsx file where you wanna access the env variable and type import.meta.env.VITE_VAR_NAME (change var name)
```
import.meta.env.VITE_VAR_NAME
```
<img width="529" alt="image" src="https://user-images.githubusercontent.com/77657627/226889265-b309ea2e-a57d-44c3-8392-860f468da801.png">

Output will look like -->

<img width="715" alt="image" src="https://user-images.githubusercontent.com/77657627/226889590-c6a387fd-44ee-4547-89bd-75ab81fe7d54.png">

## How to run ?

In the project directory, you can run:
1) Install dependencies :
```
npm install
```
2) Run this app on your browser :
```
npm run dev
```

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

<br />
