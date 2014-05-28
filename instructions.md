Get started with ModuleTea
-----------------------------------

Welcome to Node JS Web Starter application that uses the IBM DataCache REST interface!

This sample application demonstrates how to write a Node JS application using IBM DataCache REST interface and deploy it on BlueMix.

1. [Install the cf command-line tool](https://www.ng.bluemix.net/docs/redirect.jsp?name=cf-instructions).
2. [Download the starter application package](https://ace.ng.bluemix.net:443/rest/../rest/apps/2b274b3e-d5e7-4627-9289-da3a30c809be/starter-download)
3. Extract the package and cd to it.
4. Connect to BlueMix:

		cf api https://api.ng.bluemix.net

5. Log into BlueMix:

		cf login -u jullyanafialho92@gmail.com
		cf target -o jullyanafialho92@gmail.com -s dev
		
6. Deploy your app:

		cf push ModuleTea

7. Access your app: [http://ModuleTea.ng.bluemix.net](http://ModuleTea.ng.bluemix.net)
