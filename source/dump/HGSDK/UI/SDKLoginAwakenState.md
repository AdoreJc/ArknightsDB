# SDKLoginAwakenState

**Namespace:** `HGSDK.UI`


## Fields

- `Text _userTitle`

- `Text _userAccount`

- `GameObject _userPanel`

- `GameObject _guestPanel`

- `Boolean m_isGuest`

- `String m_token`


## Methods

- `Void EventOnAwakenClicked()`

- `Void EventOnGuestUpgradeClicked()`

- `String _TryHidePhoneNumber(String)`

- `Boolean _BlockGuestLogin()`

- `Void <EventOnAwakenClicked>b__10_0(LoginResult)`

- `Void <EventOnAwakenClicked>b__10_1()`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKLoginAwakenState : UIState
{
	private const Int32 HIDDED_PHONE_NUMBER_STAR_NUM; // 0x0
	private Text _userTitle; // 0x58
	private Text _userAccount; // 0x60
	private GameObject _userPanel; // 0x68
	private GameObject _guestPanel; // 0x70
	private Boolean m_isGuest; // 0x78
	private String m_token; // 0x80
	private static DelegateBridge __Hotfix0_get_myState; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_EventOnAwakenClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnGuestUpgradeClicked; // 0x18
	private static DelegateBridge __Hotfix0__TryHidePhoneNumber; // 0x20
	private static DelegateBridge __Hotfix0__BlockGuestLogin; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override LoginState myState { get; }

	// RVA: 0x3554510 VA: 0x7595b6c510
	public override LoginState get_myState() { }
	// RVA: 0x3554578 VA: 0x7595b6c578
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x35548a4 VA: 0x7595b6c8a4
	public Void EventOnAwakenClicked() { }
	// RVA: 0x3554b3c VA: 0x7595b6cb3c
	public Void EventOnGuestUpgradeClicked() { }
	// RVA: 0x3554710 VA: 0x7595b6c710
	private String _TryHidePhoneNumber(String accountName) { }
	// RVA: 0x3554a2c VA: 0x7595b6ca2c
	private Boolean _BlockGuestLogin() { }
	// RVA: 0x3554ba8 VA: 0x7595b6cba8
	public Void .ctor() { }
	// RVA: 0x3554c38 VA: 0x7595b6cc38
	private Void <EventOnAwakenClicked>b__10_0(LoginResult result) { }
	// RVA: 0x3554c94 VA: 0x7595b6cc94
	private Void <EventOnAwakenClicked>b__10_1() { }
	// RVA: 0x3554c9c VA: 0x7595b6cc9c
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
}
```