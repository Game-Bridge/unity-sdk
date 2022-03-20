# unity-sdk

1. Set up our template
Copy the WebGLTemplates directory from the downloaded zip into your Unity game's Assets directory.

Now, select the template in Player Settings > WebGL > Resolution and Presentation:

GameBridge Template in Player Settings
![unity template](https://sdk.poki.com/img/unity-poki-template.png)

index.html

The contents of index.html are rewritten by our upload system. Custom html must be wrapped with <!-- GameBridge include body --> and <!-- GameBridge include end --> Replace 'body' with 'head' to place the wrapped html in the resulting tag.

2. Initialize the SDK
Copy the GameBridgeUnitySDK.cs file and the Plugins folder into your project's Assets folder so you can access the GameBridgeSDK from your code.

Now, make sure you initialize the SDK as early as possible in your application by calling GameBridgeUnitySDK.Instance.init();.
