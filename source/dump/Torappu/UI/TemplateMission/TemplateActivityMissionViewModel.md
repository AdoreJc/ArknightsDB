# TemplateActivityMissionViewModel

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `TemplateMissionInputParam <param>k__BackingField`

- `TemplateMissionViewModel m_viewModel`


## Properties

- `TemplateMissionInputParam param`


## Methods

- `TemplateMissionInputParam get_param()`

- `Void set_param(TemplateMissionInputParam)`

- `Void RefreshMissionState()`

- `Boolean CheckHaveMissionToGet()`

- `Boolean CheckMissionListPlayerDataChanged(PlayerDataModel, PlayerDataModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateActivityMissionViewModel : TemplateActivityViewModel
{
	private TemplateMissionInputParam <param>k__BackingField; // 0x20
	private TemplateMissionViewModel m_viewModel; // 0x28
	private static DelegateBridge __Hotfix0_get_param; // 0x0
	private static DelegateBridge __Hotfix0_set_param; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_RefreshMissionState; // 0x18
	private static DelegateBridge __Hotfix0_CheckHaveMissionToGet; // 0x20
	private static DelegateBridge __Hotfix0_CheckMissionListPlayerDataChanged; // 0x28

	public TemplateMissionInputParam param { get; set; }

	// RVA: 0x2371ba8 VA: 0x7594989ba8
	public TemplateMissionInputParam get_param() { }
	// RVA: 0x2371c10 VA: 0x7594989c10
	private Void set_param(TemplateMissionInputParam value) { }
	// RVA: 0x2371c94 VA: 0x7594989c94
	public Void .ctor(Object param) { }
	// RVA: 0x2371e0c VA: 0x7594989e0c
	public Void RefreshMissionState() { }
	// RVA: 0x2371e84 VA: 0x7594989e84
	public Boolean CheckHaveMissionToGet() { }
	// RVA: 0x2371f34 VA: 0x7594989f34
	public Boolean CheckMissionListPlayerDataChanged(PlayerDataModel prevData, PlayerDataModel curData) { }
}
```