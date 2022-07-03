
# IPFS Gateway Getter

Most IPFS gateways are super slow when you try to get a file from them.

This simple app fetches from an IPFS file from list of gateways, and returns the first successful gateway.

Currently a Fastify app deployed on Railway.app



## Usage

Use the pre-deployed example. It runs on a free Railway tier so might go down at any moment.

To display an IPFS CID in the browser:  
`https://ipfs.up.railway.app/QmZgwcHnbdWH1w6gsGCPq7Eofnz2HFTsQjHeqfZM4SFesk`

To download an IPFS CID with a file name: (IPFS doesn't store file names)
`https://ipfs.up.railway.app/QmZgwcHnbdWH1w6gsGCPq7Eofnz2HFTsQjHeqfZM4SFesk?download=rick.jpg`



### Make it your own

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Frailwayapp%2Fexamples%2Ftree%2Fmaster%2Fexamples%2Ffastify)

- Install dependencies `yarn`
- Connect to your Railway project `railway link`
- Start the development server `railway run yarn dev`