node {
   stage 'Checkout'
      checkout scm
   stage 'Build'
      sh "npm install"
      sh "npm install forever"
      sh "npm install forever-monitor"
      sh "forever start server.js"
}
