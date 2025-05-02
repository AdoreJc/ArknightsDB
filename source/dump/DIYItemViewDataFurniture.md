# DIYItemViewDataFurniture

**Namespace:** ` `


## Fields

- `IFurnitureData m_furnitureData`

- `Boolean m_showTotalCount`


## Methods

- `Sprite <>xLuaBaseProxy_GetBigSprite()`

- `Boolean <>xLuaBaseProxy_ButtonValid()`

- `Boolean <>xLuaBaseProxy_ShowComfort()`

- `Int32 <>xLuaBaseProxy_GetComfort()`

- `String <>xLuaBaseProxy_GetDisplayName()`

- `Object <>xLuaBaseProxy_GetTarget()`

- `IDIYItem <>xLuaBaseProxy_get_diyItem()`

- `Int32 <>xLuaBaseProxy_get_enableRoomType()`

- `FurnitureType <>xLuaBaseProxy_get_furnitureType()`

- `FurnitureSubType <>xLuaBaseProxy_get_subType()`

- `Boolean <>xLuaBaseProxy_ShowLowerInfoButton()`

- `Boolean <>xLuaBaseProxy_ShowTotalCount()`

- `Void <>xLuaBaseProxy_SetShowTotalCount(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DIYItemViewDataFurniture : DIYItemViewData
{
	private IFurnitureData m_furnitureData; // 0x38
	private Boolean m_showTotalCount; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetBigSprite; // 0x8
	private static DelegateBridge __Hotfix0_ButtonValid; // 0x10
	private static DelegateBridge __Hotfix0_ShowComfort; // 0x18
	private static DelegateBridge __Hotfix0_GetComfort; // 0x20
	private static DelegateBridge __Hotfix0_GetDisplayName; // 0x28
	private static DelegateBridge __Hotfix0_GetTarget; // 0x30
	private static DelegateBridge __Hotfix0_get_diyItem; // 0x38
	private static DelegateBridge __Hotfix0_get_enableRoomType; // 0x40
	private static DelegateBridge __Hotfix0_get_furnitureType; // 0x48
	private static DelegateBridge __Hotfix0_get_subType; // 0x50
	private static DelegateBridge __Hotfix0_ShowLowerInfoButton; // 0x58
	private static DelegateBridge __Hotfix0_ShowTotalCount; // 0x60
	private static DelegateBridge __Hotfix0_SetShowTotalCount; // 0x68

	public override IDIYItem diyItem { get; }
	public override Int32 enableRoomType { get; }
	public override FurnitureType furnitureType { get; }
	public override FurnitureSubType subType { get; }

	// RVA: 0x3820ddc VA: 0x7595e38ddc
	public Void .ctor(IFurnitureData target) { }
	// RVA: 0x3820fa4 VA: 0x7595e38fa4
	public override Sprite GetBigSprite() { }
	// RVA: 0x3821080 VA: 0x7595e39080
	public override Boolean ButtonValid() { }
	// RVA: 0x38210f4 VA: 0x7595e390f4
	public override Boolean ShowComfort() { }
	// RVA: 0x382115c VA: 0x7595e3915c
	public override Int32 GetComfort() { }
	// RVA: 0x3821238 VA: 0x7595e39238
	public override String GetDisplayName() { }
	// RVA: 0x3821314 VA: 0x7595e39314
	public override Object GetTarget() { }
	// RVA: 0x382137c VA: 0x7595e3937c
	public override IDIYItem get_diyItem() { }
	// RVA: 0x38213e4 VA: 0x7595e393e4
	public override Int32 get_enableRoomType() { }
	// RVA: 0x38214c0 VA: 0x7595e394c0
	public override FurnitureType get_furnitureType() { }
	// RVA: 0x382159c VA: 0x7595e3959c
	public override FurnitureSubType get_subType() { }
	// RVA: 0x3821678 VA: 0x7595e39678
	public override Boolean ShowLowerInfoButton() { }
	// RVA: 0x38216e0 VA: 0x7595e396e0
	public override Boolean ShowTotalCount() { }
	// RVA: 0x3821748 VA: 0x7595e39748
	public override Void SetShowTotalCount(Boolean showTotalCount) { }
	// RVA: 0x38217c8 VA: 0x7595e397c8
	private Sprite <>xLuaBaseProxy_GetBigSprite() { }
	// RVA: 0x38217cc VA: 0x7595e397cc
	private Boolean <>xLuaBaseProxy_ButtonValid() { }
	// RVA: 0x38217d0 VA: 0x7595e397d0
	private Boolean <>xLuaBaseProxy_ShowComfort() { }
	// RVA: 0x38217d4 VA: 0x7595e397d4
	private Int32 <>xLuaBaseProxy_GetComfort() { }
	// RVA: 0x38217d8 VA: 0x7595e397d8
	private String <>xLuaBaseProxy_GetDisplayName() { }
	// RVA: 0x38217dc VA: 0x7595e397dc
	private Object <>xLuaBaseProxy_GetTarget() { }
	// RVA: 0x38217e0 VA: 0x7595e397e0
	private IDIYItem <>xLuaBaseProxy_get_diyItem() { }
	// RVA: 0x38217e4 VA: 0x7595e397e4
	private Int32 <>xLuaBaseProxy_get_enableRoomType() { }
	// RVA: 0x38217e8 VA: 0x7595e397e8
	private FurnitureType <>xLuaBaseProxy_get_furnitureType() { }
	// RVA: 0x38217ec VA: 0x7595e397ec
	private FurnitureSubType <>xLuaBaseProxy_get_subType() { }
	// RVA: 0x38217f0 VA: 0x7595e397f0
	private Boolean <>xLuaBaseProxy_ShowLowerInfoButton() { }
	// RVA: 0x38217f4 VA: 0x7595e397f4
	private Boolean <>xLuaBaseProxy_ShowTotalCount() { }
	// RVA: 0x38217f8 VA: 0x7595e397f8
	private Void <>xLuaBaseProxy_SetShowTotalCount(Boolean P0) { }
}
```