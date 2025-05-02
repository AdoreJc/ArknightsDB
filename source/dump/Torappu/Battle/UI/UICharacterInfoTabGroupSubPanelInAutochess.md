# UICharacterInfoTabGroupSubPanelInAutochess

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIAutochessEquipPair _equipTextPair`

- `LayoutGroup _equipLayoutGroup`

- `Boolean m_isActiveEquipTab`

- `ActivityAutoChessVerify1Data m_data`


## Properties

- `AutoChessDataCenter center`


## Methods

- `AutoChessDataCenter get_center()`

- `Boolean _RefreshEquipData(ObjectPtr`1, ModeType, Card)`

- `Boolean _UpdateEquip(GridPosition)`

- `Void <>xLuaBaseProxy_Reset()`

- `Void <>xLuaBaseProxy_SetData(ObjectPtr`1, ModeType, Card)`

- `Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1, ModeType, Card)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICharacterInfoTabGroupSubPanelInAutochess : UICharacterInfoTabGroupSubPanel
{
	private const Int32 MAX_EQUIP_SHOW_COUNT; // 0x0
	private const String EQUIP_TRACKER_FORMAT; // 0x0
	private UIAutochessEquipPair _equipTextPair; // 0xb0
	private LayoutGroup _equipLayoutGroup; // 0xb8
	private Boolean m_isActiveEquipTab; // 0xc0
	private List`1 m_equipTextPair; // 0xc8
	private ActivityAutoChessVerify1Data m_data; // 0xd0
	private static DelegateBridge __Hotfix0_get_center; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_SetData; // 0x10
	private static DelegateBridge __Hotfix0__RefreshEquipData; // 0x18
	private static DelegateBridge __Hotfix0__UpdateEquip; // 0x20
	private static DelegateBridge __Hotfix0_UpdateData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private AutoChessDataCenter center { get; }

	// RVA: 0x2039efc VA: 0x7594651efc
	private AutoChessDataCenter get_center() { }
	// RVA: 0x2039f78 VA: 0x7594651f78
	public override Void Reset() { }
	// RVA: 0x203a0f4 VA: 0x75946520f4
	public override Void SetData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x203a20c VA: 0x759465220c
	private Boolean _RefreshEquipData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x203a344 VA: 0x7594652344
	private Boolean _UpdateEquip(GridPosition pos) { }
	// RVA: 0x203a75c VA: 0x759465275c
	public override Void UpdateData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x203a858 VA: 0x7594652858
	public Void .ctor() { }
	// RVA: 0x203a918 VA: 0x7594652918
	private Void <>xLuaBaseProxy_Reset() { }
	// RVA: 0x203a91c VA: 0x759465291c
	private Void <>xLuaBaseProxy_SetData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
	// RVA: 0x203a920 VA: 0x7594652920
	private Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
}
```