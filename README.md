grails create-app grailsReactProfile --profile=react

| This profile provides a client/server multi-project build structure. The server Grails app is using the rest-api profile with CORS enabled. It can be started using 'grails run-app' or using the Gradle wrapper:

  ./gradlew server:bootRun

The React client app has been built using the create-react-app CLI. It can be started via 'npm start' (in which case you will need to run 'npm install' to install npm dependencies) or using the Gradle wrapper (which will install npm dependencies automatically if needed):

  ./gradlew client:start

The client app's build.gradle defines other tasks to test and build the app using react-scripts. Please see create-react-app's documentation for more information: https://github.com/facebookincubator/create-react-app

For support, please use the Groovy Community Slack (https://groovycommunity.slack.com/) or open an issue on Github: https://github.com/grails-profiles/react/issues


./gradlew bootRun -parallel

https://guides.grails.org/react-combined/guide/index.html


https://stackoverflow.com/questions/75821760/openssl-error-stack-error-03000086-digital-envelope-routines-initializatio

npm install react-scripts@latest --legacy-peer-deps