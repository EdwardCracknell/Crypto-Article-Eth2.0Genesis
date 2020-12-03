# Eth2.0Genesis

What it was like to be a part of the ETH2.0 genesis

1. Testnets

In preparation for the launch I joined the Medalla, Zinken and Pyrmont testnets and used an old mac book pro 2013 model with a 256 SSD to get up to scratch with validating. The process setting up an ETH1 node. For this I used Go Ethereum (Geth), this was ran on a fast sync mode and took roughly 5GB of space on the SSD to sync to the goerli ETH tesnet. My ETH2 validator of choice was Prysm however I did go through the process of setting up Lighthouse as insurance inc case I had any issues with my ETH1 or ETH2 validator then I could use infura ( 3rd party node service ) to cover my ETH1 and Lighthouse to cover my ETH2 to avoid any negative effects on my balance if something went wrong.

2. Preparing validator clients and hardware for mainnet launch

I didn’t want to make my 32 ETH deposit mainnet depsoit to soon as I was afraid the minimum threshold for deposits might not be reached in time to have the genesis date at 1/12/2020 12:00:00 GMT. One week and one day before I was happy enough with about 70% of deposits having already been made to the contract that I could be fairly sure ETH2 would launch at the expected time and not be delayed. I used the ETH2 launchpad to set up my deposit which ran smoothly but then quickly hit a hurdle when I tried to sync Geth to mainnet. Mainnet is a lot bigger than testnet so after a few days of downloading my 256 SSD drive had completely filled up and Geth throw an error. If I was going to run my validator in a truly decentralised fashion (not use a 3rd party infura node or other service) I would need to upgrade my machine. Some quick digging revealed that I would need at least 500GB but preferably 1TB of SSD space. So I got to work on eBay hunting for a machine that would be express delivery (1-2 days max) with a good CPU and 1TB SSD. I found a 2018 mac book pro that fit perfectly and bought it for £1250. I then proceded to beg the seller to send it next day delivery and made sure he knew I would pay whatever it took to get it asap. My wish was granted and I received the machine quickly. The Geth sync took around 315 GB of SSD and I had it running a few days before the launch deadline...  phew!

Further preparations I made were to install Ubuntu onto another PC I had with the lighthouse client so that if my main validator ever has issues I can hopefully make a quick switch and get it back up online. 

3. Mainnet - all systems start!

On the day I joined the youtube Ethstaker livestream and Bankless livestream to listen in on all the devs and enthusiasts nervously awaiting the launch. I made sure the staker was online and ready to take part from genesis. Then it was just a case of waiting.... I remember seeing the Prysm client count down in the seconds to the first genesis block, that was the most nervous I had been the whole time, would it work? Had I made a mistake? Luckily it started validating and I could visibly see on beaconch.in that it was working. One by one my slots were proposed and eventually we finalized the ephoch. It was a truely wonderful to experience the next milestone in Ethereum come to life before my eyes. Time to crack open a beer and celebrate something special. 
