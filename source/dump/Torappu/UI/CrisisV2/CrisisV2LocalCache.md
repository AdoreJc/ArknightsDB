# CrisisV2LocalCache

**Namespace:** `Torappu.UI.CrisisV2`


## Methods

- `SeasonData _EnsureMemCacheData()`

- `SeasonData _EnsureSeasonCacheData(String)`

- `DataInSeason _GetDataInSeason(String)`

- `Void _SaveData(SeasonData)`

- `Void SaveSelectSlotList(String, String, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2LocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__EnsureSeasonCacheData; // 0x10
	private static DelegateBridge __Hotfix0__GetDataInSeason; // 0x18
	private static DelegateBridge __Hotfix0__SaveData; // 0x20
	private static DelegateBridge __Hotfix0_LoadSelectSlotList; // 0x28
	private static DelegateBridge __Hotfix0_SaveSelectSlotList; // 0x30


	// RVA: 0x2bc6b88 VA: 0x75951deb88
	private Void .ctor() { }
	// RVA: 0x2bc6c18 VA: 0x75951dec18
	private SeasonData _EnsureMemCacheData() { }
	// RVA: 0x2bc6d7c VA: 0x75951ded7c
	private SeasonData _EnsureSeasonCacheData(String seasonId) { }
	// RVA: 0x2bc6f5c VA: 0x75951def5c
	private DataInSeason _GetDataInSeason(String seasonId) { }
	// RVA: 0x2bc70b4 VA: 0x75951df0b4
	private Void _SaveData(SeasonData data) { }
	// RVA: 0x2bc7160 VA: 0x75951df160
	public List`1 LoadSelectSlotList(String seasonId, String mapId) { }
	// RVA: 0x2bc724c VA: 0x75951df24c
	public Void SaveSelectSlotList(String seasonId, String mapId, List`1 selectSlotList) { }
}
```