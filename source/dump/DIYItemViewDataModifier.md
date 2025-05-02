# DIYItemViewDataModifier

**Namespace:** ` `


## Fields

- `IDIYRoomModifierData m_modifierData`

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
private class DIYItemViewDataModifier : DIYItemViewData
{
	private IDIYRoomModifierData m_modifierData; // 0x38
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

	// RVA: 0x3820e6c VA: 0x7595e38e6c
	public Void .ctor(IDIYRoomModifierData target) { }
	// RVA: 0x3821800 VA: 0x7595e39800
	public override Sprite GetBigSprite() { }
	// RVA: 0x38218dc VA: 0x7595e398dc
	public override Boolean ButtonValid() { }
	// RVA: 0x3821950 VA: 0x7595e39950
	public override Boolean ShowComfort() { }
	// RVA: 0x38219b8 VA: 0x7595e399b8
	public override Int32 GetComfort() { }
	// RVA: 0x3821a94 VA: 0x7595e39a94
	public override String GetDisplayName() { }
	// RVA: 0x3821b70 VA: 0x7595e39b70
	public override Object GetTarget() { }
	// RVA: 0x3821bd8 VA: 0x7595e39bd8
	public override IDIYItem get_diyItem() { }
	// RVA: 0x3821c40 VA: 0x7595e39c40
	public override Int32 get_enableRoomType() { }
	// RVA: 0x3821d1c VA: 0x7595e39d1c
	public override FurnitureType get_furnitureType() { }
	// RVA: 0x3821df8 VA: 0x7595e39df8
	public override FurnitureSubType get_subType() { }
	// RVA: 0x3821ed4 VA: 0x7595e39ed4
	public override Boolean ShowLowerInfoButton() { }
	// RVA: 0x3821f3c VA: 0x7595e39f3c
	public override Boolean ShowTotalCount() { }
	// RVA: 0x3821fa4 VA: 0x7595e39fa4
	public override Void SetShowTotalCount(Boolean showTotalCount) { }
	// RVA: 0x3822024 VA: 0x7595e3a024
	private Sprite <>xLuaBaseProxy_GetBigSprite() { }
	// RVA: 0x3822028 VA: 0x7595e3a028
	private Boolean <>xLuaBaseProxy_ButtonValid() { }
	// RVA: 0x382202c VA: 0x7595e3a02c
	private Boolean <>xLuaBaseProxy_ShowComfort() { }
	// RVA: 0x3822030 VA: 0x7595e3a030
	private Int32 <>xLuaBaseProxy_GetComfort() { }
	// RVA: 0x3822034 VA: 0x7595e3a034
	private String <>xLuaBaseProxy_GetDisplayName() { }
	// RVA: 0x3822038 VA: 0x7595e3a038
	private Object <>xLuaBaseProxy_GetTarget() { }
	// RVA: 0x382203c VA: 0x7595e3a03c
	private IDIYItem <>xLuaBaseProxy_get_diyItem() { }
	// RVA: 0x3822040 VA: 0x7595e3a040
	private Int32 <>xLuaBaseProxy_get_enableRoomType() { }
	// RVA: 0x3822044 VA: 0x7595e3a044
	private FurnitureType <>xLuaBaseProxy_get_furnitureType() { }
	// RVA: 0x3822048 VA: 0x7595e3a048
	private FurnitureSubType <>xLuaBaseProxy_get_subType() { }
	// RVA: 0x382204c VA: 0x7595e3a04c
	private Boolean <>xLuaBaseProxy_ShowLowerInfoButton() { }
	// RVA: 0x3822050 VA: 0x7595e3a050
	private Boolean <>xLuaBaseProxy_ShowTotalCount() { }
	// RVA: 0x3822054 VA: 0x7595e3a054
	private Void <>xLuaBaseProxy_SetShowTotalCount(Boolean P0) { }
}
```