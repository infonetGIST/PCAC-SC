# PCAC-SC
Patient-Centric access control smart contract Solidity code

CODE INFORMATION

Codes written by Mohamed Yaseen.J

Reference paper title: Mohamed Yaseen Jabarulla and Heung-No Lee, "Blockchain-Based Distributed Patient-Centric Image Management System"

Last version: Dec. 12, 2019.

FUNCTIONS

1.create_contract(): this function is created and executed only by a patient to issue corresponding roles for Image requestors (IRs) and related information for accessing medical images.

2.requesting_access(): this function is executed by IRs to obtain access permission from the patient. 

3.approve_IRs(): this function can only be executed by the patient to approve the IRs.

4.trace_authorization(): this function executed by IRs and patients to track the history of approved or disapproved requestors in the blockchain.

5.remove_IRs(): this function takes the approved IRs blockchain address as input and removes IRs from SC upon successful execution of a function by the patient.

Key links for Experimental Setup:

1. Remix IDE (Environment: Injected Web3) - https://remix.ethereum.org/
2. Rinkeby test network using metamask for chrome - https://metamask.io/download.html
3. initialize IPFS using go-ipfs - https://github.com/ipfs/go-ipfs

Key links used for Evaluation:

1. Anonymized free medical DICOM images - https://www.dicomlibrary.com/
2. PostDICOM cloud PACS - https://www.postdicom.com/
