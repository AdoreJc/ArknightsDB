# BuildingTrackPointModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `BuildingToDoNotifyModel m_viewModel`

- `Boolean m_isUnlocked`


## Properties

- `BuildingToDoNotifyModel viewModel`

- `Boolean isShow`


## Methods

- `BuildingToDoNotifyModel get_viewModel()`

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class BuildingTrackPointModel : ITrackPointModel, IHotfixable
{
	private BuildingToDoNotifyModel m_viewModel; // 0x10
	private Boolean m_isUnlocked; // 0x18
	private static DelegateBridge __Hotfix0_get_viewModel; // 0x0
	private static DelegateBridge __Hotfix0_get_isShow; // 0x8
	private static DelegateBridge __Hotfix0_UpdateState; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public BuildingToDoNotifyModel viewModel { get; }
	public Boolean isShow { get; }

	// RVA: 0x281b24c VA: 0x7594e3324c
	public BuildingToDoNotifyModel get_viewModel() { }
	// RVA: 0x281b2b4 VA: 0x7594e332b4
	public Boolean get_isShow() { }
	// RVA: 0x281b36c VA: 0x7594e3336c
	public Void UpdateState(Object param) { }
	// RVA: 0x281b40c VA: 0x7594e3340c
	public Void .ctor() { }
}
```