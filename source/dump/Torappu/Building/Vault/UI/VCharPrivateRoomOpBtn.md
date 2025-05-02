# VCharPrivateRoomOpBtn

**Namespace:** `Torappu.Building.Vault.UI`


## Fields

- `CanvasGroup _btnCanvasGroup`

- `FadeSwitchTween m_btnSwitch`


## Methods

- `Boolean _MatchObjectWhenVisit(BuildingEvent, Object)`

- `Boolean _IsLodVisible()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault.UI
public class VCharPrivateRoomOpBtn : VOUIPanel
{
	private CanvasGroup _btnCanvasGroup; // 0x28
	private FadeSwitchTween m_btnSwitch; // 0x30


	// RVA: 0x3d10cd0 VA: 0x7596328cd0
	public override Boolean MatchObject(BuildingEvent evt, Object roomObject) { }
	// RVA: 0x3d10d90 VA: 0x7596328d90
	private Boolean _MatchObjectWhenVisit(BuildingEvent evt, Object roomObject) { }
	// RVA: 0x3d10eac VA: 0x7596328eac
	protected override Void OnRoomObjectStatusChanged() { }
	// RVA: 0x3d10ed8 VA: 0x7596328ed8
	protected override Vector3 PanelWorldCenter() { }
	// RVA: 0x3d10f84 VA: 0x7596328f84
	protected override Void UpdateRender() { }
	// RVA: 0x3d11194 VA: 0x7596329194
	private Boolean _IsLodVisible() { }
	// RVA: 0x3d111fc VA: 0x75963291fc
	public Void OnClick() { }
	// RVA: 0x3d11420 VA: 0x7596329420
	public Void .ctor() { }
}
```