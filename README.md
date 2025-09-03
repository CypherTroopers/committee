 -X POST http://127.0.0.1:8000 \
  -H "Content-Type: application/json" \
  --data '{
    "jsonrpc":"2.0",
    "method":"eth_rescueCommittee",
    "params":[{"configPath":"/root/go/src/github.com/cypherium/cypher/rescue.json"}],
    "id":1
  }'
