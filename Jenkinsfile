node {
   stage 'Checkout'
      checkout scm
   stage 'Build'
      sh "npm install"
      sh "npm install forever -g"
      sh "npm install forever-monitor"
      sh "forever start node_modules/react-scripts/start.js"
}
