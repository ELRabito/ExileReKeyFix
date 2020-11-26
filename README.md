# ExileReKeyFix

##>Installation

1. Add/replace the files in your missionfile/server pbo via CfgExileCustomCode of your mission config.cpp.

2. Add this to your CfgNetworkMessages.
    
        class rekeyVehicleRequest
        {
	          module = "object_vehicle";
	          parameters[] = {"STRING","STRING","SCALAR"};
        };
