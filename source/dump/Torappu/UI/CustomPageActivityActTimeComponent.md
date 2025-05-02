# CustomPageActivityActTimeComponent

**Namespace:** `Torappu.UI`


## Fields

- `AbstractStageTime _stageTime`

- `AbstractRemainTime _remainTime`

- `Text _endTime`

- `String _param`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CustomPageActivityActTimeComponent : CustomPageActivityComponent
{
	private AbstractStageTime _stageTime; // 0x20
	private AbstractRemainTime _remainTime; // 0x28
	private Text _endTime; // 0x30
	private String _param; // 0x38
	private static DelegateBridge __Hotfix0_get_param; // 0x0
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override String param { get; }

	// RVA: 0x22699e8 VA: 0x75948819e8
	public override String get_param() { }
	// RVA: 0x2269a50 VA: 0x7594881a50
	public override Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x2269e60 VA: 0x7594881e60
	public Void .ctor() { }
}
```