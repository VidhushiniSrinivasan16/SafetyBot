Reference: https://github.com/wit-ai/wit-api-only-tutorial

Update data.tsv file with the samples in the format "text (col 1) , intent (col2)"

`There are no street lights in 16th street, near new jain temple, sowcarpet, chennai     ComplaintOn,wit/location`

# Instructions to run the multi_train.js script

Step 1: `sudo npm cache verify`

Step 2: `npm i node-fetch --save`

Step 3: `node multi_train.js `

# Successful Output on Posting to our wit.ai App

`{ sent: true, n: 2, WARNING: 'DEPRECATED' }`
