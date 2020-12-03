# HonoursProjectCryptoJacking
A Browser Based Crypto-jacking Detection System


The original code was taken from -> https://github.com/teamnsrg/outguard

The version of the code seen here has additions to the code that include new logic and code architecture to allow for more crypto-jacking websites to be found

To run this code you mus first have:
  1. Python 27
  2. The lastest version of NodeJS
  3. Google Chrome

Commands to Run Program (UI will be uploaded in later release):
  1. Run the command -> npm install chrome-remote-interface
  2. chrome --headless --remote-debugging-port=9222
  3. node resource_collection.js "Desired Website"
     Put the devtools.trace file into trace folder
  4. python parser_module.py -d trace -myoutput
  5. python outguard_classifier.py
  (May be asked to install modules to get code running. Only needs simple NPM installs)
  
