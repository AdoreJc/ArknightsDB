# UIPortraitChooseCharButtonView

**Namespace:** `Torappu.UI.ChooseChar`


## Fields

- `TwoStateFadeSwitcher _confirmBtnSwitcher`

- `Int32 m_cachedSequence`

- `UICompDialogFinder m_dialogFinder`


## Methods

- `Void EventOnCancelBtnClicked()`

- `Void EventOnConfirmBtnClicked()`

- `Void EventOnClearBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChooseChar
public class UIPortraitChooseCharButtonView : DataBinder`1, IHotfixable
{
	private TwoStateFadeSwitcher _confirmBtnSwitcher; // 0x20
	private Int32 m_cachedSequence; // 0x28
	private UICompDialogFinder m_dialogFinder; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnCancelBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnConfirmBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClearBtnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2c3de44 VA: 0x7595255e44
	public override Void OnValueChanged(UIPortraitChooseCharProperty property) { }
	// RVA: 0x2c3dfb0 VA: 0x7595255fb0
	public Void EventOnCancelBtnClicked() { }
	// RVA: 0x2c3e054 VA: 0x7595256054
	public Void EventOnConfirmBtnClicked() { }
	// RVA: 0x2c3e0f8 VA: 0x75952560f8
	public Void EventOnClearBtnClicked() { }
	// RVA: 0x2c3e19c VA: 0x759525619c
	public Void .ctor() { }
}
```