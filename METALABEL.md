# solmate - Metalabel fork Changelog

> This fork is maintained by Metalabel and contains a few small opinionated changes to accommodate our needs ✌️

## 6.6.2-metalabel-patch-2

* Remove `name` and `symbol` storage implementation in `ERC721` and removed the constructor, downstream contracts must implement name / symbol functionality

## 6.6.2-metalabel-patch-1

* Use `OwnershipTransferred` event in `Owned.sol` to match OpenZeppelin's signature
* Use a one-word per-token struct to store owner and other information in `ERC721.sol`
* Remove `name` and `symbol` storage implementation in `ERC721` and removed the constructor, downstream contracts must implement name / symbol functionality

