*Microsoft Azure Resource Manager Action Pack*
=============


Automate and orchestrate ARM using REST API
http://github.com/Automic-Community/Microsoft-Azure-Resource-Manager-Action-Pack

<!-- List of attached files -->
Contents of Solution Package:

						
								*PCK.PSL_AUTOMIC.AZURE_1.0.0.zip
								
						


Documenation and Instructions
---

<p>The actions use the ARM REST API to execute task on Microsoft Azure. First, the "Get Access Token" Action has to be executed, to get an access token from Azure. The retrieved access token has to be passed to all other actions, as input parameter</p>
<ul>
<li>Get Access Token</li>
<li>Create Resource Group</li>
<li>Deploy to Resource Group</li>
<li>Get Deployment Status</li>
<li>List Resource Groups</li>
<li>List Locations</li>
</ul>
<p>&nbsp;</p>
<p>The JSON syntax for "Deploy to Resource Group" action has to be as follows:</p>
<pre>{<br />&nbsp;&nbsp;&nbsp; "properties": {<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; "template": {<br />&nbsp;&lt;template definition - $schema, contentVersion, parameters, variables, resources&gt;<br />&nbsp;},<br />&nbsp;"parameters": {<br />&nbsp;&lt;parameter-defition&gt;<br />&nbsp;},<br />&nbsp;"mode": "Incremental"<br />&nbsp;}<br />}</pre>
<p>&nbsp;</p>

Copyright and License
---

Solutions, Templates, Actions and other content available on the Automic Marketplace subject to the Automic [Developers Distribution License] (https://marketplace.automic.com/developers-distribution-license) as well as the Automic Community [Terms of Service] (https://marketplace.automic.com/community-terms-of-service).
Automic does not support, maintain or warrant any content submitted by the Automic-Community.



Questions or Need Help? 
---
Any questions or comments? Converse with your fellow Users in the [Automic Community] (https://community.automic.com).