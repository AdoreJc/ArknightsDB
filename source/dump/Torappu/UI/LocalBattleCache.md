# LocalBattleCache

**Namespace:** `Torappu.UI`


## Fields

- `MemCache m_cache`


## Methods

- `MemCache _EnsureMemCache()`

- `Void UILocalCache_SaveStageCache(String, Dictionary`2)`

- `Void UILocalCache_SaveZoneCache(String, Dictionary`2)`

- `Void RecordLastBattle(RecentBattleRecord)`

- `RecentBattleCache _EnsureRecentBattleCache()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class LocalBattleCache : Singleton`1
{
	private static readonly ListSet`1 TYPES_TO_RECORD; // 0x0
	private MemCache m_cache; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0__EnsureMemCache; // 0x10
	private static DelegateBridge __Hotfix0_UILocalCache_GetStageCache; // 0x18
	private static DelegateBridge __Hotfix0_UILocalCache_SaveStageCache; // 0x20
	private static DelegateBridge __Hotfix0_UILocalCache_GetZoneCache; // 0x28
	private static DelegateBridge __Hotfix0_UILocalCache_SaveZoneCache; // 0x30
	private static DelegateBridge __Hotfix0_GetRecentBattleRecords; // 0x38
	private static DelegateBridge __Hotfix0_RecordLastBattle; // 0x40
	private static DelegateBridge __Hotfix0__EnsureRecentBattleCache; // 0x48


	// RVA: 0x2270b38 VA: 0x7594888b38
	private Void .ctor() { }
	// RVA: 0x2270bd8 VA: 0x7594888bd8
	private MemCache _EnsureMemCache() { }
	// RVA: 0x2270e84 VA: 0x7594888e84
	public Dictionary`2 UILocalCache_GetStageCache(String key) { }
	// RVA: 0x2270fb4 VA: 0x7594888fb4
	public Void UILocalCache_SaveStageCache(String key, Dictionary`2 localCache) { }
	// RVA: 0x2271084 VA: 0x7594889084
	public Dictionary`2 UILocalCache_GetZoneCache(String key) { }
	// RVA: 0x22711b4 VA: 0x75948891b4
	public Void UILocalCache_SaveZoneCache(String key, Dictionary`2 localCache) { }
	// RVA: 0x2271284 VA: 0x7594889284
	public List`1 GetRecentBattleRecords() { }
	// RVA: 0x22714e8 VA: 0x75948894e8
	public Void RecordLastBattle(RecentBattleRecord record) { }
	// RVA: 0x227130c VA: 0x759488930c
	private RecentBattleCache _EnsureRecentBattleCache() { }
	// RVA: 0x2271a50 VA: 0x7594889a50
	private static Void .cctor() { }
}
```