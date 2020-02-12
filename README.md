# atp-mac-ws1
Deploying MS Defender ATP macOS with vmWare WorkspaceOne

If you want to distribute Microsoft Defender ATP for macOS via WorkspaceOne in an enterprise environment you need 2 plist at the end which you distribute via the custom settings in WS1 and which are located in the /Libray/Managed Preferences/. 
On the one hand you need the onboarding info, which contains the license for Defender ATP, on the other hand you need the configuration settings. In addition you have to define the system extension policy, kernel extension policy and the privacy preferences.

