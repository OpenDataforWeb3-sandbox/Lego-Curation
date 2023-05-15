# Lego-Curation
- We expect to be able to access the lego both from the website and from Github. 
- Each lego should have a title and short description on the website. On Github, we could also include the name of the project referenced. 
- Operationally making lego images, pypi packages available and explaining the algorithms the lego implements. 
- Including the github project aupporting the lego if available. 
- Roughly the next step from the landscape and legos docs. Possible to evolve to supporting container images on public Docker or another image repository like artifactory.

## COMPOSABILITY VS COMPATIBILITY

Compatibility refers to the ability of two or more legos to work together without conflicts or issues. It means that the interfaces, data formats, and functionalities of these legos are designed in a way that allows them to interact and exchange information effectively.

Composability, on the other hand, refers to the ability to combine different legos to create new, more complex systems or applications. Composability is about designing protocols or systems in a modular and interoperable way, so that they can be easily combined or composed to achieve desired functionalities or objectives.

In the context of blockchain and decentralized applications, composability is a highly valued characteristic. It allows developers to build on top of existing protocols and smart contracts, leveraging their functionalities and combining them with other protocols or components to create innovative and complex systems.

While compatibility is a prerequisite for composability (protocols need to be compatible to be effectively composed), composability goes beyond compatibility by emphasizing the modularity, interoperability, and ability to create new functionalities through the combination of different protocols or components.

In my course of evaluation, i discovered most of the legos individually did not possess multifactor authentication which is the ability to evaluate more than one factor when evaluating sybil operations. 

Please see my submission here: [ChatGPT vs AntiSybil Legos](https://github.com/AdedamolaXL/ChatGPT-vs-AntiSybil-Legos)

Here is a suitable table evaluating this Legos over various indicators

![chart(2)](https://github.com/AdedamolaXL/Lego-Curation/assets/66562380/4802dfb7-7a11-4665-a936-3a71f97960cb)

Here is a list of compatible legos based on evaluation:
* Proof of Humanity: Compatible with BrightID and Upala as they all relate to identity verification and reputation systems.
* Address Correlation Lego: Can potentially be used in conjunction with other protocols that analyze address correlations or patterns, such as OnChain Footprint Lego or Flagged Activity.
* Levenshtein Distance: Can be used with protocols that involve username or address comparison, such as BrightID or OnChain History.
* Money Mixers: Can potentially be integrated with protocols that track or analyze transactions, such as OnChain History or Flagged Activity.

Here is a list of composable legos based on evaluation:
* Idena and Proof of Humanity: Both protocols focus on establishing and verifying the uniqueness and personhood of individuals on the blockchain.
* UBI and Proof of Humanity: UBI can utilize the verified identities from Proof of Humanity to ensure that the streamed cash is distributed to real individuals.
* Address Correlation Lego and OnChain Footprint Lego: These legos can be used together to analyze the correlation between different addresses and track the ownership and transfer of funds within a network.
* Script Call to API and Funding Wallet: Script Call to API can be used to retrieve data from external APIs and feed it into the Funding Wallet protocol to track and validate funding transactions.
* POAP and Social Presence: Social Presence can be used to analyze and verify the social media presence of individuals, which can enhance the validation process for the ownership and transfer of POAP tokens.
* High Frequency Trading and Money Mixers: These protocols can be used in conjunction to detect suspicious trading patterns and identify potential money laundering activities in the blockchain network.


# Reference 
- Created from proposal https://forum.opendatacommunity.org/t/sandbox-team-proposal/30/6
- Discord channel https://discord.com/channels/1037443230993743902/1087749418545061918
