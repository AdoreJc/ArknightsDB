# BuildingStationSelectCharList

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `BuildingStationSelectCharAdapter _adapter`

- `GameObject _panelEmpty`

- `Text _textEmpty`

- `Boolean m_rebuildListNextTime`

- `IPlugin m_statePlugin`


## Methods

- `Void InjectPlugin(IPlugin)`

- `Void MarkRebuildListNextTime()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectCharList : DataBinder`1
{
	private BuildingStationSelectCharAdapter _adapter; // 0x20
	private GameObject _panelEmpty; // 0x28
	private Text _textEmpty; // 0x30
	private Boolean m_rebuildListNextTime; // 0x38
	public Action`1 onCharClicked; // 0x40
	private IPlugin m_statePlugin; // 0x48
	private static DelegateBridge __Hotfix0_InjectPlugin; // 0x0
	private static DelegateBridge __Hotfix0_MarkRebuildListNextTime; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3d9c604 VA: 0x75963b4604
	public Void InjectPlugin(IPlugin statePlugin) { }
	// RVA: 0x3d9c688 VA: 0x75963b4688
	public Void MarkRebuildListNextTime() { }
	// RVA: 0x3d9c6f4 VA: 0x75963b46f4
	public override Void OnValueChanged(StationCharGroupProperty property) { }
	// RVA: 0x3d9c9c0 VA: 0x75963b49c0
	public Void .ctor() { }
}
```