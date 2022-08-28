# Core
Core smart contracts of WolfyStreetBets.

## MarketOraclized.sol
Template MARKET smart contract for a prediction market with assets that have available Chainlink (oracle) price feeds on mainnet. 

## MarketParameterized.sol
Template MARKET smart contract for a prediction market with assets that are non-native to the deployment chain & do not have Chainlink (oracle) price feeds on mainnet.

## MarketUtility.sol
Helper contract for all types of MARKET smart contracts. Provides calculations and exposes an interface to oracles to get latest prices.

## WOLFPACKRewardManager.sol
Tracks addresses eligible for WOLFPACK $WPACK rewards generated from incentivized public functions in other contracts. 

## WOLFPACKStakingManager.sol
Stores data and distributes proportional <chain-native stablecoin/market currency> rewards to WOLFPACK $WPACK stakers.
