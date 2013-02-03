# Building for Chrome

## Updated Feb 2013

Log in to the Chrome Web Store and upload a zip of the 
App ID Sanity.safariextension directory. It's no longer
necessary to build and sign a .crx.

## Old instructions (now outdated)

Add a chrome alias for a tidier command line

    alias chrome="/Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome"
    
Then build thus:

    chrome --pack-extension=./App\ ID\ Sanity.safariextension/ \
    --pack-extension-key=/Users/simon/Library/Keys/uk.co.goosoftware.app-id-sanity.chrome.pem
