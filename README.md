# SIEVE-CONNECT INTERACTIVE PROMPT

| COMMAND			                      | ACTION |
| -------           			          | ------ |
| activate `script`      		        | set the currently used script |
| checkscript `filename`           	| check script on the server |
| deactivate             		   	    | turn off sieve processing |
| delete `script`                  	| remove the script from the server :: aka: rm |
| download `script` [`filename`]   	| retrieve script from server :: aka: get |
| edit `script`				              | retrieve, edit, check, put script |
| help        						          | this help :: aka: ? |
| keywords    						          | list %KEYWORD substitutions |
| lcd         						          | local cd: change local working directory |
| list        						          | list the scripts currently on the server :: aka: dir -or- ls |
| lls         						          | local ls: look at local filesystem |
| lpwd        						          | local pwd: show local working directory name |
| man         						          | see docs |
| quit        						          | goodbye! :: aka: bye exit logout |
| upload `filename` [`scriptname`]  | put script on server :: aka: put |
| view `script`       				       | show contents of script :: aka: more page show |





### TERMINAL COMMANDS TO INITIATE INTERACTIVE PROMPT
> cd ~/sieveEmailSettings
> 
> sieve-connect -s mail.gandi.net -p 4190 -u _<EMAIL_USER>_  


### SYNTAX FOR THE SIEVE FILE

https://github.com/Whyglobaleyes/Sieve_Notes

------------

##### SOURCE OF SIEVE CONNECT 
https://github.com/philpennock/sieve-connect



------------


##### GANDI INFO 

If you do need to provide connection information use the following:
Host: mail.gandi.net
Port: 4190
Login: Your full email address, such as yourname@example.com
Password: The password for the provided email address


