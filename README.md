# Figment Learn - Solana Pathway

We made this app to help developers learn about Solana.

You will build a simple web client using Solana's JS SDK to interact with a Solana program (aka smart contract) that you will deploy using the Solana CLI.

Read the instructions on how to get setup over at [Figment Learn](https://learn.figment.io/network-documentation/solana/solana-pathway).  
Learn more about [Figment](https://figment.io/)

gh repo clone abraham-yusuf/solana-pathway

cd solana-pathway

yarn

cp .env.example .env.local  //let's edit your API Key datahub in .env.local

yarn start


if you following step 6-7, you'll need update file in ./src/components/Call.jsx 
find the line of codes : const PAYER_SECRET_KEY= null, to const PAYER_SECRET_KEY=[array file secret here : 2.222xxxxx] , you can find it in : cat ~/.config/solana/id.json copy and paste it

edit one more line code in : const PROGRAM_SECRET_KEY= null, (edit to) const PROGRAM_SECRET_KEY=[program secret key here : 2xx.xx.xx] , find in .dist/program/helloworld-keypair.json

<img width="1446" alt="Screen Shot 2021-06-15 at 5 43 00 PM" src="https://user-images.githubusercontent.com/206753/122127424-240c3100-ce01-11eb-83db-4fc99c19406f.png">
