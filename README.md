V1.01 (Needs Testing)

No Test Macro for this

You need triggernometry for this Version 1.1.4.1 Or higher: https://github.com/paissaheavyindustries/Triggernometry

Please make sure that Default party sort is enabled in FF (Tank, Healer, DPS)
![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/PartySortInGame.png?raw=true)

In triggernometry it is configured under "Options > Edit Configuration > Final Fantasy XIV" that player list set to `Custom Order`. Then Go through and make sure that your `In Game Role Sort Settings` and your Triggernometry Player List Custom Order match 1 to 1.  ***If they do not then the auto markers will mark the wrong players***


 ![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/PartyListTriggerStep1.png?raw=true)
 
 ![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/PartyListTriggerStep2.png?raw=true)
 
 ![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/PartyListTriggerStep3.png?raw=true)
 

The following Macros will need to be created and added to the F1-F9 keys

F1: `/mk attack <1>`

F2: `/mk attack <2>`

F3: `/mk attack <3>`

F4: `/mk attack <4>`

F5: `/mk attack <5>`

F6: `/mk attack <6>`

F7: `/mk attack <7>`

F8: `/mk attack <8>`



F9:
````
/merror off
/mk clear <1>
/mk clear <2>
/mk clear <3>
/mk clear <4>
/mk clear <5>
/mk clear <6>
/mk clear <7>
/mk clear <8>
````
It will look like this.  It does not have to be visible to work but it does have to exist on the class you are playing as. 
![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/InGameHotbar.png?raw=true)
