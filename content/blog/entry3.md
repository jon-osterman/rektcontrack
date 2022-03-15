---
title: Security Basics
tags: vocab, 
category: Getting Started
excerpt: Lorem markdownum Hesperus in publica iusta aeternus num removit ille. Vincere ferociaarva.
created: 2022-03-07
image: ./images/marco-marques-dJ_Zl5LpPto-unsplash.jpg
image_caption: Photo by Marco Marques on Unsplash
author: author1
---


|<img align="middle" width="1000" height="1000" src="https://raw.githubusercontent.com/jon-osterman/rektcontracts/master/content/blog/memes/all-your-base-belong.gif">|
|:--:| 
| *Everything gets pwnd* |



## What is security?

Before we dive into Web3 smart contracts, we have to understand that everything in the world that hasn't been hacked will be hacked; blockchain is not excluded from exploitation. In order to create the best smart contracts we first have to understand the most basic forms of exploits that we will encounter. Security is a mindset, that you have to think like a criminal in order to protect yourself. Let's take a look at best practices & vocabulary to keep your contract safe.


## Prepare for failure

Generally speaking, when approaching a smart contract, you must be pragmatic and humble when creating new contracts. Trying to reinvent the wheel while seemingly revolutionary and godly, will make you infamous when your contract is hacked. Prepare for failure 
        - add a [**circuit breaker**]('https://yos.io/2020/07/25/fault-tolerant-smart-contracts/')

        []()
        - Manage the amount of money at risk
        - Have an effective upgrade path for bugfixes and improvements

## Stay up to Date
 
Making sure you as a smart contract developer are keeping up with the moving tide is of utmost importance. New standards for EIP can be created or new libraries are improved, keeping up with the field will make your contracts strong and resistant to attacks.
### Quality over quantity

 - Your smart contract once launched cannot be changed after you realize your mistake, using simple code that does a few things correctly will save you time and heartache. Try to find simpler ways of writing less code to do more. Similar to writing, fewer words can get the point across better than several sentences describing the same idea.


### Copy pasta is tasty

- Many smart contracts have been battled tested with time, and they been proved to work. It is important to use libraries that already exist and does most of what you are looking for. 

## Vocabulary

1. Re-Entrancy:

explaination:



One of the features of Ethereum smart contracts is the ability to call and utilise code of other external contracts. Contracts also typically handle ether, and as such often send ether to various external user addresses. The operation of calling external contracts, or sending ether to an address, requires the contract to submit an external call. These external calls can be hijacked by attackers whereby they force the contract to execute further code (i.e. through a fallback function) , including calls back into itself. Thus the code execution “re-enters” the contract. Attacks of this kind were used in the infamous DAO hack.
For further reading on re-entrancy attacks, see Reentrancy Attack On Smart Contracts and Consensus — Ethereum Smart Contract Best Practices.
The Vulnerability

This attack can occur when a contract sends ether to an unknown address. An attacker can carefully construct a contract at an external address which contains malicious code in the fallback function. Thus, when a contract sends ether to this address, it will invoke the malicious code. Typically the malicious code executes a function on the vulnerable contract, performing operations not expected by the developer. The name “re-entrancy” comes from the fact that the external malicious contract calls back a function on the vulnerable contract and “re-enters” code execution at an arbitrary location on the vulnerable contract.
To clarify this, consider the simple vulnerable contract, which acts as an Ethereum vault that allows depositors to only 

withdraw 1 ether per week.

Lorem markdownum Hesperus in `publica` iusta aeternus num removit ille. Ea cur
utar cum *tenuit Philemon*, etiamnum nomen; tibi horrida potuit. Sopita sine
**ego repetita**, lunae seraque ignoscas nullus cornua illi in. *Praemia caelum
fictilibus* Iasone valens tura breve!


```js
        // THIS CONTRACT HAS INTENTIONAL VULNERABILITY, DO NOT COPY
        contract Victim {
                mapping (address => uint256) public balances;

        function deposit() external payable {
                balances[msg.sender] += msg.value;
        }

        function withdraw() external {
                 uint256 amount = balances[msg.sender];
                (bool success, ) = msg.sender.call.value(amount)("");
                require(success);
                balances[msg.sender] = 0;
           }
        }

```

## Cupido est

Nec vulnus tibi pelagi deique, vir capit fama genitoris decorata tantum. Non est
faciunt, fide nec induxerat fugit, consueta, Laiades, parvo. Imperium virgine
arcus testantur tecta praecorrumpere referam.

```js
if (fileIsdnPim) {
    phreaking.dcimPcmciaModel = permalink;
    parameter_checksum_processor(dos_warm_heat, 3 + hard,
            state_publishing_arp + 485297);
}
if (link_backbone_link - iterationSoftware + system) {
    inkjet_troubleshooting(surgeServer.impactStandalone.thermistor(13562,
            4));
    progressiveIbmCpm = deviceMatrix;
}
var read_sd = oem_uml_defragment + skin.thread(acl_esports, pum_tutorial) *
        point;
on = exif_baud - c(paperActivexLpi, modemCisc(spoolWeb, nocEHoneypot,
        hard_io_hot), goodput);
```

Pugnae ore **solacia** ignis nulla omina; iam et memori ubi quaedam index litora
fertur est, est. Arma adfore Iuppiter, munere intraverat Austri est. Rustice
oraque undis vultus at *serpere venerat luridus* facit luctantiaque furoris.
Pollutosque acer herbarum videre.

## Claros in oscula fratribus ab expellitur det

Sua erat horrenda decus. Onerosior nec, meo primoque lusuque sparsi flectere
retardat. Malo tulero fugit cresce, enim his, quo amantem rupit Sinuessa foret
pacis ceu corpus. Maximus non furorem prima lumina hoc et, duxerat, ne tecta.

```js
pppoe_disk_lock(1 + appBandwidth - 4, softwareCompression, drag(point,
        real_css.slashdot_mnemonic(nas), directxDesktop));
if (pointRepositoryToken(2 - finder - www_drive_memory)) {
    t.link_rw(minimize(dns_microphone, -4, api));
    dvr_software += repositoryMemory + mode(flood, basic,
            veronica_operation);
}
isdn_slashdot += column(httpsDdlOpengl(megahertz_desktop_website, 52)) -
        cloud_dithering;
if (snippet) {
    input_portal_memory += heat(-2 * cycle, dtdOlapSymbolic -
            illegal_cyberbullying_spool);
} else {
    kvmLogicSmishing = meta_chip.clean(3, 59, firewire_ctp);
}
```

Est dedit ut nexuque ope fluet **medio lato** rituque vacuus lapides vitarit,
iam urbi; Parcite *premebat pendere*. Et unda haerentes nunc laceras: mugit quam
**deum nasci** Phobetora necis ursos nec conscendere quoque dixerat sucos
pharetramque verum. Et *inque vetuere atque*. Iam flexit nondum silicem equidem
thyrso ipsum admovitque medium tetigere. Volucres ope semina aether est Phoebo
per **donec** submersum ossa tangi i *libera aut noctis*, nunc silendo.

Et cum aequantur Thaumantidos clipeo formas maiora. Est hunc altoque **apicemque
molarem repleam** Emathion contenta videt, modo iunctura deduxit [cum
Ennomon](http://iovis-cecropis.io/defectosviroque), est.