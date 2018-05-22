<h2><strong>Dextro Community Core (Version 1.0.1)</strong></h2>

<a href="https://bitcointalk.org/index.php?topic=3366303.0">WARNING!!! BITCOINTALK 1st dev</a>

<h2><strong>What is Dextro?</strong></h2>

<p>
Dextro (DXO) is an innovative cryptocurrency. A form of digital currency secured by cryptography and issued through a decentralized and advanced mining market. Based on Dash and PIVX, it's an enhanced and further developed version, featuring the masternode technology with 85% Reward, near-instant and secure payments as well as anonymous transactions. Dextro has great potential for rapid growth and expansion. Based on a total Proof of Work, Proof of Stake and Masternode system, it is accesible to everyone, it ensures a fair and stable return of investment for the Graphics Processing Units (GPUs) miners and the Masternode holders.
</p>

<h2><strong>Coin Specs</strong></h2>
<p>
Coin name: Dextro<br />
Ticker: DXO<br />
Algo: Skunkhash<br />
<br />
Port: 39320<br />
RPC: 39321<br />
<br />
Blockreward till block 3500: 3 DXO<br />
Blockreward after block 3500: 30 DXO<br />
<br />
PoS start at block 95000<br />
Block time: 60 seconds<br />
Mature time: 60 blocks<br />
Total supply: 25000000<br />
PoW 15% / PoS 15% (after block 95000)<br />
<br />
Masternode collateral: 1000 DXO<br />
Masternode Rewards: 85%<br />
</p>


<h2><strong>Wallet Setup?</strong></h2>
<p>
# git clone https://github.com/dextrocoin/dextro.git <br />
# cd dextro/ <br />
# chmod a+x autogen.sh <br />
# chmod a+x share/genbuild.sh <br />
# chmod a+x src/leveldb/build_detect_platform <br />
# ./autogen.sh <br />
# ./configure LDFLAGS="-L/usr/local/BerkeleyDB.4.8/lib/" CPPFLAGS="-I/usr/local/BerkeleyDB.4.8/include/" <br />
# make <br />
</p>

Install Dextro Masternode use realbityoda guide at: github.com/Realbityoda/Dextro<br />
<br />
For sync edit dextro.conf <br />
<br />
addnode=seed1.dextro.io <br />
addnode=seed2.dextro.io <br />
addnode=seed3.dextro.io <br />
addnode=seed4.dextro.io <br />
addnode=seed5.dextro.io <br />
addnode=seed6.dextro.io <br />
addnode=seed7.dextro.io <br />
addnode=seed8.dextro.io <br />
</p>

<h2><strong>License</strong></h2>
<p>
Dextro Core is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT.
 </p>
