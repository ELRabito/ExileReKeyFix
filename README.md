# ExileReKeyFix

Fixes a Exile bug/design flaw which took your poptabs while aborting the PIN change at the Vehicle Customs Trader. Now the poptabs only get deducted if the PIN change is successful.

##>Installation

1. Add/replace the files in your missionfile/server pbo via CfgExileCustomCode of your mission config.cpp.

2. Add this to your CfgNetworkMessages.
    
        class rekeyVehicleRequest
        {
	          module = "object_vehicle";
	          parameters[] = {"STRING","STRING","SCALAR"};
        };
3. Done!
