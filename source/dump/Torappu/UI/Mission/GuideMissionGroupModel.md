# GuideMissionGroupModel

**Namespace:** `Torappu.UI.Mission`


## Fields

- `String <groupId>k__BackingField`

- `String <shortName>k__BackingField`

- `Int32 <sortId>k__BackingField`

- `ItemBundle <rewardItem>k__BackingField`

- `String <itemIconId>k__BackingField`

- `Boolean <isRewardGot>k__BackingField`


## Properties

- `String groupId`

- `String shortName`

- `Int32 sortId`

- `ItemBundle rewardItem`

- `String itemIconId`

- `Boolean isRewardGot`

- `Boolean isCharReward`


## Methods

- `String get_groupId()`

- `Void set_groupId(String)`

- `String get_shortName()`

- `Void set_shortName(String)`

- `Int32 get_sortId()`

- `Void set_sortId(Int32)`

- `ItemBundle get_rewardItem()`

- `Void set_rewardItem(ItemBundle)`

- `String get_itemIconId()`

- `Void set_itemIconId(String)`

- `Boolean get_isRewardGot()`

- `Void set_isRewardGot(Boolean)`

- `Boolean get_isCharReward()`

- `Void LoadData(GuideMissionGroupInfo, MissionGroup)`

- `Void _UpdatePlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class GuideMissionGroupModel : IHotfixable
{
	private String <groupId>k__BackingField; // 0x10
	private String <shortName>k__BackingField; // 0x18
	private Int32 <sortId>k__BackingField; // 0x20
	private ItemBundle <rewardItem>k__BackingField; // 0x28
	private String <itemIconId>k__BackingField; // 0x30
	private Boolean <isRewardGot>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_groupId; // 0x0
	private static DelegateBridge __Hotfix0_set_groupId; // 0x8
	private static DelegateBridge __Hotfix0_get_shortName; // 0x10
	private static DelegateBridge __Hotfix0_set_shortName; // 0x18
	private static DelegateBridge __Hotfix0_get_sortId; // 0x20
	private static DelegateBridge __Hotfix0_set_sortId; // 0x28
	private static DelegateBridge __Hotfix0_get_rewardItem; // 0x30
	private static DelegateBridge __Hotfix0_set_rewardItem; // 0x38
	private static DelegateBridge __Hotfix0_get_itemIconId; // 0x40
	private static DelegateBridge __Hotfix0_set_itemIconId; // 0x48
	private static DelegateBridge __Hotfix0_get_isRewardGot; // 0x50
	private static DelegateBridge __Hotfix0_set_isRewardGot; // 0x58
	private static DelegateBridge __Hotfix0_get_isCharReward; // 0x60
	private static DelegateBridge __Hotfix0_LoadData; // 0x68
	private static DelegateBridge __Hotfix0__UpdatePlayerData; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public String groupId { get; set; }
	public String shortName { get; set; }
	public Int32 sortId { get; set; }
	public ItemBundle rewardItem { get; set; }
	public String itemIconId { get; set; }
	public Boolean isRewardGot { get; set; }
	public Boolean isCharReward { get; }

	// RVA: 0x27332f8 VA: 0x7594d4b2f8
	public String get_groupId() { }
	// RVA: 0x2734064 VA: 0x7594d4c064
	private Void set_groupId(String value) { }
	// RVA: 0x27328a8 VA: 0x7594d4a8a8
	public String get_shortName() { }
	// RVA: 0x27340e8 VA: 0x7594d4c0e8
	private Void set_shortName(String value) { }
	// RVA: 0x2733ffc VA: 0x7594d4bffc
	public Int32 get_sortId() { }
	// RVA: 0x273416c VA: 0x7594d4c16c
	private Void set_sortId(Int32 value) { }
	// RVA: 0x2732a3c VA: 0x7594d4aa3c
	public ItemBundle get_rewardItem() { }
	// RVA: 0x27341e8 VA: 0x7594d4c1e8
	private Void set_rewardItem(ItemBundle value) { }
	// RVA: 0x273426c VA: 0x7594d4c26c
	public String get_itemIconId() { }
	// RVA: 0x27342d4 VA: 0x7594d4c2d4
	private Void set_itemIconId(String value) { }
	// RVA: 0x2732840 VA: 0x7594d4a840
	public Boolean get_isRewardGot() { }
	// RVA: 0x2734358 VA: 0x7594d4c358
	private Void set_isRewardGot(Boolean value) { }
	// RVA: 0x2733164 VA: 0x7594d4b164
	public Boolean get_isCharReward() { }
	// RVA: 0x2733c88 VA: 0x7594d4bc88
	public Void LoadData(GuideMissionGroupInfo guideInfo, MissionGroup groupData) { }
	// RVA: 0x27343d8 VA: 0x7594d4c3d8
	private Void _UpdatePlayerData() { }
	// RVA: 0x2733c18 VA: 0x7594d4bc18
	public Void .ctor() { }
}
```