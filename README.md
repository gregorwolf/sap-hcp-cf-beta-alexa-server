# Alexa Skill Server based on alexa-app-server running on SAP HANA Cloud, Cloud Foundry Service Beta

Before you deploy using `cf push` to the SAP HCP, Cloud Foundry Service Beta you have to rename your 
service in the manifest.yml name attribute to get a unique URL. Be aware to choose 
"My development endpoint is a sub-domain of a domain that has a wildcard certificate from a certificate authority" 
in the step "SSL Certificate" during skill creation. 

After you've deployed this repository using `cf push` you can access the path /alexa/helloworld and /alexa/guessinggame. 
When you do that in the browser you will get a test page that does also conatain the Schema and Utterances.
