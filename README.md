## GitHub URL: [https://bit.ly/2IqATCK](https://bit.ly/2IqATCK)
**Note:**  Capital "i" and not "l" in the URL.
<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">
# An Introduction to IBM Blockchain Platform (IBP)!

### From Hyperledger Fabric to IBM Blockchain Platform 2.0

Presented by: [Lennart Frantzell](linkedin.com/in/lennartfrantzell)

**Contents**

- [IBM Cloud and IBM Blockchain Platform](#ibm-cloud-and-ibm-blockchain-platform)
  * [IBM Cloud (Sign-up)](#sign-up-for-ibm-cloud)
    + [Run IBM Blockchain Platform](#run-ibm-blockchain-platform-on-the-ibm-cloud)
    + [Run a free Kubernetes Cluster](#run-a-free-kubernetes-cluster-on-the-ibm-cloud)
- [Development](#development)
  * [Prerequisites](#prerequisites)
    + [Linux](#linux)
    + [Mac OS](#mac-os)
    + [Windows](#windows)
    + [Required Packages](#packages)
    + [Visual Studio Code](#visual-studio-code)
  * [Hands-On Lab](#hands-on-lab)
  * [Additonal Lab](#additional-lab)
- [Reference](#reference)
  * [Upcoming Events](#upcoming-events)
  * [Blockchain - When did it start?](#blockchain-genesis-how-did-it-all-start)
  * [Hyperledger (HL) Fabric](#hyperledger-fabric)
  * [Recent News](#recent-news)
  * [Twitter Accounts](#twitter-accounts-to-follow)

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

##  IBM Cloud and IBM Blockchain Platform

### Sign-up for [IBM Cloud](https://ibm.biz/Bdzqsf)

<img src="login.png">

#### Run [IBM Blockchain Platform](https://cloud.ibm.com/catalog?search=blockchain) on the IBM Cloud
- Select the "Blockchain Platform | IBM IAM-enabled" option.  (IAM refers to Identity Access Management)

<img src="IBP_2.0.png">

#### Run a [Kubernetes Cluster](https://cloud.ibm.com/kubernetes/catalog/cluster) (free) on the IBM Cloud

##### Reference
- [IBM Cloud Catalog](https://cloud.ibm.com/catalog)
- <a href="https://cloud.ibm.com/docs/services/blockchain?topic=blockchain-ibp-saas-pricing">IBP Pricing</a> <br>
Note: "You can preview the IBM Blockchain Platform at no charge for 30 days when you link your IBM Blockchain Platform service instance to an IBM Cloud - Kubernetes (free cluster).  Performance will be limited by throughput, storage and functionality.  IBM Cloud will delete your Kubernetes cluster after 30 days and you cannot migrate any nodes or data from a free cluster to a paid cluster."

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

## Development

<img src="VSC_BC.png">

### Prerequisites

#### Linux
Open your terminal environment and update the respositories and installed packages using the following command: <br>
sudo apt-get update && sudo apt-get upgrade

#### Mac OS
We recommend using a package installer like [Homebrew](https://brew.sh/) to facilitate the installation of packages. <br>
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

If needed, there are [other installation options](https://docs.brew.sh/Installation) available.

#### Windows
We recommend using a package installer like [Chocolately](https://chocolatey.org/) to facilitate the installation of packages. <br>
- Install with cmd.exe using the following command: <br>
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"

- Install with PowerShell.exe* using the following command: <br>
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

* An additional step is needed to ensure Get-ExecutionPolicy is not Restricted.

If needed, reference the [installation instructions](https://chocolatey.org/install).

#### [Visual Studio Code](https://code.visualstudio.com)
Download and Install VS Code - a free source-code editor developed by Microsoft for Windows, Linux and Mac OS. It includes support for debugging, embedded Git control and GitHub, syntax highlighting, intelligent code completion, snippets, and code refactoring.

##### [Install IBM Blockchain Platform (extension) for VS Code](https://marketplace.visualstudio.com/items?itemName=IBMBlockchain.ibm-blockchain-platform)

- [An Introduction to Programming on Hyperledger Fabric](https://www.slideshare.net/LennartF/ibp-technical-introduction)

- [IBM Blockchain Platform (IBP) Presentation](https://www.slideshare.net/LennartF/ibm-blockchain-platform-explained-149106072)

- [IBM Blockchain Solutions - Slides](https://www.slideshare.net/LennartF/ibm-blockchain-solutions-149098151)

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">
<img src="architecture.png">

### Hands-On Lab
**Developing Smart Contracts using Visual Studio (VS) Code**

Ensure you have [VS Code](https://code.visualstudio.com) installed and the [IBM Blockchain Platform extension](https://marketplace.visualstudio.com/items?itemName=IBMBlockchain.ibm-blockchain-platform).

https://cloud.ibm.com/docs/services/blockchain?topic=blockchain-develop-vscode#develop-vscode-install

Go through Tutorial One in VS Code: Local Smart Contract Development.
<img src="VSCODE_TUT1.PNG" width="300" height="500">
Follow the typical workflow from generating a new smart contract project, deploying code to the <i>local_fabric_runtime</i> and testing your transactions via an <i>application gateway</i>.

### Additional Lab
[Build a Blockchain Insurance App](https://developer.ibm.com/patterns/build-a-blockchain-insurance-app/)

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">

## Reference

### Upcoming Events

**June 21, 2019** - [Blockchain Developer Summit](https://blockchain-developer-summit.splashthat.com)

[IBM Developer SF Bay Area](https://www.meetup.com/IBM-Developer-SF-Bay-Area-Meetup/) (Meetup Group)

[IBM Developer SF Bay Area Events](https://www.meetup.com/IBM-Developer-SF-Bay-Area-Meetup/events/) (Meetup Events)

### Blockchain Genesis: How did it all start?

During the Global Financial Crisis in 2008: Oct 2008. <br>
It all started with Satoshi Nakamoto and his whitepaper [BitCoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf) which addressed a key problem in electronic commerce:
<p><i><b>
A purely peer-to-peer version of electronic cash would allow online payments to be sent directly from one party to another without going through a financial institution or any intermeditary. 
<p> 
Digital signatures provide part of the solution, but the main benefits are lost if a trusted third party is still required to prevent double-spending. 
<p>
We propose a solution to the double-spending problem using a peer-to-peer network.</i></b> 

### Hyperledger Fabric
Enterprise grade permissioned distributed ledger platform that offers modularity and versatility for a broad set of industry use cases.

#### [HL Fabric (GitHub)](https://github.com/hyperledger/fabric)

#### [Writing your first application using Smart Contracts (Node.js) in Hyperledger Fabric](https://hyperledger-fabric.readthedocs.io/en/release-1.4/write_first_app.html#writing-your-first-application)

#### [Hyperledger Fabric 1.4.1 - Release Notes](https://hyperledger-fabric.readthedocs.io/en/release-1.4/index.html)

1. [Hyperledger Fabric - What's New](https://hyperledger-fabric.readthedocs.io/en/release-1.4/whatsnew.html)

2. [Raft Ordering Service](https://hyperledger-fabric.readthedocs.io/en/release-1.4/whatsnew.html#raft-ordering-service) -
Fault Tolerance Consensus Algorithm   

- [Use Cases for Blockchain](https://www.ibm.com/blockchain/use-cases/)

- [IBM Blockchain - Garage Services](https://www.ibm.com/blockchain/garage)

### Recent News

- [Does Hyperledger Fabric Perform at Scale?](https://www.ibm.com/blogs/blockchain/2019/04/does-hyperledger-fabric-perform-at-scale/)

- [Forbes: Blockchain Goes To Work At Walmart, Amazon, JPMorgan, Cargill and 46 Other Enterprises](https://www.forbes.com/sites/michaeldelcastillo/2019/04/16/blockchain-goes-to-work/#3aa207de2a40)

- [Cargill - Hyperledger Grid](https://www.cargill.com/2019/cargill-invests-digital-engineering-to-support-hyperledger-grid)

- [Target Blockchain for Supply Chain](https://www.coindesk.com/retail-giant-target-is-working-on-a-blockchain-for-supply-chains)

- [Why new off-chain storage is required for blockchains](https://www.ibm.com/downloads/cas/RXOVXAPM)

### Twitter Accounts to Follow

- [IBM Blockchain (Official)](https://twitter.com/ibmblockchain)

- [Christopher Ferris](https://twitter.com/christo4ferris) | IBM Fellow CTO - Open Technology

- [Arnaud J Le Hors](https://twitter.com/lehors) | IBM - Senior Technical Staff Member

- [Christian Cachin](https://twitter.com/cczurich) | IBM Cryptographer, Zurich

- [Mark Parzygnat](https://twitter.com/meetmarkp) | IBM Blockchain Program Director

<img src="https://farm5.staticflickr.com/4503/37148677233_71edc5a37b_o.png" width="1041" height="53" alt="blueband">
