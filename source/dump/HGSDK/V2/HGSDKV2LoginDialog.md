# HGSDKV2LoginDialog

**Namespace:** `HGSDK.V2`


## Fields

- `GameObject _btnLogin`

- `GameObject _btnRegister`

- `GameObject _btnSwitchAccount`

- `GameObject _panelUserInfo`

- `Text _textName`

- `CanvasGroup _rootCanvasGroup`

- `Single _hideDuration`

- `Options m_options`

- `Boolean m_isShowingDialog`


## Methods

- `Void EventOnLogin()`

- `Void EventOnSwitchAccount()`

- `Void EventOnAnnounceClicked()`

- `Boolean _CheckIfLoginReady()`

- `Void _Login()`

- `Void _SwitchAccount()`

- `Void _LoginImpl(Int32, String)`

- `Void _OnBackPressed()`

- `Void <_OnBackPressed>b__19_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.V2
public class HGSDKV2LoginDialog : UICustomDialog`1
{
	private GameObject _btnLogin; // 0x40
	private GameObject _btnRegister; // 0x48
	private GameObject _btnSwitchAccount; // 0x50
	private GameObject _panelUserInfo; // 0x58
	private Text _textName; // 0x60
	private CanvasGroup _rootCanvasGroup; // 0x68
	private Single _hideDuration; // 0x70
	private Options m_options; // 0x78
	private Boolean m_isShowingDialog; // 0x80
	private static DelegateBridge __Hotfix0_GenerateShowTween; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_EventOnLogin; // 0x10
	private static DelegateBridge __Hotfix0_EventOnSwitchAccount; // 0x18
	private static DelegateBridge __Hotfix0_EventOnAnnounceClicked; // 0x20
	private static DelegateBridge __Hotfix0__CheckIfLoginReady; // 0x28
	private static DelegateBridge __Hotfix0__Login; // 0x30
	private static DelegateBridge __Hotfix0__SwitchAccount; // 0x38
	private static DelegateBridge __Hotfix0__LoginImpl; // 0x40
	private static DelegateBridge __Hotfix0__OnBackPressed; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2f2fc8c VA: 0x7595547c8c
	protected override UISwitchTween GenerateShowTween() { }
	// RVA: 0x2f2fd44 VA: 0x7595547d44
	protected override Void OnRender(Options options) { }
	// RVA: 0x2f2ff14 VA: 0x7595547f14
	public Void EventOnLogin() { }
	// RVA: 0x2f30088 VA: 0x7595548088
	public Void EventOnSwitchAccount() { }
	// RVA: 0x2f3017c VA: 0x759554817c
	public Void EventOnAnnounceClicked() { }
	// RVA: 0x2f30008 VA: 0x7595548008
	private Boolean _CheckIfLoginReady() { }
	// RVA: 0x2f30204 VA: 0x7595548204
	private Void _Login() { }
	// RVA: 0x2f30458 VA: 0x7595548458
	private Void _SwitchAccount() { }
	// RVA: 0x2f30294 VA: 0x7595548294
	private Void _LoginImpl(Int32 type, String phoneNum) { }
	// RVA: 0x2f304c8 VA: 0x75955484c8
	private Void _OnBackPressed() { }
	// RVA: 0x2f30640 VA: 0x7595548640
	public Void .ctor() { }
	// RVA: 0x2f306d8 VA: 0x75955486d8
	private Void <_OnBackPressed>b__19_0() { }
}
```