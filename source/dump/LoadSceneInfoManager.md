# LoadSceneInfoManager

**Namespace:** ` `


## Fields

- `UInt32 m_sceneLoadSeqNum`


## Methods

- `Void OnSceneLoaded(Scene, LoadSceneMode)`

- `Void OnSceneUnloaded(Scene)`

- `LoadSceneMeta GetLoadSceneMeta(Scene)`

- `LoadSceneMeta GetLoadSceneMeta(String)`

- `WaitForSceneLoaded WaitForSceneLoaded(String)`

- `Boolean _KeepWaitingForSceneLoaded(String, UInt32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LoadSceneInfoManager : IHotfixable
{
	private Dictionary`2 m_loadSceneInfo; // 0x10
	private LocalGenericPool`1 m_metaPool; // 0x18
	private UInt32 m_sceneLoadSeqNum; // 0x20
	private static DelegateBridge __Hotfix0_OnSceneLoaded; // 0x0
	private static DelegateBridge __Hotfix0_OnSceneUnloaded; // 0x8
	private static DelegateBridge __Hotfix0_GetLoadSceneMeta; // 0x10
	private static DelegateBridge __Hotfix1_GetLoadSceneMeta; // 0x18
	private static DelegateBridge __Hotfix0_WaitForSceneLoaded; // 0x20
	private static DelegateBridge __Hotfix0__KeepWaitingForSceneLoaded; // 0x28
	private static DelegateBridge __Hotfix0__GetSceneKey; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2f30c00 VA: 0x7595548c00
	public Void OnSceneLoaded(Scene scene, LoadSceneMode loadMode) { }
	// RVA: 0x2f30e1c VA: 0x7595548e1c
	public Void OnSceneUnloaded(Scene scene) { }
	// RVA: 0x2f30f60 VA: 0x7595548f60
	public LoadSceneMeta GetLoadSceneMeta(Scene scene) { }
	// RVA: 0x2f31088 VA: 0x7595549088
	public LoadSceneMeta GetLoadSceneMeta(String sceneName) { }
	// RVA: 0x2f311a4 VA: 0x75955491a4
	public WaitForSceneLoaded WaitForSceneLoaded(String sceneName) { }
	// RVA: 0x2f312f0 VA: 0x75955492f0
	private Boolean _KeepWaitingForSceneLoaded(String sceneName, UInt32 lastSeqNum) { }
	// RVA: 0x2f30d74 VA: 0x7595548d74
	private static String _GetSceneKey(Scene scene) { }
	// RVA: 0x2f313b0 VA: 0x75955493b0
	public Void .ctor() { }
}
```