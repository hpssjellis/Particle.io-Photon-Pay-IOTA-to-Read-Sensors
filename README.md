# Particle.io-Photon-Pay-IOTA-to-Read-Sensors
Hackster competition for which I will Pay IOTA to Read Photoresistor information from a Particle.io Photon microprocessor


Trying to get communication going between the particle photon microprocessor and a nodeJS website exchanging IOTA

Started August 19th, 2019



Most people with IOTA know how to use the Trinity wallet

Setup yout IOTA Trinity wallet as normal https://trinity.iota.org/


To run this site online using https://Gitpod.io

Load as a Gitpod.io site (needs Github authentication)  (Takes a few minutes to make the Docker image)

https://gitpod.io/#github.com/hpssjellis/particle-photon-IOTA-node-javascript


Or just do your normal way of loading a Github Nodejs site (Be aware that a few security issues for your IOTA exist using cloud Node sites). 

-----------------------------------------------------------------

Then run

```npm install```

```npm start```


1. Open in Browser  (If it does not pop up try the Ports terminal )


1. Click button for new recieve address

1. Using your Trinity Wallet send IOTA to that receive address but in the message place your own receive address

1. On confirmation of IOTA being sent using your Trinity Wallet, click the Confirm button on the web browser

1. The open webpage should show the new information from my Photon when it has been sent.

1. Your Trinity Wallet should receive a Zero value message about some sensor or actuator on my Photon. (Zero value messages are removed on the next IOTA SNAPSHOT)

-------------------------------------------------------

For Developers wanting to try this you need a Particle Photon and a secure Nodejs website

Set up your photon as normal https://www.particle.io/

In the code you will need to change 
(As these are important to you you should only use a private Github or Private Nodejs server.)

IOTA seed
Particel ID
Particel Assess token

-------------------------------------------------------------------------------------------------------------------

This site was made in August 2019 You might want to check each of these in the package.json file for upgrades on npm 

    "express": "^4.17.1",
    "@iota/core" : "^1.0.0-beta.21",
    "@iota/mam": "^0.7.3",
    "@iota/transaction-converter": "^1.0.0-beta.21",
    "@iota/converter": "^1.0.0-beta.21",
    "zeromq": "^5.1.0"
    
    

check npm search iota/core to get to 

https://www.npmjs.com/package/express    then click on "version"

https://www.npmjs.com/package/@iota/core    then click on "version"

https://www.npmjs.com/package/@iota/converter    then click on "version"


I don't actually yet use the other onces

https://www.npmjs.com/package/@iota/mam    then click on "version"

https://www.npmjs.com/package/@iota/transaction-converter    then click on "version"

https://www.npmjs.com/package/@iota/zeromq    then click on "version"


---------------------------------------------------------------------------------------------

By Jeremy Ellis
Twitter @rocksetta
Use at your Own Risk!

Do not use your main IOTA seed but setup a temporary seed for any projects.

