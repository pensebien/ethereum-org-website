---
title: Ethereum kehittäjille
description: Ohjeet, resurssit ja työkalut kehittäjille Ethereumin rakentamiseen.
lang: fi
sidebar: true
sidebarDepth: 2
---

# Kehittäjäresurssit {#developer-resources}

<div class="featured">Ohjeet, resurssit ja työkalut kehittäjille Ethereumin rakentamiseen.</div>

## Näin pääset alkuun {#getting-started}

**Jos olet uusi Ethereum-kehittäjä, olet oikeassa paikassa!** Näillä Ethereumin yhteisön kirjoittamilla ohjeilla pääset tutustumaan Ethereumin pinoon ja pääkäsitteisiin, jotka saattavat olla erilaisia muusta tuntemastasi sovelluskehityksestä.

Haluatko aloittaa koodaamisen heti? [Aloita rakentaminen täältä](/fi/build/).

Tarvitsetko perusteellisempaa aloitusta? Katso [oppimisresurssit](/fi/learn/).

**Hyödyllisiä resursseja englanniksi**

- [Getting up to speed on Ethereum](https://medium.com/@mattcondon/getting-up-to-speed-on-ethereum-63ed28821bbe) *Aug 7, 2017 - Matt Condon*
- [Ethereum In Depth, Part 1](https://blog.openzeppelin.com/ethereum-in-depth-part-1-968981e6f833/) *May 11, 2018 - Facu Spagnuolo*
- [Ethereum In Depth, Part 2](https://blog.openzeppelin.com/ethereum-in-depth-part-2-6339cf6bddb9/) *July 24, 2018 - Facu Spagnuolo*
- [Ethereum Development Walkthrough, Parts 1-5](https://hackernoon.com/ethereum-development-walkthrough-part-1-smart-contracts-b3979e6e573e) *Jan 14, 2018 - dev_zl*
- [Ethereum 101, Parts 1-7](https://kauri.io/collection/5bb65f0f4f34080001731dc2/ethereum-101) *Feb 13, 2019 - Wil Barnes*
- [Full Stack Hello World Voting Ethereum Dapp Tutorial](https://medium.com/@mvmurthy/full-stack-hello-world-voting-ethereum-dapp-tutorial-part-1-40d2d0d807c2)  *Feb 2019 - Mahesh Murthy*
- [Mastering Ethereum - A comprehensive textbook available for free online](https://github.com/ethereumbook/ethereumbook) *Dec 1, 2018 - Andreas Antonopoulos & Gavin Wood*
- [Ethereum Developer Portal - Everything you need to get started building on Ethereum](https://ethereum.consensys.net/ethereum-dev-portal) *Päivitetään usein - ConsenSys*
- [Deconstructing a Solidity Contract](https://blog.openzeppelin.com/deconstructing-a-solidity-contract-part-i-introduction-832efd2d7737/) *Aug 13, 2018 - Alejandro Santander & Leo Arias*
- [Full Stack Dapp Tutorial Series](https://kauri.io/collection/5b8e401ee727370001c942e3)  *Päivitetään usein - Joshua Cassidy*

## Kielet älysopimuksille {#smart-contract-languages}

Mitä tahansa ohjelmaa, joka suoritetaan Ethereum Virtual Machine (EVM) -ympäristössä, kutsutaan yleisesti "älysopimukseksi". Suosituimmat ohjelmointikielet Ethereumin älysopimuksille ovat **Solidity** ja **Vyper**. Lisäksi [kehityksen alla on muita kieliä](https://github.com/ConsenSys/ethereum-developer-tools-list#smart-contract-languages).

**Solidity -** ***Ethereumin suosituin ohjelmointikieli C++:n, Pythonin ja JavaScriptin inspiroimana.***

- [Dokumentaatio](https://solidity.readthedocs.io)
- [GitHub](https://github.com/ethereum/solidity/)
- [Solidity Gitter chat-huone](https://gitter.im/ethereum/solidity/)

**Vyper -** ***Ethereumin tietoturvaan keskittyvä ohjelmointikieli, joka perustuu Pythoniin.***

- [Dokumentaatio](https://vyper.readthedocs.io)
- [GitHub](https://github.com/ethereum/vyper)
- [Vyper Gitter chat-huone](https://gitter.im/ethereum/vyper)

**Etsitkö muita vaihtoehtoja?**

- [Ethereum-kehitystyökalujen luettelo #SmartContractLanguages](https://github.com/ConsenSys/ethereum-developer-tools-list#smart-contract-languages)

## Kielikohtaiset resurssit {#language-specific-resources}

Rakennamme kielikohtaisia aloitussivuja kehittäjille opettamaan lisää Ethereumista useilla suosituilla ohjelmointikielillä.

- [Ethereum Java-kehittäjille](/fi/java/)
- [Ethereum Python-kehittäjille](/fi/python/)
- [Ethereum JavaScript-kehittäjille](/fi/javascript/)
- [Ethereum Go-kehittäjille](/fi/golang/)
- [Ethereum Rust-kehittäjille](/fi/rust/)
- [Ethereum .NET-kehittäjille](/fi/dot-net/)
- Lisää tulossa pian! Etkö näe suosikkikieltäsi täällä? [Avaa ongelma](https://github.com/ethereum/ethereum-org-website/issues/new/choose)!

## Kehitystyökalut {#developer-tools}

Ethereumilla on suuri ja kasvava määrä työkaluja, jotka auttavat kehittäjiä rakentamaan, testaamaan ja julkaisemaan sovelluksia. Alla on luettelo suosituimmista työkaluista, joilla pääset alkuun. Jos haluat sukeltaa aiheessa syvemmälle, katso tämä [kattava lista](https://github.com/ConsenSys/ethereum-developer-tools-list).

### Ohjelmistokehykset {#frameworks}

**Truffle -** ***Kehitysympäristö, testauskehys, putkiliikenteen rakentaminen ja muita työkaluja.***

- [trufflesuite.com](https://www.trufflesuite.com/)
- [GitHub](https://github.com/trufflesuite/truffle)

**Embark -** ***Kehitysympäristö, testauskehys ja muita työkaluja integroituna Ethereumiin, IPFS:ään ja Whisperiin.***

- [Dokumentaatio](https://embark.status.im/docs/)
- [GitHub](https://github.com/embark-framework/embark)

**Waffle -** ***Ohjelmistokehys edistyneelle älysopimuskehitykselle ja -testaukselle (pohjautuu ethers.js:ään).***

- [getwaffle.io](https://getwaffle.io/)
- [GitHub](https://github.com/EthWorks/Waffle)

**Etherlime -** ***Ethers.js:ään pohjautuva ohjelmistokehys dapp-kehitykselle (Solidity & Vyper), julkaisemiselle, debuggaukselle, testaukselle ja muihin tarkoituksiin.***

- [Dokumentaatio](https://etherlime.readthedocs.io/en/latest/)
- [GitHub](https://github.com/LimeChain/etherlime)

### Muut työkalut {#other-tools}

**Ethereum Grid -** ***Työpöytäsovellus Ethereum-asiakasohjelmien ja -työkalujen lataamiseen, konfigurointiin ja ajamiseen.***

- [grid.ethereum.org](https://grid.ethereum.org)
- [GitHub](https://github.com/ethereum/grid)

**Buidler -** ***Tehtävänsuorittaja Ethereum-älysopimusten kehittäjille.***

- [builder.dev](https://buidler.dev)
- [GitHub](https://github.com/nomiclabs/buidler)

**OpenZeppelin SDK -** ***The Ultimate Smart Contract Toolkit: Kokoelma työkaluja, jotka helpottavat älysopimusten kehittämistä, kääntämistä, päivittämistä, julkaisemista ja käyttämistä.***

- [OpenZeppelin SDK](https://openzeppelin.com/sdk/)
- [GitHub](https://github.com/OpenZeppelin/openzeppelin-sdk)
- [Keskustelupalsta](https://forum.openzeppelin.com/c/sdk)

**The Graph -** ***Protokolla Ethereumin ja IPFS-datan indeksöintiin ja tietokantakyselyihin käyttäen GraphQL:ää.***

- [The Graph](https://thegraph.com/)
- [Graph Explorer](https://thegraph.com/explorer/)
- [Dokumentaatio](https://thegraph.com/docs/)
- [GitHub](https://github.com/graphprotocol/)
- [Discord](https://thegraph.com/discord)

**Tenderly -** ***Alusta, jossa voit helposti monitoroida älysopimuksiasi virheen seurannalla, hälytyksillä, tehokkuusmittareilla ja yksityiskohtaisella sopimusanalyysillä.***

- [tenderly.dev](https://tenderly.dev/)
- [GitHub](https://github.com/Tenderly)
- [Discord](https://discord.gg/eCWjuvt)

**Python-työkalut -** ***Erinlaisia kirjastoja vuorovaikutukseen Ethereumilla Pythonin avulla.***

- [py.ethereum.org](http://python.ethereum.org/)
- [web3.py Github](https://github.com/ethereum/web3.py)
- [web3.py Chat](https://gitter.im/ethereum/web3.py)

**Brownie -** ***Python-pohjainen kehitysympäristö ja testauskehys.***

- [Dokumentaatio](https://eth-brownie.readthedocs.io/en/latest/)
- [GitHub](https://github.com/iamdefinitelyahuman/brownie)

**web3j -** ***Java/Android/Kotlin/Scala-integraatiokirjasto Ethereumille.***

- [web3j.io](https://web3j.io)
- [GitHub](https://github.com/web3j/web3j)
- [Dokumentaatio](https://docs.web3j.io/)
- [Gitter](https://gitter.im/web3j/web3j)

**One Click Dapp -** ***Luo frontend suoraan ABI:stä nopeaan kehitykseen ja testaukseen.***

- [OneClickDapp.com](https://oneclickdapp.com)
- [Truffle Plugin](https://npmjs.org/package/oneclick)
- [Remix Plugin](https://github.com/pi0neerpat/remix-plugin-one-click-dapp)
- [GitHub](https://github.com/pi0neerpat/one-click-dapp)

**Etsitkö muita vaihtoehtoja?**

- [Ethereum-kehitystyökalujen luettelo #Frameworks](https://github.com/ConsenSys/ethereum-developer-tools-list#frameworks)

## Ohjelmointiympäristöt (IDE) {#integrated-development-environments-ides}

**Ethereum Studio -** ***Web-pohjainen IDE, ideaalinen uusille kehittäjille, jotka haluavat kokeilla älysopimuksia. Ethereum Studio sisältää useita malleja, MetaMask-integraation, liiketapahtumien kirjauksen ja sisäänrakennetun selaimen Ethereum Virtual Machine (EVM) -ympäristön, jotka auttavat pääsemään alkuun mahdollisimman nopeasti Ethereumilla rakentamisessa.***

- [studio.ethereum.org](https://studio.ethereum.org)
- [superblocks.com/ethereum-studio](https://superblocks.com/ethereum-studio)
- [GitHub](https://github.com/SuperblocksHQ/ethereum-studio)

**Visual Studio Code -** ***Ammattitason alustariippumaton IDE, Ethereumin virallisella tuella.***

- [Visual Studio Code](https://code.visualstudio.com/)
- [Azure Blockchain Development Kit, Ethereumille](https://marketplace.visualstudio.com/items?itemName=AzBlockchain.azure-blockchain)
- [Azure Blockchain Workbench plugin](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/microsoft-azure-blockchain.azure-blockchain-workbench?tab=Overview)
- [Koodiesimerkit](https://github.com/Azure-Samples/blockchain/blob/master/blockchain-workbench/application-and-smart-contract-samples/readme.md)
- [GitHub](https://github.com/microsoft/vscode)

**Remix -** ***Web-pohjainen IDE sisäänrakennetulla staattisella analyysillä ja testilohkoketjussa toimivalla virtuaalikoneella.***

- [remix.ethereum.org](https://remix.ethereum.org/)

**EthFiddle -** ***Web-pohjainen IDE, joka mahdollistaa älysopimuksen kirjoittamisen, kääntämisen ja debuggauksen.***

- [ethfiddle.com](https://ethfiddle.com/)
- [Gitter](https://gitter.im/loomnetwork/ethfiddle)

**Etsitkö muita vaihtoehtoja?**

- [Ethereum-kehitystyökalujen luettelo #IDEs](https://github.com/ConsenSys/ethereum-developer-tools-list#ides)

## Frontend JavaScript API {#frontend-javascript-apis}

**Web3.js -** ***Ethereum JavaScript API.***

- [Dokumentaatio](https://web3js.readthedocs.io/en/1.0/)
- [GitHub](https://github.com/ethereum/web3.js/)

**Ethers.js -** ***Kokonainen Ethereum-lompakkototeutus ja työkalut JavaScriptillä ja TypeScriptillä. ***

- [Dokumentaatio](https://docs.ethers.io/ethers.js/html/)
- [GitHub](https://github.com/ethers-io/ethers.js/)

**light.js -** ***Korkean tason reaktiivinen JS-kirjasto, joka on optimoitu kevyille asiakasohjelmille.***

- [Dokumentaatio](https://paritytech.github.io/js-libs/light.js/)
- [GitHub](https://github.com/paritytech/js-libs/tree/master/packages/light.js)

**Web3-wrapper -** ***Typescript vaihtoehto Web3.js:lle.***

- [Dokumentaatio](https://0x.org/docs/web3-wrapper#introduction)
- [GitHub](https://github.com/0xProject/0x-monorepo/tree/development/packages/web3-wrapper)

**Etsitkö muita vaihtoehtoja?**

- [Ethereum-kehitystyökalujen luettelo #Frontend-Ethereum-APIs](https://github.com/ConsenSys/ethereum-developer-tools-list#frontend-ethereum-apis)

## Backend API {#backend-apis}

**Infura -** ***Ethereum API palveluna***

- [infura.io](https://infura.io)
- [Dokumentaatio](https://infura.io/docs)
- [GitHub](https://github.com/INFURA)

**Cloudflaren Ethereum-yhdyskäytävä.**

- [cloudflare-eth.com](https://cloudflare-eth.com)

**Nodesmith -** ***JSON-RPC API-pääsy Ethereumin pää- ja testiverkkoihin.***

- [nodesmith.io](https://nodesmith.io/network/ethereum/)
- [Dokumentaatio](https://nodesmith.io/docs/#/ethereum/apiRef)

**Chainstack -** ***Jaetut ja dedikoidut Ethereum-solmut palveluina.***

- [chainstack.com](https://chainstack.com)
- [Dokumentaatio](https://docs.chainstack.com)

## Tallennustila {#storage}

**IPFS -** ***InterPlanetary File System on hajautettu varasto- ja tiedostoviittauksiin käytettävä järjestelmä Ethereumissa.***

- [ipfs.io](https://ipfs.io/)
- [Dokumentaatio](https://docs.ipfs.io/)
- [GitHub](https://github.com/ipfs/ipfs)

**Swarm -** ***Hajautettu varastojärjestelmä ja sisällönjakelupalvelu Ethereumin web3 stackille.***

- [Swarm](https://ethersphere.github.io/swarm-home/)
- [GitHub](https://github.com/ethersphere/swarm)

**OrbitDB -** ***Hajautettu vertaisverkon tietokanta IPFS:n päällä.***

- [Dokumentaatio](https://github.com/orbitdb/field-manual)
- [GitHub](https://github.com/orbitdb/orbit-db)

## Turvallisuustyökalut {#security-tools}

### Älysopimusten turvallisuus {#smart-contract-security}

**Slither -** ***Solidityn staattinen analyysikehys, kirjoitettu Python 3:lla.***

- [GitHub](https://github.com/crytic/slither)

**MythX -** ***Tietoturva-analyysi API Ethereumin älysopimuksille.***

- [mythx.io](https://mythx.io/)
- [Dokumentaatio](https://docs.mythx.io/en/latest/)

**Mythril -** ***Tietoturva-analyysityökalu EVM-tavukoodille.***

- [mythril](https://github.com/ConsenSys/mythril)
- [Dokumentaatio](https://mythril-classic.readthedocs.io/en/master/about.html)

**SmartContract.Codes -** ***Hakukone vahvistetuille solidity-lähdekoodeille.***

- [smartcontract.codes (alpha)](https://smartcontract.codes/)
- [Dokumentaatio](https://github.com/ethereum-play/smartcontract.codes/blob/master/README.md)

**Manticore -** ***Komentoliittymä, joka käyttää symbolista suoritustyökalua älysopimuksissa ja binäärijärjestelmissä.***

- [GitHub](https://github.com/trailofbits/manticore)
- [Dokumentaatio](https://github.com/trailofbits/manticore/wiki)

**Securify -** ***Turvallisuustutkain Ethereumin älysopimuksille.***

- [securify.chainsecurity.com](https://securify.chainsecurity.com/)
- [Discord](https://discordapp.com/invite/nN77ckb)

**ERC20 Verifier -** ***Vahvistustyökalu, jolla varmistetaan, että sopimus kääntyy ERC20-standardin mukaisesti.***

- [erc20-verifier.openzeppelin.com](https://erc20-verifier.openzeppelin.com)
- [Foorumi](https://forum.openzeppelin.com/t/online-erc20-contract-verifier/1575)

### Muodollinen vahvistus {#formal-verification}

**Tietoa muodollisesta vahvistuksesta englanniksi**

- [How formal verification of smart-contacts works](https://runtimeverification.com/blog/how-formal-verification-of-smart-contracts-works/) *July 20, 2018 - Brian Marick*
- [How Formal Verification Can Ensure Flawless Smart Contracts](https://media.consensys.net/how-formal-verification-can-ensure-flawless-smart-contracts-cbda8ad99bd1) *Jan 29, 2018 - Bernard Mueller*

**Etsitkö muita vaihtoehtoja?**

- [Ethereum-kehitystyökalujen luettelo #Security-Tools](https://github.com/ConsenSys/ethereum-developer-tools-list#security-tools)

## Testaustyökalut {#testing-tools}

**Solidity-Coverage -** ***Vaihtoehtoinen Solidity-koodin kattavuustyökalu.***

- [GitHub](https://github.com/sc-forks/solidity-coverage)

**hevm -** ***Toteutus EVM:stä, tarkoitettu erityisesti älysopimusten yksikkötestaukseen ja debuggaukseen.***

- [GitHub](https://github.com/dapphub/dapptools/tree/master/src/hevm)
- [DappHub Chat](https://dapphub.chat/)

**Whiteblock Genesis -** ***End-to-end sandbox-kehitysympäristö ja testausalusta lohkoketjuille.***

- [Whiteblock.io](https://whiteblock.io)
- [Dokumentaatio](https://docs.whiteblock.io)
- [GitHub](https://github.com/whiteblock/genesis)

**Etsitkö muita vaihtoehtoja?**

- [Ethereum-kehitystyökalujen luettelo #Testing-Tools](https://github.com/ConsenSys/ethereum-developer-tools-list#testing-tools)

## Lohkoselaimet {#block-explorers}

Lohkoselaimet ovat palveluita, joilla voi selata Ethereumin lohkoketjua (ja sen testiverkkoja) etsimällä informaatiota tietyistä liiketapahtumista, lohkoista, sopimuksista ja muista ketjunsisäisistä tapahtumista.

- [Etherscan](https://etherscan.io/)
- [Blockscout](https://blockscout.com/)
- [Etherchain](https://www.etherchain.org/)

## Testiverkot ja faucetit {#testnets-and-faucets}

Ethereumin yhteisö ylläpitää useita testiverkkoja. Nämä on tarkoitettu kehittäjille sovellusten testaamiseen eri olosuhteissa ennen Ethereumin pääverkkoon lähettämistä.

**Ropsten -** ***Proof of Work -lohkoketju, louhittavissa testi-etheriä.***

- [Test-ether faucet](https://faucet.ropsten.be/)

**Rinkeby -** ***Proof of Authority -lohkoketju, Gethin kehitystiimin ylläpitämä.***

- [Test-ether faucet](https://faucet.rinkeby.io/)
- [Universaali faucet](https://faucets.blockxlabs.com)

**Goerli -** ***Asiakasohjelmariippumaton Proof of Authority -lohkoverkko, Goerli-yhteisön rakentama ja ylläpitämä***

- [Test-ether faucet](https://faucet.goerli.mudit.blog/)
- [goerli.net](https://goerli.net/)
- [Universaali faucet](https://faucets.blockxlabs.com)

## Asiakasohjelmat ja oman solmun ajaminen {#clients--running-your-own-node}

Ethereumin tietoverkko on rakennettu useista solmuista, joissa suoritetaan niille sopivia asiakasohjelmistoja. Useimmissa solmuissa ajetaan [Gethiä](https://geth.ethereum.org/) tai [Parityä](https://www.parity.io/ethereum/), joista kumpikin voidaan konfiguroida eri tavoilla tarpeen mukaan.

### Asiakasohjelmat {#clients}

**Geth -** ***Ethereum-asiakasohjelma, kirjoitettu Golla.***

- [GitHub](https://github.com/ethereum/go-ethereum)
- [Discord chat](https://discordapp.com/invite/nthXNEv)

**Parity -** ***Ethereum-asiakasohjelma, kirjoitettu Rustilla.***

- [parity.io](https://www.parity.io/)
- [GitHub](https://github.com/paritytech/parity-ethereum)

**Pantheon -** ***Ethereum-asiakasohjelma, kirjoitettu Javalla.***

- [pegasys.tech](http://pegasys.tech)
- [GitHub](https://github.com/PegaSysEng/pantheon/)

**Nethermind -** ***Ethereum-asiakasohjelma, kirjoitettu C# .NET Corella.***

- [Nethermind.io](http://nethermind.io/)
- [GitHub](https://github.com/NethermindEth/nethermind)
- [Gitter](https://gitter.im/nethermindeth/nethermind)

### Oman solmun ajaminen {#running-your-own-node}

**Ethnode -** ***Ethereum-solmun ajaminen (Geth tai Parity) paikallista kehitystä varten.***

- [GitHub](https://github.com/vrde/ethnode)

**Ethereum-solmujen resurssit**

- [Node Configuration Cheat Sheet](https://dev.to/5chdn/ethereum-node-configuration-modes-cheat-sheet-25l8) *Jan 5, 2019 - Afri Schoeden*

**Etsitkö muita vaihtoehtoja?**

- [Ethereum-kehitystyökalujen luettelo #Ethereum-clients](https://github.com/ConsenSys/ethereum-developer-tools-list#ethereum-clients)

## Parhaat käytännöt, suunnittelumallit ja antisuunnittelumallit {#best-practices-patterns-and-anti-patterns}

### Älysopimukset {#smart-contracts}

**DappSys -** ***Turvallista, yksinkertaista, joustavaa lohkojen rakentamista älysopimuksille.***

- [dapp.tools/dappsys](https://dapp.tools/dappsys/)
- [GitHub](https://github.com/dapphub/dappsys)

**OpenZeppelin Contracts -** ***Kirjasto turvallisille älysopimuksille.***

- [openzeppelin.com/contracts/](https://openzeppelin.com/contracts/)
- [GitHub](https://github.com/OpenZeppelin/openzeppelin-contracts)
- [Keskustelupalsta](https://forum.openzeppelin.com/c/contracts)

**aragonOS -** ***Suunnittelumallit päivitettävyydelle ja käyttöoikeuksien hallinnalle.***

- [hack.aragon.org](https://hack.aragon.org/docs/aragonos-intro.html#aragonos-provides-the-following-functionality)
- [Dokumentaatio](https://wiki.aragon.org/)

**Smart Contract Weakness Registry**

- [SWC-rekisteri](https://smartcontractsecurity.github.io/SWC-registry/)
- [GitHub](https://github.com/SmartContractSecurity/SWC-registry)

### Turvallisuus {#security}

**Parhaat käytännöt älysopimusten turvallisuudelle**

- [consensys.github.io/smart-contract-best-practices/](https://consensys.github.io/smart-contract-best-practices/)
- [GitHub](https://github.com/ConsenSys/smart-contract-best-practices/)
- [Kokoelma turvallisuussuosituksista ja parhaista käytännöistä](https://github.com/guylando/KnowledgeLists/blob/master/EthereumSmartContracts.md)

**Smart Contract Security Verification Standard (SCSVS)**

- [securing.github.io/SCSVS/](https://securing.github.io/SCSVS/)

**Etsitkö muita vaihtoehtoja?**

- [Ethereum-kehitystyökalujen luettelo #Patterns—best-practices](https://github.com/ConsenSys/ethereum-developer-tools-list#patterns--best-practices)

## Tuki ja koulutukset kehittäjille {#developer-support--training}

### Yleinen oppiminen {#general-learning}

**Ethereum Stackexchange**

- [ethereum.stackexchange.com](https://ethereum.stackexchange.com/)

**ConsenSys Academy -** ***End-to-end-kurssi Ethereum-kehittäjille, jonka voi suorittaa omalla tahdilla ja on avoin ympäri vuoden.***

- [consensys.academy](https://consensys.net/academy/ondemand/)

**Solidity Gitter chat-huone**

- [gitter.im/ethereum/solidity](https://gitter.im/ethereum/solidity/)

**Kaikki Ethereum Gitter chat-huoneet**

- [gitter.im/ethereum/home](https://gitter.im/ethereum/home)

**Chainshot -** ***Web-pohjaiset dapp-koodausoppaat.***

- [chainshot.com](https://www.chainshot.com/)

**Blockgeeks -** ***Verkkokursseja lohkoketjuteknologiasta.***

- [courses.blockgeeks.com](https://courses.blockgeeks.com/)

**DappUniversity -** ***Opi rakentamaan hajautettuja sovelluksia Ethereumin lohkoketjuun.***

- [DappUniversity.com](http://www.dappuniversity.com/)

**B9lab Academy -** ***Vanhin ammattitason Ethereum dapp-kehittäjäkurssi sekä syvempää oppimista auditoijille ja laadunvarmistajille. Sis. mentoroinnin ja koodin katselmoinnin.***

- [academy.b9lab.com](https://academy.b9lab.com)

### Pelipohjaista oppimista {#game-based-learning}

**Cryptozombies -** ***Opi koodaamaan pelejä Ethereumilla.***

- [Cryptozombies.io](https://cryptozombies.io/)

**Ethernaut -** ***Solidity-pohjainen sotapeli, jossa jokainen taso on hakkeroitava sopimus.***

- [ethernaut.openzeppelin.com](https://ethernaut.openzeppelin.com/)

**Capture the Ether -** ***Peli Ethereumin älysopimusten turvallisuudesta.***

- [capturetheether.com](https://capturetheether.com/)

## UI/UX-suunnittelu {#uiux-design}

- [Challenge of UX in Ethereum](https://medium.com/ecf-review/challenge-of-ux-in-ethereum-122e1a33688d) *June 25, 2018 - Anna Rose*
- [Designing for blockchain: what’s different and what’s at stake](https://media.consensys.net/designing-for-blockchain-whats-different-and-what-s-at-stake-b867eeade1c9) *March 22, 2018 - Sarah Baker Mills*

**Rimble UI** ***- Muokattavia komponentteja ja suunnittelustandardeja hajautetuille sovelluksille.***

- [rimble.consensys.design](https://rimble.consensys.design)
- [GitHub](https://github.com/ConsenSys/rimble-ui)

## Standardit {#standards}

Ethereum-yhteisö on ottanut käyttöön useita standardeja, jotka ovat hyödyllisiä kehittäjille. Tyypillisesti nämä esitetään nimellä [Ethereum Improvement Proposals](http://eips.ethereum.org/) (EIPs), joista käydään keskuteluja yhteisön jäsenien kesken [standardiprosessin avulla](http://eips.ethereum.org/EIPS/eip-1).

- [EIP-lista](http://eips.ethereum.org/)
- [EIP github -tietovarasto](https://github.com/ethereum/EIPs)
- [EIP-keskustelupalsta](https://ethereum-magicians.org/c/eips)
- [Ethereum Governance Overview](https://blog.bmannconsulting.com/ethereum-governance/) *March 31, 2019 - Boris Mann*
- [Playlist of all Ethereum Core Dev Meetings](https://www.youtube.com/playlist?list=PLaM7G4Llrb7zfMXCZVEXEABT8OSnd4-7w) *(YouTube -soittolista)*

Tietyt EIP:t vastaavat sovellustason standardeja (esim. standardi älysopimusformaatti), jotka esitetään nimellä [Ethereum Requests for Comment (ERC)](https://eips.ethereum.org/erc). Monet ERC:t ovat kriittisiä standardeja, joita käytetään yleisesti Ethereum-ekosysteemissä.

- [EIP-lista](http://eips.ethereum.org/erc)
- [ERC20 - Standardiliittymä tokeneille](https://eips.ethereum.org/EIPS/eip-20)
- [ERC20 - Standardiliittymä "ei-fungiibeleille" tokeneille](https://eips.ethereum.org/EIPS/eip-721)