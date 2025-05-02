# ClimbTowerSquadSingleEditStateBean

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSquadSingleEditProp m_squadProp`

- `CharAttrViewProperty m_attrPop`

- `Int32 m_selectCardId`


## Properties

- `ClimbTowerSquadSingleEditProp squadProp`

- `CharAttrViewProperty attrProp`


## Methods

- `ClimbTowerSquadSingleEditProp get_squadProp()`

- `CharAttrViewProperty get_attrProp()`

- `Void SelectCard(Int32)`

- `Void InitData(UIPage)`

- `Void UpdateAttrProp(Int32)`

- `Void SelectSkill(String)`

- `Void SelectBranch(String)`

- `Void SaveEditDict()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadSingleEditStateBean : IStateBean, IHotfixable
{
	private ClimbTowerSquadSingleEditProp m_squadProp; // 0x10
	private CharAttrViewProperty m_attrPop; // 0x18
	private Int32 m_selectCardId; // 0x20
	private static DelegateBridge __Hotfix0_get_squadProp; // 0x0
	private static DelegateBridge __Hotfix0_get_attrProp; // 0x8
	private static DelegateBridge __Hotfix0_SelectCard; // 0x10
	private static DelegateBridge __Hotfix0_InitData; // 0x18
	private static DelegateBridge __Hotfix0_UpdateAttrProp; // 0x20
	private static DelegateBridge __Hotfix0_SelectSkill; // 0x28
	private static DelegateBridge __Hotfix0_SelectBranch; // 0x30
	private static DelegateBridge __Hotfix0_SaveEditDict; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public ClimbTowerSquadSingleEditProp squadProp { get; }
	public CharAttrViewProperty attrProp { get; }

	// RVA: 0x2cca7ac VA: 0x75952e27ac
	public ClimbTowerSquadSingleEditProp get_squadProp() { }
	// RVA: 0x2cca814 VA: 0x75952e2814
	public CharAttrViewProperty get_attrProp() { }
	// RVA: 0x2ccc5b8 VA: 0x75952e45b8
	public Void SelectCard(Int32 cardId) { }
	// RVA: 0x2cca6f4 VA: 0x75952e26f4
	public Void InitData(UIPage page) { }
	// RVA: 0x2ccadac VA: 0x75952e2dac
	public Void UpdateAttrProp(Int32 cardId) { }
	// RVA: 0x2ccb6fc VA: 0x75952e36fc
	public Void SelectSkill(String skillId) { }
	// RVA: 0x2ccba18 VA: 0x75952e3a18
	public Void SelectBranch(String equipId) { }
	// RVA: 0x2ccb2d0 VA: 0x75952e32d0
	public Void SaveEditDict() { }
	// RVA: 0x2ccbcec VA: 0x75952e3cec
	public Void .ctor() { }
}
```