Adds a Simple wrapper that runs Unity's Debug.Log only when only certain Unity Custom Scripting Define Symbols is included
Compiled into dll

--- 
Usage Instructions
  1. Copy [UnityDebugLogWrapper.dll] into plugin folder
  2. Use instead of Debug.Log(), use Custom.Log() in your code
  3. Applicable only when the following Scripting Define Symbols is configured
     1. "DEVELOPMENT_BUILD"
     2. "UNITY_EDITOR"
     3. "UNITY_ASSERTIONS"
