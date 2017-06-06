node {
   stage 'Checkout'
      checkout scm
   stage 'Build'
      sh "npm install"
      sh "npm install forever"
      sh "npm install forever-monitor 2> /dev/null"
      sh "npm forever start server.js"
}
