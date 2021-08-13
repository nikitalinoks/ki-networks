{
  "type": "cosmos-sdk/StdTx",
  "value": {
    "msg": [{
      "type": "cosmos-sdk/MsgCreateValidator",
      "value": {
        "description": {
          "moniker": "",
          "identity": "",
          "website": "",
          "details": ""
        },
        "commission": {
          "rate": "0.100000000000000000",
          "max_rate": "0.100000000000000000",
          "max_change_rate": "0.100000000000000000"
        },
        "min_self_delegation": "1",
        "delegator_address": "tki1...",
        "validator_address": "tkivaloper1...",
        "pubkey": "tkivalconspub1...",
        "value": {
          "denom": "utki",
          "amount": "100000000"
        }
      }
    }],
    "fee": {
      "amount": [],
      "gas": ""
    },
    "signatures": [{
      "pub_key": {
        "type": "tendermint/PubKeySecp256k1",
        "value": ""
      },
      "signature": ""
    }],
    "memo": ""
  }
}