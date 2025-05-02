# ActMultiV3SquadEffectModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String m_actId`

- `ActMultiV3SquadEffectTokenModel m_tokenModel`

- `String <id>k__BackingField`

- `String <iconId>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `String <name>k__BackingField`

- `String <themeColor>k__BackingField`

- `String <buffDesc>k__BackingField`

- `String <debuffDesc>k__BackingField`

- `Int32 <unlockKeyNum>k__BackingField`

- `Boolean <isUnlock>k__BackingField`


## Properties

- `String id`

- `String iconId`

- `Int32 sortId`

- `String name`

- `String themeColor`

- `String buffDesc`

- `String debuffDesc`

- `Int32 unlockKeyNum`

- `Boolean isUnlock`

- `ActMultiV3SquadEffectTokenModel tokenModel`


## Methods

- `String get_id()`

- `Void set_id(String)`

- `String get_iconId()`

- `Void set_iconId(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `String get_name()`

- `Void set_name(String)`

- `String get_themeColor()`

- `Void set_themeColor(String)`

- `String get_buffDesc()`

- `Void set_buffDesc(String)`

- `String get_debuffDesc()`

- `Void set_debuffDesc(String)`

- `Int32 get_unlockKeyNum()`

- `Void set_unlockKeyNum(Int32)`

- `Boolean get_isUnlock()`

- `Void set_isUnlock(Boolean)`

- `ActMultiV3SquadEffectTokenModel get_tokenModel()`

- `Void LoadData(String, ActMultiV3SquadEffectData)`

- `Void UpdatePlayerData(TroopBuff)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadEffectModel : IHotfixable
{
	private String m_actId; // 0x10
	private ActMultiV3SquadEffectTokenModel m_tokenModel; // 0x18
	private String <id>k__BackingField; // 0x20
	private String <iconId>k__BackingField; // 0x28
	private Int32 <sortId>k__BackingField; // 0x30
	private String <name>k__BackingField; // 0x38
	private String <themeColor>k__BackingField; // 0x40
	private String <buffDesc>k__BackingField; // 0x48
	private String <debuffDesc>k__BackingField; // 0x50
	private Int32 <unlockKeyNum>k__BackingField; // 0x58
	private Boolean <isUnlock>k__BackingField; // 0x5c
	private static DelegateBridge __Hotfix0_get_id; // 0x0
	private static DelegateBridge __Hotfix0_set_id; // 0x8
	private static DelegateBridge __Hotfix0_get_iconId; // 0x10
	private static DelegateBridge __Hotfix0_set_iconId; // 0x18
	private static DelegateBridge __Hotfix0_get_sortId; // 0x20
	private static DelegateBridge __Hotfix0_set_sortId; // 0x28
	private static DelegateBridge __Hotfix0_get_name; // 0x30
	private static DelegateBridge __Hotfix0_set_name; // 0x38
	private static DelegateBridge __Hotfix0_get_themeColor; // 0x40
	private static DelegateBridge __Hotfix0_set_themeColor; // 0x48
	private static DelegateBridge __Hotfix0_get_buffDesc; // 0x50
	private static DelegateBridge __Hotfix0_set_buffDesc; // 0x58
	private static DelegateBridge __Hotfix0_get_debuffDesc; // 0x60
	private static DelegateBridge __Hotfix0_set_debuffDesc; // 0x68
	private static DelegateBridge __Hotfix0_get_unlockKeyNum; // 0x70
	private static DelegateBridge __Hotfix0_set_unlockKeyNum; // 0x78
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x80
	private static DelegateBridge __Hotfix0_set_isUnlock; // 0x88
	private static DelegateBridge __Hotfix0_get_tokenModel; // 0x90
	private static DelegateBridge __Hotfix0_LoadData; // 0x98
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public String id { get; set; }
	public String iconId { get; set; }
	public Int32 sortId { get; set; }
	public String name { get; set; }
	public String themeColor { get; set; }
	public String buffDesc { get; set; }
	public String debuffDesc { get; set; }
	public Int32 unlockKeyNum { get; set; }
	public Boolean isUnlock { get; set; }
	public ActMultiV3SquadEffectTokenModel tokenModel { get; }

	// RVA: 0x31377d8 VA: 0x759574f7d8
	public String get_id() { }
	// RVA: 0x31395f4 VA: 0x75957515f4
	private Void set_id(String value) { }
	// RVA: 0x3137ebc VA: 0x759574febc
	public String get_iconId() { }
	// RVA: 0x3139678 VA: 0x7595751678
	private Void set_iconId(String value) { }
	// RVA: 0x313958c VA: 0x759575158c
	public Int32 get_sortId() { }
	// RVA: 0x31396fc VA: 0x75957516fc
	private Void set_sortId(Int32 value) { }
	// RVA: 0x3137e54 VA: 0x759574fe54
	public String get_name() { }
	// RVA: 0x3139778 VA: 0x7595751778
	private Void set_name(String value) { }
	// RVA: 0x3137f24 VA: 0x759574ff24
	public String get_themeColor() { }
	// RVA: 0x31397fc VA: 0x75957517fc
	private Void set_themeColor(String value) { }
	// RVA: 0x3139880 VA: 0x7595751880
	public String get_buffDesc() { }
	// RVA: 0x31398e8 VA: 0x75957518e8
	private Void set_buffDesc(String value) { }
	// RVA: 0x313996c VA: 0x759575196c
	public String get_debuffDesc() { }
	// RVA: 0x31399d4 VA: 0x75957519d4
	private Void set_debuffDesc(String value) { }
	// RVA: 0x3137978 VA: 0x759574f978
	public Int32 get_unlockKeyNum() { }
	// RVA: 0x3139a58 VA: 0x7595751a58
	private Void set_unlockKeyNum(Int32 value) { }
	// RVA: 0x31378a8 VA: 0x759574f8a8
	public Boolean get_isUnlock() { }
	// RVA: 0x3139ad4 VA: 0x7595751ad4
	private Void set_isUnlock(Boolean value) { }
	// RVA: 0x3139b54 VA: 0x7595751b54
	public ActMultiV3SquadEffectTokenModel get_tokenModel() { }
	// RVA: 0x3138cd4 VA: 0x7595750cd4
	public Void LoadData(String actId, ActMultiV3SquadEffectData effectData) { }
	// RVA: 0x3139118 VA: 0x7595751118
	public Void UpdatePlayerData(TroopBuff playerSquadEffect) { }
	// RVA: 0x3138c28 VA: 0x7595750c28
	public Void .ctor() { }
}
```