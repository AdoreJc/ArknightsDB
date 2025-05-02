# StationSelectConfirmStateBean

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `StationConfirmModel stateInput`

- `Boolean isConfirm`

- `StationSelectConfirmCharProperty selectConfirmProperty`


## Methods

- `Void LoadInput()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class StationSelectConfirmStateBean : IStateBean, IHotfixable
{
	public StationConfirmModel stateInput; // 0x10
	public List`1 changedRoomGroupProperty; // 0x18
	public Boolean isConfirm; // 0x20
	public StationSelectConfirmCharProperty selectConfirmProperty; // 0x28
	private static DelegateBridge __Hotfix0_LoadInput; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3d8eda8 VA: 0x75963a6da8
	public Void LoadInput() { }
	// RVA: 0x3d904f4 VA: 0x75963a84f4
	public Void .ctor() { }
}
```