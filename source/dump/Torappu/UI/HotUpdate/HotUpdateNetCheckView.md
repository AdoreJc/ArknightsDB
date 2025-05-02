# HotUpdateNetCheckView

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `Text _textInfo`

- `Text _textTitle`

- `Action m_onDialogClosed`


## Methods

- `Void EventOnCopyClicked()`

- `Void EventOnCloseClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdateNetCheckView : UICustomDialog`1, IHotfixable
{
	private Text _textInfo; // 0x40
	private Text _textTitle; // 0x48
	private Action m_onDialogClosed; // 0x50
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_EventOnCopyClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x27c9058 VA: 0x7594de1058
	protected override Void OnRender(Options options) { }
	// RVA: 0x27c9290 VA: 0x7594de1290
	public Void EventOnCopyClicked() { }
	// RVA: 0x27c9360 VA: 0x7594de1360
	public Void EventOnCloseClicked() { }
	// RVA: 0x27c93e4 VA: 0x7594de13e4
	public Void .ctor() { }
}
```