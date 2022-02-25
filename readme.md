---
title: "A"
data: 2022-02-25 02:19:34
xxx: http://bafybeigxdvsjzdktpfi6ni67w4nxtf6babux6ms6z2fdf4xcuvvzscs6si.ipfs.localhost:48084/?filename=cfP40y6E_fi1p4HwiKsWay98-RbxwgljmRRj-vtJenJ1TnoyqEqUumIwqL7-v5GUWGzl3sjc33qT25-Lk6EIGFU9FAnFqkBtNmieCmqwkNr5xKIrHvSlhaJTlucqSLVCvKUPtvb9D3DnhOND9eQurUHwIf_1YKmIymNP6gAbRlPN7czcjkU5BPHzpNETI_hwVHwBwba-HqjA9K5CnxXyGBWnAQ_JN9PgLIyO0VfS9P9ZaANpG3Apbt9L_BSSYjvxexkNbVYZG9xeCs_CgyARFMPnO3UNXfP7nrvMcc6YkHaNn8RX7c05bTg9zXABcSS068unAASWkUqystbshYSHl_5cV6-1SW9KChICmRfEp2dcy-J7IDDhHHO8fCrdVMAiY1r6PPKMOL-IVMLpQYs8m_aZjV1meKloG1CVR9n7SKN7jkAa73x7OE2ui9JGwGs5R_-e5yyP0e7z7X_cDZPdWZl1eHiEwk8z4hRIyv1jXqIFgFqxUlGC_4L0VplGJlW0terUKMmloSDcfvtDRzoIxoy69-xEFvCtmzWKl93sDpYzo138OloDV3dLK3DUW_3KHvkzXGH-FFFIc_sEXrjceF8XfunoTgILl1XkoDa-ElIpIdtQNMXQIrQaKvBLluXZl7KIhAY8ghZ4m2BSkgZP_9KWAoH-2YZWtxouuvuCgbIDA6bPZsz5EHDuYaO2JOSS5CEgRTt9AY8w3FF4XthMRKxz7A%3Dw1673-h941-no


---



# The Challenge!
  create a "crypto-OS" starting from the simplest TXT encoding

# Rules
- parse scopes
- define non-spaced, non-word, main text separator regex, ....whatever
- get attached non-spaced text
- normalize proof-of-work (from_TXT_to_PK method that could accept 'empty string' as well as very large TXT data)
- Define TXT_DATA. Raw ascii ?? smaller?
- 
- if "TXT -> first == '@'"{#todo '\'' and "'" precedence} it creates a wallet with:
    - a public key that "parses" to 'RSF' string.
- the ipfs-anchor would manage a distributed MFS (mutable file system)
- the ipfs-cluster would assume some crypto-contracts {interacting with #hyperledger-aries}

- a scope without any '@' would be assumed to be in a local MFS. This could be a configurable default

- Public MTF would not involve any kind of restriction besides the information that "public folder named @RSF" "should" (or is assumed to) be signed by a related private-key and/or encrypted but it.

- the "Global View" of an MFS_DAPP_GLOBAL would contain all the signed (eventually not encrypted at all) in order to get some kind of monetization, "social value", incentive structure, etc out of it.

- the "Global MFS" would be an append-only DL. timestamp data would be a given.
    - [File systems | IPFS Docs](http://docs.ipfs.io.ipns.localhost:48084/concepts/file-systems/#unix-file-system-unixfs)

    - [IPNS | IPFS Docs](http://docs.ipfs.io.ipns.localhost:48084/concepts/ipns/)

    - related to [this]('@RSF/#XUI\_XUI.md# The @XUI project')
    {would there be a root dir (without encryption, the "@"?)}
    
- in this case I'm using "@RSF -> create_ipfs_node(<--my private key-->)" wich public key is "


# Tasks

# Questions @{50€ informal donation}
- Should some kind of crypto layer network infra-structure be financed by "public funds"?
- Any effort being made regarding public funding in state-of-the-art cryptography R&D?

# Good Online Resources {50€}

# Tools
- markdown_online_preview:
    -   [hugodias/facebook-post-preview: Preview how a link will be rendered on facebook](https://github.com/hugodias/facebook-post-preview)
- yaml_online_preview


# @proposal




# Definitios

- Scope:
    types
    - random: using random PK curly-brackets with no "@foldername" right before
    - scoped: folder "@RSF" would enforce 

    digitally signed RANDOM(or not) ipfs hashes (since global MTF is a tree)
    
- "paths and Ledgers types"
    "@": mainly cryptographic material
    "$": high-volume storage (distributed, local or "centralized")
    "#": these would be root level GFS folder names

- "auth-path": "nested hierarchy of signature requirements "forced" by the "GLOBAL-MFS"

- "computation layer": #dapp_dsl_Ethereum_crypto@some_output_key
- "Chain-code": #dapp_dsl_crypto_hyperledger
- "markdown normalization":...
- "

============================================================================

- inside/after a "#" a nested folder "@rsf" would "enforce" digitally signed data by defining enforced 'Task' to convert to full PK length
- should TXT(or some other 'encode') have even smaller table then ascii? This could solve some
  cross-platform problems like Windows vs Linux 'Case Sensitiveness'
- "#" would be a very high speed transactional append only Distributed Ledger
* it would be impossible to visualizing unfiltered data in a "# Some topic folder" 'transaction log'
- "$" would relate to FileCoin token  

# todo 2022_02
- [-] Mercury
- [+] Venus
- [x] Earth (Orbit/Moon)
- [x] Mars
- [ ] [Host a Git-style repo | IPFS Docs](http://docs.ipfs.io.ipns.localhost:48084/how-to/host-git-style-repo/)

# Refs

- [Local IPFS Node](https://ipfs.io/ipfs/Qma7Bc7LkmPHqorsxbmjNS6rVoQx5kwCGXapfHgpsT7Z24?filename=screencapture-github-microsoft-vscode-issues-12453-2022-02-24-19_52_32.png)
- [HTML Local Copy](http://bafybeifoitngyl7jezn536mipj4rzzjy2wyvsnoffwfofioq3r7pmaglle.ipfs.localhost:48084/?filename=12453)
- [Host a Git-style repo | IPFS Docs](http://docs.ipfs.io.ipns.localhost:48084/how-to/host-git-style-repo/)
- [GFS (global file system)](https://ipfs.io/ipfs/Qma7Bc7LkmPHqorsxbmjNS6rVoQx5kwCGXapfHgpsT7Z24?filename=screencapture-github-microsoft-vscode-issues-12453-2022-02-24-19_52_32.png)
- [Add sorting to Open Editors list · Issue #12453 · microsoft/vscode](https://github.com/microsoft/vscode/issues/12453)
- [How to Build Ethereum Dapp (Decentralized Application Development Tutorial) - YouTube](https://www.youtube.com/watch?v=3681ZYbDSSk&t=1s)

![](https://lh3.googleusercontent.com/U4EWYjG6m_aM6ccUYUgwwQljrO_T4hbwy3bmoDJPnafpdMWyS0Rc0Uy4Jrw6CjBR1t5cDPaLACGd2glOs7XQUB2jkZt-4h1jnjtrWgh2iKBSXrRLh1LEFkVMQaB4DKjYvXksnc9aJXXett8cvSFT3gz4MdAmqZFpsxWUb_zFEr-vL_87oF_Q6EOhkeHzLCGiplblISclaODp-qGFmAl8IHGGEW4g66lqQjzI6VuzQTCU-G_dMMW05dSbzEh5DEm4IAHfVPriKGcyu1Ia-dSgny1IHNBITH5ATo7lDBZnsc0dZyOmN8JHJ4nALcvG16AKnrysDC-dyZN1RpRthsHQv4FP6McxDI_mfxBDe4QKDlsR6IGMLi0GNBvT4J3ycH2FOPveR8fdeV3HvNuQgw-OMF5pyXiKJdoVvgm6ormovwOS_rq2VQmnOPoje1JUYVkj1w366X2xzUPQe0AXHNsrYgDmgIQiGFxDkJdhIq4IvWlbzXWOSX5n99oTgaE72H3CozVLJMhEK7yz_qpGHc_0C7lLczDj8cX8RjKkLZceGwX6sonXqmlQIAzixMTzaMT8WJJ5S5HA1rg6Jv8VrUPpfcXTV-cLcVCsPn9WDbvrMw0MuiZNXfBzNEHp_i0qa91Btpnon5_O1tNjupoLvxka_X8TOGikBYzz0HU-iSf19AqbvpwJ3pyO2_HZK446RkTV70TS4fJ5xZ4IcaHgnIkYwNixRg=w1673-h941-no?authuser=0)