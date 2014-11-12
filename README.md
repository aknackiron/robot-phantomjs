
**What to install**

requirements.txt file contains the needed Python stuff that needs to
be installed into a virtualenv. Note that it also contains 'nodeenv'
for virtual node environment inside of virtualenv.

'$ nodeenv -p ;'

This gives you node.js and npm to install e.g. Phantom.js.

'$ deactivate;'

'$ source venv/bin/activate;'

There is a similar installation done here for reference:

http://calvinx.com/2013/07/11/python-virtualenv-with-node-environment-via-nodeenv/


Update PATH to contain Phantom.js binary. Only then can you pass
phantomjs to e.g. pybot.

