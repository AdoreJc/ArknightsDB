# SandboxV2CharFoodModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Int32 m_instId`

- `Int32 m_rarity`

- `Int32 m_duration`

- `Int32 m_remainTime`

- `Int32 m_maxDuration`

- `SandboxV2FoodAttribute m_foodAttr`

- `String m_foodId`

- `Boolean <isSub>k__BackingField`

- `String <detailInfo>k__BackingField`

- `String <itemName>k__BackingField`


## Properties

- `Boolean isSub`

- `String detailInfo`

- `String itemName`

- `String foodId`

- `Boolean isExpireOrEmpty`

- `Boolean isExpire`

- `Boolean isEmpty`

- `Int32 rarity`

- `Int64 remainTime`

- `Boolean isLasting`

- `Single normalizedDuration`

- `Single normalizedRemain`

- `SandboxV2FoodAttribute foodAttr`


## Methods

- `Boolean get_isSub()`

- `Void set_isSub(Boolean)`

- `String get_detailInfo()`

- `Void set_detailInfo(String)`

- `String get_itemName()`

- `Void set_itemName(String)`

- `String get_foodId()`

- `Boolean get_isExpireOrEmpty()`

- `Boolean get_isExpire()`

- `Boolean get_isEmpty()`

- `Int32 get_rarity()`

- `Int64 get_remainTime()`

- `Boolean get_isLasting()`

- `Single get_normalizedDuration()`

- `Single get_normalizedRemain()`

- `SandboxV2FoodAttribute get_foodAttr()`

- `Void LoadData(String, Int32, CharFood)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharFoodModel : IHotfixable
{
	private Int32 m_instId; // 0x10
	private Int32 m_rarity; // 0x14
	private Int32 m_duration; // 0x18
	private Int32 m_remainTime; // 0x1c
	private Int32 m_maxDuration; // 0x20
	private SandboxV2FoodAttribute m_foodAttr; // 0x24
	private String m_foodId; // 0x28
	private Boolean <isSub>k__BackingField; // 0x30
	private String <detailInfo>k__BackingField; // 0x38
	private String <itemName>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_isSub; // 0x0
	private static DelegateBridge __Hotfix0_set_isSub; // 0x8
	private static DelegateBridge __Hotfix0_get_detailInfo; // 0x10
	private static DelegateBridge __Hotfix0_set_detailInfo; // 0x18
	private static DelegateBridge __Hotfix0_get_itemName; // 0x20
	private static DelegateBridge __Hotfix0_set_itemName; // 0x28
	private static DelegateBridge __Hotfix0_get_foodId; // 0x30
	private static DelegateBridge __Hotfix0_get_isExpireOrEmpty; // 0x38
	private static DelegateBridge __Hotfix0_get_isExpire; // 0x40
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x48
	private static DelegateBridge __Hotfix0_get_rarity; // 0x50
	private static DelegateBridge __Hotfix0_get_remainTime; // 0x58
	private static DelegateBridge __Hotfix0_get_isLasting; // 0x60
	private static DelegateBridge __Hotfix0_get_normalizedDuration; // 0x68
	private static DelegateBridge __Hotfix0_get_normalizedRemain; // 0x70
	private static DelegateBridge __Hotfix0_get_foodAttr; // 0x78
	private static DelegateBridge __Hotfix0_LoadData; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Boolean isSub { get; set; }
	public String detailInfo { get; set; }
	public String itemName { get; set; }
	public String foodId { get; }
	public Boolean isExpireOrEmpty { get; }
	public Boolean isExpire { get; }
	public Boolean isEmpty { get; }
	public Int32 rarity { get; }
	public Int64 remainTime { get; }
	public Boolean isLasting { get; }
	public Single normalizedDuration { get; }
	public Single normalizedRemain { get; }
	public SandboxV2FoodAttribute foodAttr { get; }

	// RVA: 0x26122ec VA: 0x7594c2a2ec
	public Boolean get_isSub() { }
	// RVA: 0x2612354 VA: 0x7594c2a354
	private Void set_isSub(Boolean value) { }
	// RVA: 0x26123d4 VA: 0x7594c2a3d4
	public String get_detailInfo() { }
	// RVA: 0x261243c VA: 0x7594c2a43c
	private Void set_detailInfo(String value) { }
	// RVA: 0x26124c0 VA: 0x7594c2a4c0
	public String get_itemName() { }
	// RVA: 0x2612528 VA: 0x7594c2a528
	private Void set_itemName(String value) { }
	// RVA: 0x26125ac VA: 0x7594c2a5ac
	public String get_foodId() { }
	// RVA: 0x260b834 VA: 0x7594c23834
	public Boolean get_isExpireOrEmpty() { }
	// RVA: 0x2612614 VA: 0x7594c2a614
	public Boolean get_isExpire() { }
	// RVA: 0x2612684 VA: 0x7594c2a684
	public Boolean get_isEmpty() { }
	// RVA: 0x261270c VA: 0x7594c2a70c
	public Int32 get_rarity() { }
	// RVA: 0x2612774 VA: 0x7594c2a774
	public Int64 get_remainTime() { }
	// RVA: 0x260b8b8 VA: 0x7594c238b8
	public Boolean get_isLasting() { }
	// RVA: 0x260b924 VA: 0x7594c23924
	public Single get_normalizedDuration() { }
	// RVA: 0x260b9b4 VA: 0x7594c239b4
	public Single get_normalizedRemain() { }
	// RVA: 0x260ba44 VA: 0x7594c23a44
	public SandboxV2FoodAttribute get_foodAttr() { }
	// RVA: 0x2611f44 VA: 0x7594c29f44
	public Void LoadData(String topicId, Int32 charInstId, CharFood playerCharFood) { }
	// RVA: 0x2611ed4 VA: 0x7594c29ed4
	public Void .ctor() { }
}
```