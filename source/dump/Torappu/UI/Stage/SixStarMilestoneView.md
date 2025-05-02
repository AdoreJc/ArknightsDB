# SixStarMilestoneView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `SixStarMilestoneAdapter _adapter`

- `Text _textCurrPoint`

- `GameObject _panelClaimAll`

- `UICompDialogFinder m_finder`


## Methods

- `Void EventOnBackClicked()`

- `Void EventOnClaimAllClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarMilestoneView : DataBinder`1, IHotfixable
{
	private SixStarMilestoneAdapter _adapter; // 0x20
	private Text _textCurrPoint; // 0x28
	private GameObject _panelClaimAll; // 0x30
	private UICompDialogFinder m_finder; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClaimAllClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f4b12c VA: 0x759556312c
	public override Void OnValueChanged(SixStarMilestoneProperty property) { }
	// RVA: 0x2f4b240 VA: 0x7595563240
	public Void EventOnBackClicked() { }
	// RVA: 0x2f4b2e4 VA: 0x75955632e4
	public Void EventOnClaimAllClicked() { }
	// RVA: 0x2f4b388 VA: 0x7595563388
	public Void .ctor() { }
}
```