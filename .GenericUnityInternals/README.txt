Projects in this solution contain calls to Unity internal methods. They are highlighted as errors but upon building the project, those errors will be ignored.
After building a project, the DLL file will be copied over to the parent folder of GenericUnityInternals~, so you will be able to use the updated DLL in Unity after building it.
Projects a built with help of OpenSesame. Check it out https://github.com/mob-sakai/OpenSesame

If references are missing in the Visual Studio solution, here is how to add them:
In the solution explorer panel, right click on References, then add a reference.
For the Unity references, grab them from their install location (should be C:/Program Files/Unity/Hub/Editor/<UNITY_VERSION>/Editor/Data/Managed/UnityEngine)
For the other references (SolidUtilities, GenericUnityObject), grab them from <YOUR_PROJECT_FOLDER>/Library/ScriptAssemblies/