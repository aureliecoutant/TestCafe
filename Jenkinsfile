node {
   stage 'Checkout'
      checkout scm
   stage 'Build'
      sh "npm install"
      sh "forever start server.js"
}
