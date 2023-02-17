# Futures Contract Loss Analysis - VIOP Derivatives Market in Istanbul Stock Exchange



![Logo](https://www.borsaistanbul.com/files/duyuru_viop-logo-2-k.jpg)



Derivatives Market (VIOP) is the market where derivatives contracts are traded on single stock, index, foreign currency, energy, commodities, precious metals, foreign index, metal, TLREF and government bond. By creating a transparent and secure investment environment for domestic and foreign investors, Derivetives Market (VIOP) provides investors with opportunities such as hedging, portfolio diversification, leverage effect, effective price formation and access to high liquidity.

## future_loss_analysis() function:

***future_loss_analysis()*** function performs a simulation of a future derivative investment in the USDTRY currency pair. The purpose of the simulation is to analyze the potential loss of the investment under different price scenarios.

The function takes in 3 inputs:

contract_price: the price at which the contract is bought.
contract_amount: the number of contracts bought.
current_contract_price: the current market price of the contract.

The simulation works by decreasing the contract price by 0.05 at each iteration until the amount of the contracts reaches 0. At each iteration, the function calculates various metrics such as the initial investment, total capital, contract size in USD, the total size of the investment in TRY. These metrics are stored in a Pandas DataFrame and the final result is returned by the function. The resulting DataFrame is then saved to an Excel file. You can easily edit the code for different future contracts with different amount of contracts.


## Update of the code with version 2 / 17.02.2023:

I updated the code following my friend Quentin's recommendation to clear depreciation errors and added comments to improve its readability.
