# LoginServiceLicenseView

**Namespace:** `Torappu.UI.Login`


## Fields

- `GameObject _content`

- `TwoStateToggle _licenseToggle`

- `TwoStateToggle _btnToggle`

- `UIUniWebView _webView`

- `Boolean m_isAgreed`

- `Action m_onAgreed`


## Methods

- `Void Show(Action)`

- `Void Hide()`

- `Void EventOnLicenseToggleClicked()`

- `Void EventOnNextBtnClicked()`

- `Void _SetToggle(Boolean)`

- `Void _OnAgreed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Login
public class LoginServiceLicenseView : MonoBehaviour, IHotfixable
{
	private GameObject _content; // 0x18
	private TwoStateToggle _licenseToggle; // 0x20
	private TwoStateToggle _btnToggle; // 0x28
	private UIUniWebView _webView; // 0x30
	private Boolean m_isAgreed; // 0x38
	private Action m_onAgreed; // 0x40
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0_EventOnLicenseToggleClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnNextBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0__SetToggle; // 0x20
	private static DelegateBridge __Hotfix0__OnAgreed; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x27b0610 VA: 0x7594dc8610
	public Void Show(Action onAgreed) { }
	// RVA: 0x27b3eac VA: 0x7594dcbeac
	public Void Hide() { }
	// RVA: 0x27b3f4c VA: 0x7594dcbf4c
	public Void EventOnLicenseToggleClicked() { }
	// RVA: 0x27b3fc0 VA: 0x7594dcbfc0
	public Void EventOnNextBtnClicked() { }
	// RVA: 0x27b3e00 VA: 0x7594dcbe00
	private Void _SetToggle(Boolean isActive) { }
	// RVA: 0x27b4044 VA: 0x7594dcc044
	private Void _OnAgreed() { }
	// RVA: 0x27b40d8 VA: 0x7594dcc0d8
	public Void .ctor() { }
}
```