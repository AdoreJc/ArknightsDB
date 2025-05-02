# SandboxV2LocalCache

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Methods

- `CacheData _EnsureMemCacheData()`

- `DataInTopic _EnsureTopicData(CacheData, String)`

- `DataInSingleGame _EnsureSingleGameData(CacheData, String, Int64)`

- `Void _SaveData(CacheData)`

- `DataInTopic _GetDataInTopic(String)`

- `SandboxV2SquadFocusCacheModel LoadSquadFocusCacheModel(String, Int64)`

- `Void SaveSquadFocusCacheModel(String, Int64, SandboxV2SquadFocusCacheModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__EnsureTopicData; // 0x10
	private static DelegateBridge __Hotfix0__EnsureSingleGameData; // 0x18
	private static DelegateBridge __Hotfix0__SaveData; // 0x20
	private static DelegateBridge __Hotfix0__GetDataInTopic; // 0x28
	private static DelegateBridge __Hotfix0_LoadSquadFocusCacheModel; // 0x30
	private static DelegateBridge __Hotfix0_SaveSquadFocusCacheModel; // 0x38


	// RVA: 0x2605404 VA: 0x7594c1d404
	private Void .ctor() { }
	// RVA: 0x2605494 VA: 0x7594c1d494
	private CacheData _EnsureMemCacheData() { }
	// RVA: 0x26055f8 VA: 0x7594c1d5f8
	private DataInTopic _EnsureTopicData(CacheData cacheData, String topicId) { }
	// RVA: 0x2605818 VA: 0x7594c1d818
	private DataInSingleGame _EnsureSingleGameData(CacheData cacheData, String topicId, Int64 timestamp) { }
	// RVA: 0x26059ec VA: 0x7594c1d9ec
	private Void _SaveData(CacheData data) { }
	// RVA: 0x2605a98 VA: 0x7594c1da98
	private DataInTopic _GetDataInTopic(String topicId) { }
	// RVA: 0x2605be4 VA: 0x7594c1dbe4
	public SandboxV2SquadFocusCacheModel LoadSquadFocusCacheModel(String topicId, Int64 timestamp) { }
	// RVA: 0x2605c94 VA: 0x7594c1dc94
	public Void SaveSquadFocusCacheModel(String topicId, Int64 timestamp, SandboxV2SquadFocusCacheModel focusCacheModel) { }
}
```