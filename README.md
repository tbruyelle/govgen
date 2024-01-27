# GovGen

GovGen is built using the [Cosmos SDK](https://github.com/cosmos/cosmos-sdk) as a fork of the [Cosmos Hub](https://github.com/cosmos/gaia) at version [v14.1.0](https://github.com/cosmos/gaia/releases/tag/v14.1.0).

The following modifications have been made to the Cosmos Hub software to create GovGen:

    1. Remove x/globalfee module and revert to older and simpler fee decorator
    2. Remove IBC and related modules (e.g. ICA, Packat Forwarding Middleware, etc.)
    3. Remove Interchain Security module
    4. Revert to standart Cosmos SDK v0.46.16 without the Liquid Staking Module (LSM)
