- 👋 Hi, I’m @ozzy-oz-69
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ozzy-oz-69/ozzy-oz-69 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!-- TODO: Step 1: Include Fortmatic SDK Script -->
<script src="https://cdn.jsdelivr.net/npm/fortmatic@latest/dist/fortmatic.js"></script>
<!-- End Step 1 -->
$ npm i --save fortmatic@latest
// TODO: Step 2: Setup Developer API Key
let fm = new Fortmatic('YOUR_API_KEY');
web3 = new Web3(fm.getProvider());
// End Step 2
// TODO: Step 3: Send Transaction Implementation
web3.eth.sendTransaction({
  // From address will automatically be replaced by the address of current user
  from: '0x0000000000000000000000000000000000000000',
  to: address,
  value: web3.utils.toWei(amount, 'ether')
});
// End Step 3
