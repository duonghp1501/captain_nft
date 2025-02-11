
## How to setup and get this project running

In the project directory, first install all the dependencies required using the command:

#### Check update. 

```bash
npx npm-check-updates -u
```
#### Run
```bash
npm install
```
```bash
npm install --legacy-peer-deps
```
Once done, create a .env file inside the project directory (or you can simply rename the `dev.env` file to `.env` file) and add the following variables.
```bash
REACT_APP_API_KEY=YOUR-API-KEY
REACT_APP_URL_EP=https://api.shyft.to/sol/v1/
```

Once done, enter your own API key in place of YOUR-API-KEY. You can enter your own API key at the [SHYFT Website](https://shyft.to/get-api-key).

Once this is done, you are good to do.

 #### To run this project enter the following command,
```bash
npm run start
```
Runs the app in the development mode in your own local server.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.




