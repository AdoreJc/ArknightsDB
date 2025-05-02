# Act42D0EffectViewModel

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Boolean isShow`

- `Int32 sequenceNum`

- `String m_actId`

- `String m_stageId`

- `String m_areaId`

- `Int32 m_energyMax`

- `Int32 m_costEnergy`

- `Act42D0AreaDifficulty m_difficulty`


## Properties

- `String stageId`

- `String areaId`

- `Int32 energyMax`

- `Int32 costEnergy`

- `Act42D0AreaDifficulty difficulty`

- `Int32 ratingIndex`


## Methods

- `String get_stageId()`

- `String get_areaId()`

- `Int32 get_energyMax()`

- `Int32 get_costEnergy()`

- `Act42D0AreaDifficulty get_difficulty()`

- `Int32 get_ratingIndex()`

- `Void LoadData(String, String)`

- `Void AddEffect(String)`

- `Void RemoveEffect(String)`

- `Void UpdateEffects(List`1)`

- `Void SaveSelectedEffect()`

- `Boolean TryHide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0EffectViewModel : IHotfixable
{
	public Boolean isShow; // 0x10
	public Int32 sequenceNum; // 0x14
	private String m_actId; // 0x18
	private List`1 m_selectedEffects; // 0x20
	private ListDict`2 m_effectBranchs; // 0x28
	private Dictionary`2 m_effects; // 0x30
	private String m_stageId; // 0x38
	private String m_areaId; // 0x40
	private Int32 m_energyMax; // 0x48
	private Int32 m_costEnergy; // 0x4c
	private List`1 m_ratingData; // 0x50
	private Act42D0AreaDifficulty m_difficulty; // 0x58
	private static DelegateBridge __Hotfix0_get_effectBranchs; // 0x0
	private static DelegateBridge __Hotfix0_get_effects; // 0x8
	private static DelegateBridge __Hotfix0_get_stageId; // 0x10
	private static DelegateBridge __Hotfix0_get_areaId; // 0x18
	private static DelegateBridge __Hotfix0_get_energyMax; // 0x20
	private static DelegateBridge __Hotfix0_get_costEnergy; // 0x28
	private static DelegateBridge __Hotfix0_get_ratingData; // 0x30
	private static DelegateBridge __Hotfix0_get_difficulty; // 0x38
	private static DelegateBridge __Hotfix0_get_ratingIndex; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge __Hotfix0_LoadSelectedEffects; // 0x50
	private static DelegateBridge __Hotfix0_AddEffect; // 0x58
	private static DelegateBridge __Hotfix0_RemoveEffect; // 0x60
	private static DelegateBridge __Hotfix0_UpdateEffects; // 0x68
	private static DelegateBridge __Hotfix0_SaveSelectedEffect; // 0x70
	private static DelegateBridge __Hotfix0__GetSelectedEffectSortList; // 0x78
	private static DelegateBridge __Hotfix0_GetEffectIdList; // 0x80
	private static DelegateBridge __Hotfix0_GetEffectRuneList; // 0x88
	private static DelegateBridge __Hotfix0_TryHide; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public ListDict`2 effectBranchs { get; }
	public Dictionary`2 effects { get; }
	public String stageId { get; }
	public String areaId { get; }
	public Int32 energyMax { get; }
	public Int32 costEnergy { get; }
	public List`1 ratingData { get; }
	public Act42D0AreaDifficulty difficulty { get; }
	public Int32 ratingIndex { get; }

	// RVA: 0x32128d8 VA: 0x759582a8d8
	public ListDict`2 get_effectBranchs() { }
	// RVA: 0x3212940 VA: 0x759582a940
	public Dictionary`2 get_effects() { }
	// RVA: 0x32129a8 VA: 0x759582a9a8
	public String get_stageId() { }
	// RVA: 0x3212a10 VA: 0x759582aa10
	public String get_areaId() { }
	// RVA: 0x3212a78 VA: 0x759582aa78
	public Int32 get_energyMax() { }
	// RVA: 0x3212ae0 VA: 0x759582aae0
	public Int32 get_costEnergy() { }
	// RVA: 0x3212b48 VA: 0x759582ab48
	public List`1 get_ratingData() { }
	// RVA: 0x3212bb0 VA: 0x759582abb0
	public Act42D0AreaDifficulty get_difficulty() { }
	// RVA: 0x3212c18 VA: 0x759582ac18
	public Int32 get_ratingIndex() { }
	// RVA: 0x3212d14 VA: 0x759582ad14
	public Void LoadData(String actId, String stageId) { }
	// RVA: 0x3213c28 VA: 0x759582bc28
	public List`1 LoadSelectedEffects() { }
	// RVA: 0x3213f20 VA: 0x759582bf20
	public Void AddEffect(String effectId) { }
	// RVA: 0x3213fe4 VA: 0x759582bfe4
	public Void RemoveEffect(String effectId) { }
	// RVA: 0x32139a0 VA: 0x759582b9a0
	public Void UpdateEffects(List`1 selectedIds) { }
	// RVA: 0x32140a4 VA: 0x759582c0a4
	public Void SaveSelectedEffect() { }
	// RVA: 0x321436c VA: 0x759582c36c
	private List`1 _GetSelectedEffectSortList() { }
	// RVA: 0x32146d0 VA: 0x759582c6d0
	public List`1 GetEffectIdList() { }
	// RVA: 0x3214880 VA: 0x759582c880
	public List`1 GetEffectRuneList() { }
	// RVA: 0x3214a30 VA: 0x759582ca30
	public Boolean TryHide() { }
	// RVA: 0x3214ab4 VA: 0x759582cab4
	public Void .ctor() { }
}
```