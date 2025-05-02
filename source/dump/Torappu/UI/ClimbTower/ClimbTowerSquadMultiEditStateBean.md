# ClimbTowerSquadMultiEditStateBean

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSquadMultiEditProp m_prop`


## Properties

- `ClimbTowerSquadMultiEditProp prop`


## Methods

- `ClimbTowerSquadMultiEditProp get_prop()`

- `Void InitData(UIPage)`

- `Void SetFocusIndex(Int32, Single)`

- `Void SaveEditDict()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadMultiEditStateBean : IStateBean, IHotfixable
{
	private ClimbTowerSquadMultiEditProp m_prop; // 0x10
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_InitData; // 0x8
	private static DelegateBridge __Hotfix0_SetFocusIndex; // 0x10
	private static DelegateBridge __Hotfix0_SaveEditDict; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public ClimbTowerSquadMultiEditProp prop { get; }

	// RVA: 0x2cc4b1c VA: 0x75952dcb1c
	public ClimbTowerSquadMultiEditProp get_prop() { }
	// RVA: 0x2cc49f0 VA: 0x75952dc9f0
	public Void InitData(UIPage page) { }
	// RVA: 0x2cbbf38 VA: 0x75952d3f38
	public Void SetFocusIndex(Int32 viewIndex, Single columnIndex) { }
	// RVA: 0x2cc5094 VA: 0x75952dd094
	public Void SaveEditDict() { }
	// RVA: 0x2cc58b4 VA: 0x75952dd8b4
	public Void .ctor() { }
}
```