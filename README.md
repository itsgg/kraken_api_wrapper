# Kraken Wrapper

Simple Kraken API Wrapper for Node.js

## Setup

- Set environment variables in a `.env` file in the root directory of the project. The following environment variables are required:

```bash
KRAKEN_API_KEY=your-api-key
KRAKEN_API_SECRET=your-api-secret
KRAKEN_API_DOMAIN=https://api.kraken.com
```

## Usage

```bash
node index.js <command> <options>
```

## Example

```bash
node index.js Balance
```

```json
{"error":[],"result":{"ETHW":"0.0000015","USDT":"250.00000000","XETH":"0.0000015000","XMLN":"0.0000000100","XXBT":"0.0000093900"}}
```
