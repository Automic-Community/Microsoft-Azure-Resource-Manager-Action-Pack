*Microsoft Azure Resource Manager Action Pack*
=============


Automate and orchestrate ARM using REST API
http://github.com/Automic-Community/Microsoft-Azure-Resource-Manager-Action-Pack

<!-- List of attached files -->
Contents of Solution Package:

						
								*PCK.PSL_AUTOMIC.AZURE_1.0.0.zip
								
						


Documenation and Instructions
---

<p>&nbsp;</p>
<p><img src="http://logo-logotype.com/wp-content/uploads/2016/10/Microsoft_Azure_logo_wordmark.png" alt="" width="442" height="148" /></p>
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
<pre><code>
{
 "properties": {
  "template": {
   (template definition - $schema, contentVersion, parameters, variables, resources)
  },
  "parameters": {
   (parameter-defition)
  },
  "mode": "Incremental"
 }
}
</code></pre>
<p><em><strong>*Since 17 Jan 2018, this community supported Action Pack may be replaced by this one when used with CA Automic Release Automation or CA Automic Service Orchestration: <a href="https://marketplace.automic.com/details/microsoft-azure-action-pack">https://marketplace.automic.com/details/microsoft-azure-action-pack</a></strong></em></p>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
