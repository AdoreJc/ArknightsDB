# LoginNamingState

**Namespace:** `Torappu.UI.Login`


## Fields

- `InputField _playerNameInput`

- `LoginServiceLicenseView _licenseView`

- `Text _confirmButtonText`

- `Boolean m_isAgreementPassed`


## Methods

- `Void _DoInGameLicenseLogics()`

- `Void OnConfirmClicked()`

- `Void Awake()`

- `Void <_DoInGameLicenseLogics>b__6_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Login
public class LoginNamingState : State
{
	private InputField _playerNameInput; // 0x50
	private LoginServiceLicenseView _licenseView; // 0x58
	private Text _confirmButtonText; // 0x60
	private Boolean m_isAgreementPassed; // 0x68
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__DoInGameLicenseLogics; // 0x10
	private static DelegateBridge __Hotfix0_OnConfirmClicked; // 0x18
	private static DelegateBridge __Hotfix0_Awake; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x27b1324 VA: 0x7594dc9324
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27b1388 VA: 0x7594dc9388
	protected override Void OnEnter() { }
	// RVA: 0x27b13fc VA: 0x7594dc93fc
	private Void _DoInGameLicenseLogics() { }
	// RVA: 0x27b1748 VA: 0x7594dc9748
	public Void OnConfirmClicked() { }
	// RVA: 0x27b1ad0 VA: 0x7594dc9ad0
	private Void Awake() { }
	// RVA: 0x27b1c88 VA: 0x7594dc9c88
	public Void .ctor() { }
	// RVA: 0x27b1cf8 VA: 0x7594dc9cf8
	private Void <_DoInGameLicenseLogics>b__6_0() { }
	// RVA: 0x27b1d18 VA: 0x7594dc9d18
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```