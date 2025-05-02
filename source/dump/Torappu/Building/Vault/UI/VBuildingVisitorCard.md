# VBuildingVisitorCard

**Namespace:** `Torappu.Building.Vault.UI`


## Fields

- `Text _textName`

- `Text _textLevel`

- `GameObject _panelCard`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault.UI
public class VBuildingVisitorCard : VOUIPanel
{
	private Text _textName; // 0x28
	private Text _textLevel; // 0x30
	private GameObject _panelCard; // 0x38


	// RVA: 0x3d0eba4 VA: 0x7596326ba4
	public override Boolean MatchObject(BuildingEvent evt, Object roomObject) { }
	// RVA: 0x3d0ecac VA: 0x7596326cac
	protected override Vector3 PanelWorldCenter() { }
	// RVA: 0x3d0ed58 VA: 0x7596326d58
	protected override Void OnRoomObjectBinded(Object roomObj) { }
	// RVA: 0x3d0eeb8 VA: 0x7596326eb8
	protected override Void UpdateRender() { }
	// RVA: 0x3d0efc8 VA: 0x7596326fc8
	public Void .ctor() { }
}
```