
## DAPP Setup
After installing Ganache, NPM, and MetaMask:
Install ipfs-mini: 
npm install --save ipfs-mini

Install project dependencies from project directory: **npm install**
   
Compile the Truffle project by entering the following command in the terminal window:
**truffle compile**
   
Migrate the smart contract:
**truffle migrate --reset**

Set MetaMask URL to http://127.0.0.0:7545.
   
Run the application: **npm run start**

Enter all required details, and press confirm. MetaMask will ask to confirm the transaction.
A pop-up will show up with your patient ID.
You can use this number or a past number during the same session to look up your patient record.
Press Home to enter a new immunization record without closing the session.

If you restart the app, the old records will be wiped.

## Usage
On the first page, type in your name, a choice of immunization proof, a location of immunization, and the date. 
On submit, MetaMask will pop up to ask you to approve the transaction.
On approval, there will be a pop up that shows you your assigned patient id.
The next page will have a form available where you can enter your patient id to look up your vaccination records.
This page will also tell you until which date each vaccination is valid until.

## Analytics
We generated sample data based on business logic for this application and created some basic visuals off it.
The code for data generation is in analytics/data_mockup.ipynb
The charts are exported to the analytics directory.

A couple charts are in the same jupyter notebook as the data generation code.
The rest are in the analytics/excel_graphs directory.



