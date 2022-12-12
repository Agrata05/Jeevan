<h1 align="center"> Jeevan </h1>

## Inspiration 

When we all thought the pandemic was over, we were hit by it with a greater force. Each day the number of cases is increasing and with an increase in the number of people getting infected, it’s getting very hard to find hospitals with beds, ventilators, and the number of vaccines available in hospitals. <br>
Also, there is a huge need for plasma donation in every hospital, and thus an urgent need to make people aware of the process.

## What it does 

We aim to provide a Web App through which people can see the number of hospitals having free beds (with or without ventilators) and are vaccinating people or not. <br>
People can also volunteer themselves for plasma donation and provide space to convert into covid centers through the web App.<br>
On the other hand, Hospitals can register themselves in the app and request plasma donations by the recovered patients and for extra spaces needed for the patients.

## How we built it
The frontend was implemented in <a href="https://reactjs.org/" target="_blank">React.js</a>, using <a href="https://www.figma.com/" target="_blank">Figma</a> for design and layout, and <a href="https://www.axios.com/" target="_blank">Axios</a> to consume the backend.<br>
The backend was developed in <a href="http://nodejs.org" target="_blank">Node.js</a> and <a href="https://expressjs.com/" target="_blank">Express.js</a>. Using some middlewares like <a href="https://jwt.io/" target="_blank">Jwt</a>, to generate tokens, cors to enable the external ports for the frontend. And we keep the information in a <a href="https://www.mongodb.com/" target="_blank">MongoDB</a>..

## Screenshots of the project:

### Landing Page
![33](https://user-images.githubusercontent.com/62853703/207134885-5dece189-5d01-42b7-abdf-538f5dc59e47.png)

### Hospital Request 
![37](https://user-images.githubusercontent.com/62853703/207135135-a106b1e4-75d2-4632-8275-96237f6515b4.png)

### Donate Plasma
![35](https://user-images.githubusercontent.com/62853703/207135201-5008559c-da61-4cef-929e-53630814f2f2.png)

### Donate Beds
![34](https://user-images.githubusercontent.com/62853703/207135302-bdd04679-f8b0-4f3a-af6d-208e88392aba.png)


# Installation
1. Clone repository:
```bash
$ git clone https://github.com/Agrata05/Jeevan.git
```

2. Install dependencies:

```bash
$ npm i
```
3. Open `.env` and edit config, if it's necessary.(Put your atlas uri in backend)

4. Run example:
```bash
npm start
```
#### **Note**: cd ./FrontEnd and cd ./Backend, then proceed to step 2.

## Stay In Touch

* Author - [Agrata Tiwari](https://www.linkedin.com/in/agrata-tiwari-0511/) & [Abhishek Srivas](https://www.linkedin.com/in/abhishek-srivas-8421611a1)
* Website - [https://jeevan01.netlify.app/](https://jeevan01.netlify.app/)
