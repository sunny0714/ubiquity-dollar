# CreditNftRedemptionCalculatorFacet
[Git Source](https://github.com/ubiquity/ubiquity-dollar/blob/ccc689b8b816039996240d21714a491a27963d57/packages/contracts/src/dollar/facets/CreditNftRedemptionCalculatorFacet.sol)

**Inherits:**
[ICreditNftRedemptionCalculator](/src/dollar/interfaces/ICreditNftRedemptionCalculator.sol/interface.ICreditNftRedemptionCalculator.md)

Contract facet for calculating amount of Credit NFTs to mint on Dollars burn


## Functions
### getCreditNftAmount

Returns Credit NFT amount minted for `dollarsToBurn` amount of Dollars to burn


```solidity
function getCreditNftAmount(uint256 dollarsToBurn) external view override returns (uint256);
```
**Parameters**

|Name|Type|Description|
|----|----|-----------|
|`dollarsToBurn`|`uint256`|Amount of Dollars to burn|

**Returns**

|Name|Type|Description|
|----|----|-----------|
|`<none>`|`uint256`|Amount of Credit NFTs to mint|


