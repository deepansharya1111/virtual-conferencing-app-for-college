- PDM-Teams virtual-conferencing-app-for-college

  A conference call implementation using WebRTC, Socket.io and Node.js.


  # Getting Started
  - Run `npm install`
  - `npm install nodemon --save-dev`
  - Then
  - `npm start`
  - or
  - `node src/app.js`
  - Seen in browser using`localhost:8080`
  <!-- `npm run deploy` to use gh-pages script. Reference = https://www.youtube.com/watch?v=SKXkC4SqtRk&t=608s -->


  # Features
  - Multi-participants
  - Toggling of video stream
  - Toggling of audio stream (mute & unmute)
  - Screen sharing
  - Text chat
  - Mute individual participant
  - Expand participants' stream
  - Screen Recording
  - Video Recording


  # project guide 
  - Dr. Jasvinder Kaur, HOD (CSE Dept), Pdm university.

  # Demo
  You can test at https://pdm-teams.herokuapp.com.


  # Note
  You can create a free xirsys account and use their free ice server. You can replace the one I used with your own at `src/assets/js/helpers.js`, function `getIceServer()` from xirsys 'Static TURN Credentials' since WebRTC needs STEM and TURN server.
