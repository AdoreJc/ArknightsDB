# TemplateActivityLifeCycleViewModel

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `BasicData m_data`

- `ActState state`

- `Int64 remainTime`

- `Int64 endTime`


## Methods

- `Void RefreshData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityLifeCycleViewModel : TemplateActivityViewModel
{
	private BasicData m_data; // 0x20
	public ActState state; // 0x28
	public Int64 remainTime; // 0x30
	public Int64 endTime; // 0x38
	private static DelegateBridge __Hotfix0_RefreshData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x30a0f90 VA: 0x75956b8f90
	public Void RefreshData() { }
	// RVA: 0x30ab950 VA: 0x75956c3950
	public Void .ctor(Object param) { }
}
```