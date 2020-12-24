# Bug in HardHat 2.0.6 demonstration

```
$ npx hardhat compile
Error HH606: The project cannot be compiled, see reasons below.

The Solidity version pragma statement in these files don't match any of the configured compilers in your config. Change the pragma or configure additional compiler versions in your hardhat config.

  * abdk-libraries-solidity/ABDKMath64x64.sol (^0.5.0)

These files import other files that use a different and incompatible version of Solidity:

  * contracts/import.sol (^0.7.5) imports abdk-libraries-solidity/ABDKMath64x64.sol (^0.5.0)

To learn more, run the command again with --verbose

Read about compiler configuration at https://hardhat.org/config


For more info go to https://hardhat.org/HH606 or run Hardhat with --show-stack-traces
```