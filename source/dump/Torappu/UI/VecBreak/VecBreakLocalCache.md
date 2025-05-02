# VecBreakLocalCache

**Namespace:** `Torappu.UI.VecBreak`


## Methods

- `ActData _EnsureMemCacheData()`

- `ActData _EnsureActCacheData(String)`

- `DataInAct _GetDataInAct(String)`

- `Void _SaveData(ActData)`

- `Void SaveSquadCache(String, String, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakLocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__EnsureActCacheData; // 0x10
	private static DelegateBridge __Hotfix0__GetDataInAct; // 0x18
	private static DelegateBridge __Hotfix0__SaveData; // 0x20
	private static DelegateBridge __Hotfix0_LoadSquadCache; // 0x28
	private static DelegateBridge __Hotfix0_SaveSquadCache; // 0x30


	// RVA: 0x22e0510 VA: 0x75948f8510
	private Void .ctor() { }
	// RVA: 0x22e05a0 VA: 0x75948f85a0
	private ActData _EnsureMemCacheData() { }
	// RVA: 0x22e0704 VA: 0x75948f8704
	private ActData _EnsureActCacheData(String actId) { }
	// RVA: 0x22e08e4 VA: 0x75948f88e4
	private DataInAct _GetDataInAct(String actId) { }
	// RVA: 0x22e0a28 VA: 0x75948f8a28
	private Void _SaveData(ActData data) { }
	// RVA: 0x22d8fe4 VA: 0x75948f0fe4
	public List`1 LoadSquadCache(String actId, String squadId) { }
	// RVA: 0x22d83d8 VA: 0x75948f03d8
	public Void SaveSquadCache(String actId, String squadId, List`1 slotList) { }
}
```