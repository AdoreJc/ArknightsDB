# QuickPlayKnownNotifyView

**Namespace:** `Torappu.AVG`


## Fields

- `Text _text`

- `Text _btnText`

- `GameObject _knownBtn`

- `CanvasGroup _alphaHandler`

- `Vector2 _showPos`

- `Vector2 _hidePos`

- `Single _toastDuration`

- `UISwitchTween m_switchTween`


## Methods

- `Void OnReadToastClick()`

- `UISwitchTween GetSwitchTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class QuickPlayKnownNotifyView : UINotifyView`1, IFloatNotifyView
{
	private const String QUICK_PLAY_TOAST_SIG; // 0x0
	private Text _text; // 0x30
	private Text _btnText; // 0x38
	private GameObject _knownBtn; // 0x40
	private CanvasGroup _alphaHandler; // 0x48
	private Vector2 _showPos; // 0x50
	private Vector2 _hidePos; // 0x58
	private Single _toastDuration; // 0x60
	private UISwitchTween m_switchTween; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnReadToastClick; // 0x8
	private static DelegateBridge __Hotfix0_GetSwitchTween; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3e92240 VA: 0x75964aa240
	protected override Void Render(Param param) { }
	// RVA: 0x3e92328 VA: 0x75964aa328
	public Void OnReadToastClick() { }
	// RVA: 0x3e92514 VA: 0x75964aa514
	public UISwitchTween GetSwitchTween() { }
	// RVA: 0x3e92640 VA: 0x75964aa640
	public Void .ctor() { }
}
```