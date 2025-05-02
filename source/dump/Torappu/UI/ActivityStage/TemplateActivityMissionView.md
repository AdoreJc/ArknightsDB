# TemplateActivityMissionView

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `Text _txtProgressCount`

- `TwoStateToggle _claimAllStateToggle`


## Methods

- `Void OnViewModelRefresh(TemplateActivityViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityMissionView : MonoBehaviour, IBaseActViewBinder, IHotfixable
{
	private const String FORMAT_PROGRESS_COUNT; // 0x0
	private Text _txtProgressCount; // 0x18
	private TwoStateToggle _claimAllStateToggle; // 0x20
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x30a9264 VA: 0x75956c1264
	public Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x30a93f4 VA: 0x75956c13f4
	public Void .ctor() { }
}
```