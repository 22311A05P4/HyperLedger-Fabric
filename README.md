# HyperLedger-Fabric

## Setup Instructions

1. Clone this repo and navigate to the test-network folder from fabric-samples.
2. Run `./network.sh up createChannel -ca`
3. Deploy the chaincode using `./network.sh deployCC -ccn basic -ccp ../chaincode -ccl go`
4. Use the provided REST API to interact with the network.

## Chaincode Functions

- `CreateAsset`: Adds a new asset.
- `ReadAsset`: Retrieves asset details.

## API Endpoints

- `POST /createAsset`
- `GET /readAsset/:id`

## Tech Stack

- Chaincode: Go
- REST API: Node.js with Express
