# Scribe-Cloneservice
Sample Code for a Cloneservice for the Scribe platform api (TCI Connect Powered by Scribe)
Sample Scribe event map, that automates cloning of scribe solutions within the same org or across orgs.

Usage Requirements:
Make sure your API user has admin rights to all orgs that you want to use it.
Make sure that your agent's IP addresses are whitelisted in the orgs intended for use.

For best experience make sure you create your connections in source and target orgs before doing the clone(not included in this Clone service) 
If your Connection names are identical in Source and Destination org, your cloned solution will prepare and validate and be ready to run without manual interaction.
(in case the service timesout, does not necessarily means the clone failed, 
it just means the preparation steps took so long that the response timeout (approx 90seconds) limit exceeded.(from the event-endpoint) 

Scribe platform API documentation can be found here: https://dev.scribesoft.com/en/main/overview.htm
Scribe api connector docs can be found here:  https://help.scribesoft.com/scribe/en/index.htm#sol/conn/scribe_api.htm

Scribe Connector extensions docs can be found here: https://help.scribesoft.com/scribe/en/index.htm#sol/conn/conn_ext.htm
