# storjnotepad
saves and loads AES encrypted text to StorJ's MetaDisk

#
# How It Works

Simply type in a passphrase and type into the box below. Press SAVE. At any point you can return and type the same passphrase to retrieve the data.

All data is encrypted in the browser before saving to MetaDisk using AES encryption, and you are welcome to inspect the source code to verify.

I have hardcoded a MetaDisk account and bucket for demonstration purposes.



#
# Live Demo

See this code in action at the following url:

http://mycoinads.com/STORJnotepadDEMO/


#
# Known Issues

metadisk-api running on api.metadisk.org sometimes gives errors saying 'shard not found' or a problem with a /challenges url when trying to SAVE

If you keep retrying, it will eventually save. 