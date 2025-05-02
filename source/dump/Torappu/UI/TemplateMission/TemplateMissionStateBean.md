# TemplateMissionStateBean

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `TemplateMissionProperty m_property`

- `TemplateMissionInputParam m_param`


## Properties

- `TemplateMissionProperty property`

- `TemplateMissionInputParam inputParam`


## Methods

- `TemplateMissionProperty get_property()`

- `TemplateMissionInputParam get_inputParam()`

- `Void SetInputData(TemplateMissionInputParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionStateBean : IStateBean, IHotfixable
{
	private TemplateMissionProperty m_property; // 0x10
	private TemplateMissionInputParam m_param; // 0x18
	private static DelegateBridge __Hotfix0_get_property; // 0x0
	private static DelegateBridge __Hotfix0_get_inputParam; // 0x8
	private static DelegateBridge __Hotfix0_SetInputData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public TemplateMissionProperty property { get; }
	public TemplateMissionInputParam inputParam { get; }

	// RVA: 0x236cfe8 VA: 0x7594984fe8
	public TemplateMissionProperty get_property() { }
	// RVA: 0x236c4f8 VA: 0x75949844f8
	public TemplateMissionInputParam get_inputParam() { }
	// RVA: 0x236d050 VA: 0x7594985050
	public Void SetInputData(TemplateMissionInputParam param) { }
	// RVA: 0x236cd24 VA: 0x7594984d24
	public Void .ctor() { }
}
```