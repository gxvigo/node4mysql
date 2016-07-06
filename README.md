# node4mysql


#### Node test app for mySQL - node4mysql
This app just establish a connection to a mySQL instance. The connection uses the Secure Gateway destination defined earlier ( XXXX).
Code can be found on GIT: https://github.com/gxvigo/node4mysql

Create a node.js runtime in Bluemix and name it: node4mysql

To publish the app on Bluemix from your laptop (CF and Bluemix CLI must be installed)

 - cd /Users/giovanni/opt/workspaces/Bluemix/node4mysql (or whereever you cloned the git repo)
 - $ bluemix api https://api.au-syd.bluemix.net
 - $ bluemix login -u giovanni@nz.ibm.com -o giovanni@nz.ibm.com -s test
 - $ cf push node4mysql

To app logs:
 - on Bluemix AU - test space - node4mysql - Logs
