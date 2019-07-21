# A-simple-KV-key-value-store-web-service-with-a-subscription-feature
"A simple KV (key-value) store web service with a subscription feature. The  user will able to perform set(key, val) and get(key) operations over HTTP and also subscribe to changes happening to any of the keys."

NOTE: Require Python Version 3.0 or Later Required


<b><u>Hardware Requirement:</u></b></br>
 -Processor (CPU) with 2 gigahertz (GHz) frequency or above</br>
 -A minimum of 2 GB of RAM</br>
 -Network Connection(Local/Global)</br>

<b><u>Software Requirement:</b></u></br>

 -OS - REDHAT/LINUX/</br>
 -Package - pip # Can install pip directly using "get-pip" file.</br>
 -Frame-work - Flask</br>

<u><b>Resolving Dependency:</u></b>("All the Dependencys will be resolved by running "ansible.yml" file")


		<b>step-1</b> - First configure your "client-node" at your host location in "Master-node"
	
</br>
<img align="center" src="https://user-images.githubusercontent.com/16596896/61273575-b52e8500-a75e-11e9-8883-b00541b01746.JPG">
</br>
<img align="center" src="https://user-images.githubusercontent.com/16596896/61273622-d3948080-a75e-11e9-8d41-929730f428d6.JPG">
		
		step-2 - Run the ansible.yml file for resolving the dependency

		step-3 - Visit the given "URL" for "API" - http://127.0.0.1:5000 # If the service is not active kindly check the port it might be used in another process


		step-4 - Visit the given link for getting data "GET-FUNCTION" - http://127.0.0.1:5000/api/v1/resources/grofers?id=0







