# RecruitSpecialGachaUpCharListButtonView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `GameObject _panelBtnConfirm`

- `GameObject _panelBtnConfirmDisable`

- `UICompDialogFinder m_dialogFinder`


## Methods

- `Void EventOnConfirmBtnClicked()`

- `Void EventOnCancelBtnClicked()`

- `Void EventOnIntroBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialGachaUpCharListButtonView : DataBinder`1, IHotfixable
{
	private GameObject _panelBtnConfirm; // 0x20
	private GameObject _panelBtnConfirmDisable; // 0x28
	private UICompDialogFinder m_dialogFinder; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnConfirmBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnCancelBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnIntroBtnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2701078 VA: 0x7594d19078
	public override Void OnValueChanged(RecruitSpecialGachaUpCharListProperty property) { }
	// RVA: 0x2701380 VA: 0x7594d19380
	public Void EventOnConfirmBtnClicked() { }
	// RVA: 0x2701424 VA: 0x7594d19424
	public Void EventOnCancelBtnClicked() { }
	// RVA: 0x27014c8 VA: 0x7594d194c8
	public Void EventOnIntroBtnClicked() { }
	// RVA: 0x270156c VA: 0x7594d1956c
	public Void .ctor() { }
}
```