# SDKLoginStateReady

**Namespace:** `YostarSDK.UI`


## Fields

- `Text _userTitle`

- `Text _userAccount`

- `GameObject _panelUser`

- `Action m_latestLoginAction`


## Methods

- `Void OnAwakenBtnClicked()`

- `Void _LoginPreventAccountDeleted(Action)`

- `Void _OnAiriSDKLogin(LoginRet)`

- `Void <OnAwakenBtnClicked>b__7_0()`

- `Void <_OnAiriSDKLogin>b__9_0()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : YostarSDK.UI
public class SDKLoginStateReady : UIState
{
	private Text _userTitle; // 0x50
	private Text _userAccount; // 0x58
	private GameObject _panelUser; // 0x60
	private Action m_latestLoginAction; // 0x68
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnAwakenBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0__LoginPreventAccountDeleted; // 0x18
	private static DelegateBridge __Hotfix0__OnAiriSDKLogin; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override LoginState myState { get; }

	// RVA: 0x1b47110 VA: 0x759415f110
	public override LoginState get_myState() { }
	// RVA: 0x1b47178 VA: 0x759415f178
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1b47370 VA: 0x759415f370
	public Void OnAwakenBtnClicked() { }
	// RVA: 0x1b47440 VA: 0x759415f440
	private Void _LoginPreventAccountDeleted(Action loginAction) { }
	// RVA: 0x1b474ec VA: 0x759415f4ec
	private Void _OnAiriSDKLogin(LoginRet ret) { }
	// RVA: 0x1b47628 VA: 0x759415f628
	public Void .ctor() { }
	// RVA: 0x1b47694 VA: 0x759415f694
	private Void <OnAwakenBtnClicked>b__7_0() { }
	// RVA: 0x1b47748 VA: 0x759415f748
	private Void <_OnAiriSDKLogin>b__9_0() { }
	// RVA: 0x1b47764 VA: 0x759415f764
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```