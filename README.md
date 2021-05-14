
# React & Googlesheets app

It is a simple client sided app made with react to input some data and save it to googlesheets.
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
Googlesheets acts as the database and a third party service sheet.best is used as a REST APIs to connect with the database.

## Run the app

1. Open a new Spreadsheet by clicking File, then New, and then Spreadsheet.
2. Name the sheet to name of your choice and save.
3. Click the share button on the top right of your screen, and edit the permission to public.
4. Copy the link and go to <https://sheet.best/> and create your free account.
5. Create a new connection and paste your copied URL from the Google Sheets in the connection URL box.
6. Click on connect. You'll be redirected to your connections page. Here, you can see all your connections. Click on the details of your new connection.
7. Copy the CONNECTION URL. This URL will be used as the endpoint for sending POST Requests.
8. Paste the CONNECTION URL in the 31st line of App.js in place of the string `axios.post('{CONNECTION URL}', this.state)`
9. Now run the following scripts

### Available Scripts

In the project directory, you can run:

#### `npm install`

Installs the necessary dependencies required to run the app.

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.
