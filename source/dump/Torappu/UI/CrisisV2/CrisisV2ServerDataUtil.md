# CrisisV2ServerDataUtil

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2DataFromServer m_dataFromServer`


## Methods

- `Boolean RequestCrisisV2DataIfNeeded()`

- `ServerDataValidStatus GetServerDataValidStatus()`

- `CrisisV2CacheServerData GetCacheData()`

- `Boolean CheckIfDataValid()`

- `Boolean _RequestCrisisDataIfNeeded()`

- `Void <_RequestCrisisDataIfNeeded>b__6_0(CrisisV2GetInfoResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2ServerDataUtil : Singleton`1
{
	private CrisisV2DataFromServer m_dataFromServer; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RequestCrisisV2DataIfNeeded; // 0x8
	private static DelegateBridge __Hotfix0_GetServerDataValidStatus; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheData; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfDataValid; // 0x20
	private static DelegateBridge __Hotfix0__RequestCrisisDataIfNeeded; // 0x28


	// RVA: 0x2bc5980 VA: 0x75951dd980
	private Void .ctor() { }
	// RVA: 0x2bc5a4c VA: 0x75951dda4c
	public Boolean RequestCrisisV2DataIfNeeded() { }
	// RVA: 0x2bc5d5c VA: 0x75951ddd5c
	public ServerDataValidStatus GetServerDataValidStatus() { }
	// RVA: 0x2bc41e8 VA: 0x75951dc1e8
	public CrisisV2CacheServerData GetCacheData() { }
	// RVA: 0x2bc5dec VA: 0x75951dddec
	public Boolean CheckIfDataValid() { }
	// RVA: 0x2bc5ab4 VA: 0x75951ddab4
	private Boolean _RequestCrisisDataIfNeeded() { }
	// RVA: 0x2bc5e74 VA: 0x75951dde74
	private Void <_RequestCrisisDataIfNeeded>b__6_0(CrisisV2GetInfoResponse response) { }
}
```