# SiracusaLocalCache

**Namespace:** `Torappu.UI.SiracusaMap`


## Methods

- `ActData _EnsureMemCacheData()`

- `ActData _EnsureActCacheData(String)`

- `DataInAct _GetDataInAct(String)`

- `Void _SaveData(ActData)`

- `Boolean GetIsPlayerEntryGroupFolded(String)`

- `Void SetIsPlayerEntryGroupFolded(String, Boolean)`

- `Boolean TryGetLastBigMapPosition(String, out)`

- `Void SaveLastBigMapPosition(String, Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaLocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__EnsureActCacheData; // 0x10
	private static DelegateBridge __Hotfix0__GetDataInAct; // 0x18
	private static DelegateBridge __Hotfix0__SaveData; // 0x20
	private static DelegateBridge __Hotfix0_GetIsPlayerEntryGroupFolded; // 0x28
	private static DelegateBridge __Hotfix0_SetIsPlayerEntryGroupFolded; // 0x30
	private static DelegateBridge __Hotfix0_TryGetLastBigMapPosition; // 0x38
	private static DelegateBridge __Hotfix0_SaveLastBigMapPosition; // 0x40


	// RVA: 0x23ff5f0 VA: 0x7594a175f0
	private Void .ctor() { }
	// RVA: 0x23ff680 VA: 0x7594a17680
	private ActData _EnsureMemCacheData() { }
	// RVA: 0x23ff7e4 VA: 0x7594a177e4
	private ActData _EnsureActCacheData(String actId) { }
	// RVA: 0x23ff9c4 VA: 0x7594a179c4
	private DataInAct _GetDataInAct(String actId) { }
	// RVA: 0x23ffb08 VA: 0x7594a17b08
	private Void _SaveData(ActData data) { }
	// RVA: 0x23ffbb4 VA: 0x7594a17bb4
	public Boolean GetIsPlayerEntryGroupFolded(String actId) { }
	// RVA: 0x23ffc48 VA: 0x7594a17c48
	public Void SetIsPlayerEntryGroupFolded(String actId, Boolean isFolded) { }
	// RVA: 0x23ffd04 VA: 0x7594a17d04
	public Boolean TryGetLastBigMapPosition(String actId, out Vector2 lastPos) { }
	// RVA: 0x23ffe00 VA: 0x7594a17e00
	public Void SaveLastBigMapPosition(String actId, Vector2 lastPos) { }
}
```