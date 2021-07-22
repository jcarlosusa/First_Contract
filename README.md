# First_Contract
Build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic!

The project will use Remix IDE and create to  a new contract called AssociateProfitSplitter.sol. I am using Ganache development chain, and point MetaMask to localhost:8545

## Level One: The AssociateProfitSplitter Contract

Once the code is ready 'AssociateProfitSplitter.sol' we have to complile with the compliler 0.5.0
 
 You will see a Deploy (orange) button, wehere you  can click the down arrow to type the address of the three employees

 ![Deploy](/Images/deploy.png)

 At beginning the balance for all employees will be the same, in this example 100.00 ETH

 - employee_one = 0xb2Cd47a7FECac2fa041FfEd55BC6f1F830DCb70
 - employee_two = 0x2D0116D4d80cd8e7406E32233Ea5551DCD315750
 - employee_three = 0x53a110D8Df9032d2e886dC800Bf154434847f3F2

 ![Deploy](/Images/deploy_addrs.png)

We are ready to transact with value 101 wei, Contract selected and all address for the employees

![Deploy](/Images/contract.png)

![eployed Contracts](/Images/deployed_contracts.png)

## Level Two: The TieredProfitSplitter Contract

In this contract, we will calculate rudimentary percentages for different tiers of employees (CEO, CTO, and Bob).

Testing the contract functionality by depositing various Ether values (greater than 100 wei)

![eployed Contracts](/Images/deposit.png)

## Level Three: The Level Three: The DeferredEquityPlan Contract

We are managing an employee's deferred equity incentive plan in which 1000 shares will be distributed over 4 years to the employee.

The employees receive shares for joining and staying with the firm. They may receive, an award of 1,000 shares when joining, but with a 4 year vesting period for these shares. 

This means that these shares would stay with the company, with only 250 shares (1,000/4) actually distributed to and owned by the employee each year. If the employee leaves within the first 4 years, he or she would forfeit ownership of any remaining (“unvested”) shares.

![Deferred Contract](/Images/contract_deferred.png)

![Deferred Contract, deactivate, distribute](/Images/deposit.png)

