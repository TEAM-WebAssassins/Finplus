<h1>FinPlus- A financial dashboard app</h1>
<h3><b>Problem Statement</b></h3>
<p>Many people struggle with managing their finances effectively. Our goal is to create an app that will help users track their expenses, set budgets, and manage their finances more efficiently. The app will be built using the MERN stack and will provide users with an intuitive interface that makes it easy to manage their finances.</p>

<h3>What is it about? </h3>
<ul>
  <li>FinPlus is a financial dashboard with all your financial data centralized in one place. </li>
  <li>It is used to get meaningful insights for the segment of your financial data in business. </li>
  <li>One can gain a deeper understanding of their business through FinPlus and take strategic decisions for the business. </li>
</ul>
<h3>Why FinPlus? </h3>
<ul>
  <li>It is a MERN Finance Dashboard App that has Machine Learning Predictions. </li>
  <li> It is done to understand the financial position, solvency, and profitability of the business and to make better financial decisions in the future. </li>
  </ul>
  
  <h3>Frontend Tools used to make FinPlus</h3>
  <ol>
  <li>Material UI </li>
  <li>TypeScript</li>
  <li>Vite</li>
  <li>Recharts</li>
    <li>Redux</li>
    <li>RTK Query</li>
    <li>Heroicons</li>
    <li>React Router</li>
  </ol>
   <h3>Backend Tools used to make FinPlus</h3>
  <ol>
  <li>Node JS</li>
    <li>Express JS</li>
    <li>mongoose</li>
    <li>Regression JS</li>
  </ol>
<h3>About MUI</h3>
<ul>
  <li>Material UI is an open-source React component library that implements Google's Material Design. </li>

  <li>It includes a comprehensive collection of prebuilt components that are ready for use in production right out of the box. </li>

  <li> Also, we use Material UI data grid for the tables shown in the dashboard. </li>
</ul>
<h3>About VITE</h3>
  <p>Vite is a tool that aims to provide a faster and leaner development experience for modern web projects.</p>

<h5> Advantages of Vite: </h5>
<ul>
  <li> It is 20x faster, so less waiting time for reflecting file updates </li>

  <li> It helps to update the data in the project without reloading the page </li>
</ul>
<h3> Demo </h3>
<img style="width:75%" src="./finplus.gif" />
<hr>

## To Use
To clone and run this repository you'll need [Git](https://git-scm.com/) and [Node.js](https://nodejs.org/en) (which comes with npm) installed on your computer. From your command line:
<p>1. Clone github repository</p>

```
git clone https://github.com/TEAM-WebAssassins/Finance-Dashboard-App.git 
```
<p>2. Split Terminal</p>

```
|         Client terminal            |           Server terminal           |
|:-----------------------------------|------------------------------------:|
|                                    |                                     |
| \Finance-Dashboard-App> cd client  |  \Finance-Dashboard-App> cd server  |
|                                    |                                     |
|                                    |   npm i --force                     |
|   npm i --force                    |                                     |
|                                    |   touch .env                        |
|                                    |                                     |
|   npm run dev                      |   nodemon index.js                  |
|                                    |                                     |

```
<p>3. Go into .env file inside server dir and add mongodb url & port no</p>

```
MONGO_URL='mongodb+srv://USERNAME:PASSWORD@cluster0.pzaa32l.mongodb.net/?retryWrites=true&w=majority'
PORT=1337
```
