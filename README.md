# smartcotractlottery

### Specification

1. Users can enter lottery with ETH based on USD fee
2. An Admin will choose when lottery is over
3. The lottery will select a random winner

### Notes

This project lacks decentralisation as an admin has to decide when the lottery ends.

Ways to fix this would be:

- Use a timing/counting algorithm (draw once weekly, draw once a certain value has been reached)
- DAO could be the admin
- Chainlink Keepers

### Testing

1. mainnet-fork
2. development with mocks
3. testnet
