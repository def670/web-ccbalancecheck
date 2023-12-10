template generated with chatgpt and then extended by me, the mighty editor

you can active it from your file explorer or put it on a website. Alter as you will, the AI wont mind

page prompts for an ethereum address.  as long as its an eth type address it should work.  Doesnt have 
to be mainnet ethereum
the page will pull the balances for the entered account across a number of networks (currently 8)
ETH, ETC, ETHO, EGAZ, EGEM, CLO, MINTME, and OCTA

If you wish to extend the list you could put up a pull request or fork it and alter it yourself.
all that needs providing is the name of the new network and a working RPC for that network.
adding in is pretty straightforward - open it in an editor and find the lines with rpcs...make a 
new line and add your new rpc (with the rest of the simple to follow line

        { name: 'ETC', rpc: 'https://etc.rivet.link/' },
        { name: 'COIN', rpc: 'https://the.rpc.for.your.COIN/' },

just like that - ez

enjoy
