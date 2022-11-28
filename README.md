# Core
Core smart contracts of WolfyStreetBets.

## MarketOraclized.sol
Template MARKET smart contract for a prediction market with assets that have available Chainlink (oracle) price feeds on mainnet. 

## MarketParameterized.sol [DEPRECATED ~ MARKET MANIPULATION PROBABLE]
Template MARKET smart contract for a prediction market with assets that are non-native to the deployment chain & do not have Chainlink (oracle) price feeds on mainnet.

## MarketHybrid.sol
Template MARKET smart contract for a prediction market with combination assets: one that is non-native to the deployment chain & do not have Chainlink (oracle) price feeds on mainnet, one that is native and has available Chainlink (oracle) price feeds on mainnet.

## MarketUtility.sol
Helper contract for all types of MARKET smart contracts. Provides calculations and exposes an interface to oracles to get latest prices.

## MarketLiquidity.sol
Market currency staking & rewards contract that collects liquidity fees from predictions. Collected fees are are paid to stakers based on proportional stake amount and time staked for.

## WOLFPACKRewardManager.sol
Tracks addresses eligible for WOLFPACK $WPACK rewards generated from incentivized public functions in other contracts. 

## WOLFPACKStakingManager.sol
Stores data and distributes proportional <chain-native stablecoin/market currency> rewards to WOLFPACK $WPACK stakers.
