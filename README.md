# Getting started with engage-rtc-web-client-audiovideo-demo-app-reactjs
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Scripts to run the application

In the project directory, you can run:

### `npm install`
Install the dependencies to the local node_modules folder.

### `set HTTPS=true&&npm start`
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser. 
Once app loads successfully, it will connect to the engageDigital domain and the call button will be enabled on screen. You can make call using this button.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `update the configuration`
Update the configuration in engageDigitalClickToCallConfigration.js with proper values. It has the following properties.
- **domain:** Engage Digital RTC domain name. Get this domain name from Engage Platform Admin. In this demo you can use the publicly hosted **rtc.engagedigital.ai**
- **callToNum:** The number to dial to. It should be a proper service number. Creating the service and assigning it to a number can be done through ESMP-UI.
	 In this demo, you can use the number 9070707120 which is available in publicly hosted ESMP portal (https://portal.engagedigital.ai)
	 Note: When you dial to this number a video announcement will be played.
- **callType:** Type of call. Valid values are video or audio.
- **consoleLog:** If its true, click-to-call logs as well as EngageDigital logs will be written to browser console
- **joinWithVideoMuted:** Join the call with local video muted or not. When it's true caller will join the call with local video muted.



### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
