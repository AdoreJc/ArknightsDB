# VBuildingFuncTagIcon

**Namespace:** `Torappu.Building.Vault.UI`


## Fields

- `BuildingCharModel m_charModel`

- `ILODHolder m_lodHolder`


## Properties

- `ILODHolder lodHolder`

- `Boolean lodVisible`


## Methods

- `ILODHolder get_lodHolder()`

- `Boolean get_lodVisible()`

- `Boolean _CheckIfIconVisible()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault.UI
public class VBuildingFuncTagIcon : VOUIPanel
{
	private const Single VISIBLE_HIGHT_THRESHOLD; // 0x0
	private AbstractVFuncTagSubItem[] _subItems; // 0x28
	private BuildingCharModel m_charModel; // 0x30
	private ILODHolder m_lodHolder; // 0xa0

	private ILODHolder lodHolder { get; }
	private Boolean lodVisible { get; }

	// RVA: 0x3d0e0a0 VA: 0x75963260a0
	private ILODHolder get_lodHolder() { }
	// RVA: 0x3d0e104 VA: 0x7596326104
	private Boolean get_lodVisible() { }
	// RVA: 0x3d0e1c4 VA: 0x75963261c4
	public override Boolean MatchObject(BuildingEvent evt, Object roomObject) { }
	// RVA: 0x3d0e368 VA: 0x7596326368
	protected override Void OnRoomObjectBinded(Object roomObj) { }
	// RVA: 0x3d0e478 VA: 0x7596326478
	protected override Void OnRoomObjectStatusChanged() { }
	// RVA: 0x3d0e550 VA: 0x7596326550
	protected override Void UpdateRender() { }
	// RVA: 0x3d0e69c VA: 0x759632669c
	private Boolean _CheckIfIconVisible() { }
	// RVA: 0x3d0e7f4 VA: 0x75963267f4
	public Void .ctor() { }
}
```