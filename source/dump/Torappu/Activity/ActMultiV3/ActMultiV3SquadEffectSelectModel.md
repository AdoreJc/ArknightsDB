# ActMultiV3SquadEffectSelectModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String m_currSelectId`

- `String m_currEquipId`

- `String m_effectEditHint`

- `String m_squadName`

- `String <actId>k__BackingField`

- `ActMultiV3MapModeType <modeType>k__BackingField`

- `Int32 <keyCount>k__BackingField`

- `Int32 <starProgress>k__BackingField`

- `Int32 <requireStarCnt>k__BackingField`


## Properties

- `String actId`

- `ActMultiV3MapModeType modeType`

- `Int32 keyCount`

- `Int32 starProgress`

- `Int32 requireStarCnt`

- `String currEquipId`

- `String currSelectId`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `ActMultiV3MapModeType get_modeType()`

- `Void set_modeType(ActMultiV3MapModeType)`

- `Int32 get_keyCount()`

- `Void set_keyCount(Int32)`

- `Int32 get_starProgress()`

- `Void set_starProgress(Int32)`

- `Int32 get_requireStarCnt()`

- `Void set_requireStarCnt(Int32)`

- `String get_currEquipId()`

- `String get_currSelectId()`

- `ActMultiV3SquadEffectModel FindSelectModel()`

- `Boolean IsAllKeyCollected()`

- `String BuildEffectEditHint()`

- `Void LoadData(String, ActMultiV3MapModeType)`

- `String _FindInitCurrSelectId()`

- `Void UpdatePlayerData()`

- `Void _UpdatePlayerData()`

- `Boolean TrySelectEffect(String)`

- `Boolean IsAllEffectUnlock()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadEffectSelectModel : IHotfixable
{
	private List`1 m_effectList; // 0x10
	private String m_currSelectId; // 0x18
	private String m_currEquipId; // 0x20
	private String m_effectEditHint; // 0x28
	private String m_squadName; // 0x30
	private String <actId>k__BackingField; // 0x38
	private ActMultiV3MapModeType <modeType>k__BackingField; // 0x40
	private Int32 <keyCount>k__BackingField; // 0x44
	private Int32 <starProgress>k__BackingField; // 0x48
	private Int32 <requireStarCnt>k__BackingField; // 0x4c
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_modeType; // 0x10
	private static DelegateBridge __Hotfix0_set_modeType; // 0x18
	private static DelegateBridge __Hotfix0_get_keyCount; // 0x20
	private static DelegateBridge __Hotfix0_set_keyCount; // 0x28
	private static DelegateBridge __Hotfix0_get_starProgress; // 0x30
	private static DelegateBridge __Hotfix0_set_starProgress; // 0x38
	private static DelegateBridge __Hotfix0_get_requireStarCnt; // 0x40
	private static DelegateBridge __Hotfix0_set_requireStarCnt; // 0x48
	private static DelegateBridge __Hotfix0_get_currEquipId; // 0x50
	private static DelegateBridge __Hotfix0_get_currSelectId; // 0x58
	private static DelegateBridge __Hotfix0_get_effectList; // 0x60
	private static DelegateBridge __Hotfix0_FindSelectModel; // 0x68
	private static DelegateBridge __Hotfix0_IsAllKeyCollected; // 0x70
	private static DelegateBridge __Hotfix0_BuildEffectEditHint; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x80
	private static DelegateBridge __Hotfix0__FindInitCurrSelectId; // 0x88
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x90
	private static DelegateBridge __Hotfix0__UpdatePlayerData; // 0x98
	private static DelegateBridge __Hotfix0_TrySelectEffect; // 0xa0
	private static DelegateBridge __Hotfix0_IsAllEffectUnlock; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public String actId { get; set; }
	public ActMultiV3MapModeType modeType { get; set; }
	public Int32 keyCount { get; set; }
	public Int32 starProgress { get; set; }
	public Int32 requireStarCnt { get; set; }
	public String currEquipId { get; }
	public String currSelectId { get; }
	public List`1 effectList { get; }

	// RVA: 0x313809c VA: 0x759575009c
	public String get_actId() { }
	// RVA: 0x3138104 VA: 0x7595750104
	private Void set_actId(String value) { }
	// RVA: 0x3138188 VA: 0x7595750188
	public ActMultiV3MapModeType get_modeType() { }
	// RVA: 0x31381f0 VA: 0x75957501f0
	private Void set_modeType(ActMultiV3MapModeType value) { }
	// RVA: 0x3137910 VA: 0x759574f910
	public Int32 get_keyCount() { }
	// RVA: 0x313826c VA: 0x759575026c
	private Void set_keyCount(Int32 value) { }
	// RVA: 0x31382e8 VA: 0x75957502e8
	public Int32 get_starProgress() { }
	// RVA: 0x3138350 VA: 0x7595750350
	private Void set_starProgress(Int32 value) { }
	// RVA: 0x31383cc VA: 0x75957503cc
	public Int32 get_requireStarCnt() { }
	// RVA: 0x3138434 VA: 0x7595750434
	private Void set_requireStarCnt(Int32 value) { }
	// RVA: 0x3137840 VA: 0x759574f840
	public String get_currEquipId() { }
	// RVA: 0x3137770 VA: 0x759574f770
	public String get_currSelectId() { }
	// RVA: 0x31384b0 VA: 0x75957504b0
	public List`1 get_effectList() { }
	// RVA: 0x3138518 VA: 0x7595750518
	public ActMultiV3SquadEffectModel FindSelectModel() { }
	// RVA: 0x3138638 VA: 0x7595750638
	public Boolean IsAllKeyCollected() { }
	// RVA: 0x313875c VA: 0x759575075c
	public String BuildEffectEditHint() { }
	// RVA: 0x31387fc VA: 0x75957507fc
	public Void LoadData(String actId, ActMultiV3MapModeType modeType) { }
	// RVA: 0x3138f90 VA: 0x7595750f90
	private String _FindInitCurrSelectId() { }
	// RVA: 0x31390b0 VA: 0x75957510b0
	public Void UpdatePlayerData() { }
	// RVA: 0x3138dd8 VA: 0x7595750dd8
	private Void _UpdatePlayerData() { }
	// RVA: 0x31391e0 VA: 0x75957511e0
	public Boolean TrySelectEffect(String effectId) { }
	// RVA: 0x313930c VA: 0x759575130c
	public Boolean IsAllEffectUnlock() { }
	// RVA: 0x3139404 VA: 0x7595751404
	public Void .ctor() { }
}
```