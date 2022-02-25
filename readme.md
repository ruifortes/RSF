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

# Refs

- [Local IPFS Node](https://ipfs.io/ipfs/Qma7Bc7LkmPHqorsxbmjNS6rVoQx5kwCGXapfHgpsT7Z24?filename=screencapture-github-microsoft-vscode-issues-12453-2022-02-24-19_52_32.png)
- [HTML Local Copy](http://bafybeifoitngyl7jezn536mipj4rzzjy2wyvsnoffwfofioq3r7pmaglle.ipfs.localhost:48084/?filename=12453)
- [Host a Git-style repo | IPFS Docs](http://docs.ipfs.io.ipns.localhost:48084/how-to/host-git-style-repo/)
- [GFS (global file system)](https://ipfs.io/ipfs/Qma7Bc7LkmPHqorsxbmjNS6rVoQx5kwCGXapfHgpsT7Z24?filename=screencapture-github-microsoft-vscode-issues-12453-2022-02-24-19_52_32.png)
- [Add sorting to Open Editors list · Issue #12453 · microsoft/vscode](https://github.com/microsoft/vscode/issues/12453)
- [How to Build Ethereum Dapp (Decentralized Application Development Tutorial) - YouTube](https://www.youtube.com/watch?v=3681ZYbDSSk&t=1s)
