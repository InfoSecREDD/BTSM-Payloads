# BTSM Payloads
### BTSM (Behind-the-Scenes Manipulation) Payloads PoC
 (It's a "play" on BDSM; Because it feels so wrong, and probably shouldn't be shared with the world.)


This Proof of Concept requires Microsoft Windows PowerShell 7+.

### What does it do?
As of the time of this release, I will leave it up to your imagination. Once this PoC has been around for awhile, this will be filled in accurately.

### Why this only works on PowerShell 7+?
The transition from PowerShell version 5 to version 7 marked a significant improvement in the language's capabilities. In version 5, handling arrays and complex byte assembly posed challenges, limiting its ability to execute payloads like InvisInk effectively. However, with the upgrade to PowerShell 7, these limitations were addressed. The new version enabled the integration of complex arrays seamlessly, allowing for the execution of [InvisInk](https://github.com/InfoSecREDD/InvisInk-Encoder) payloads without revealing the underlying code while also skipping the decoy code. 

[InvisInk Encoder](https://github.com/InfoSecREDD/InvisInk-Encoder) - By InfoSecREDD
