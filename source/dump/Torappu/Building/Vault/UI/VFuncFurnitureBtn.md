# VFuncFurnitureBtn

**Namespace:** `Torappu.Building.Vault.UI`


## Fields

- `FurnitureSubType _subType`

- `CanvasGroup _uiPanel`

- `GameObject _trackPoint`

- `FurnitureSubType m_subType`

- `Boolean m_showTrackPoint`

- `Boolean m_funcInUse`

- `FadeSwitchTween m_fadeSwitchTween`

- `ILODHolder m_lodHolder`


## Properties

- `ILODHolder lodHolder`

- `Boolean lodVisible`


## Methods

- `Void OnClick()`

- `ILODHolder get_lodHolder()`

- `Boolean get_lodVisible()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault.UI
public class VFuncFurnitureBtn : VOUIPanel
{
	private FurnitureSubType _subType; // 0x24
	private CanvasGroup _uiPanel; // 0x28
	private GameObject _trackPoint; // 0x30
	protected FurnitureSubType m_subType; // 0x38
	protected Boolean m_showTrackPoint; // 0x3c
	protected Boolean m_funcInUse; // 0x3d
	private FadeSwitchTween m_fadeSwitchTween; // 0x40
	private ILODHolder m_lodHolder; // 0x48

	private ILODHolder lodHolder { get; }
	protected Boolean lodVisible { get; }

	// RVA: 0x3d0d2d4 VA: 0x75963252d4
	public override Boolean MatchObject(BuildingEvent evt, Object roomObject) { }
	// RVA: 0x3d0d370 VA: 0x7596325370
	protected override Vector3 PanelWorldCenter() { }
	// RVA: 0x3d0d448 VA: 0x7596325448
	protected override Void OnRoomObjectBinded(Object roomObj) { }
	// RVA: 0x3d0d5a0 VA: 0x75963255a0
	protected override Void OnRoomObjectStatusChanged() { }
	// RVA: 0x3d0d5ac VA: 0x75963255ac
	protected override Void UpdateRender() { }
	// RVA: 0x3d0d660 VA: 0x7596325660
	protected virtual Boolean _CheckShowBtn() { }
	// RVA: 0x3d0d7fc VA: 0x75963257fc
	protected virtual Void _UpdateStatus() { }
	// RVA: 0x3d0d898 VA: 0x7596325898
	public Void OnClick() { }
	// RVA: 0x3d0d958 VA: 0x7596325958
	private ILODHolder get_lodHolder() { }
	// RVA: 0x3d0d73c VA: 0x759632573c
	protected Boolean get_lodVisible() { }
	// RVA: 0x3d0d9bc VA: 0x75963259bc
	public Void .ctor() { }
}
```