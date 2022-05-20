# Crypto Wallet Demo

This python application is a demo on utilising a cryptocurrency wallet to make transactions. The program uses streamlit as a frontend, and you can run it with >streamlit run fintech_finder.py

---

The program is designed to work with a Ganache instance which simulates a crypto currency wallet. After downloading the application and running a quickstart environment, you can see the default senders account on the first entry as seen below
![](Images/account_balance.png)

You will need to create or edit an environment file to include a "MNEMONIC" with the provided mnemonic from Ganache

---

When running Streamlit, it will automatically pull the account details from the Ganache instance. Using the below image as a reference, you can see a list of professionals for hire on the main page, and on the leftis the UI to select a professional to hire and how long to hire them for. It will confirm the details of the transaction and calculate the total cost of the hire in ether. Pressing the "send transaction" button will send the transaction to your Ganache instance

![](Images/UI.png)

---

After pressing send transaction, you should be able to see the transaction on ganache as seen below
![](Images/transaction.png)

---

You can also check the receivers details by clicking the 'to contract address'

![](Images/to_address.png)