# SVTProject
This is the project about the formal verification of SCION path lookup protocol for the exam of Security Verification and Testing (SVT). 

The folder contains the following files:
  - **multichannelVerifiedSuccessfully.pv**: actual script that correctly verifies the protocol but with the usage of multiple channels between the parties.
  - **singleChannelBeforeBreaks.pv**: the protocol script with the usage of single channels (full-duplex) between the parties that is not correctly proving all the queries. The uncommented code is the one till the last step before the verification fails. The commented part complements the definition of the model.  
