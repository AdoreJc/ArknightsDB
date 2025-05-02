# HGSettingViewAccount

**Namespace:** `HGSDK.UI`


## Fields

- `GameObject _accountPanel`

- `GameObject _unbindPanel`

- `Text _agreementText`

- `HGSDK m_sdk`

- `Boolean m_listenToNativeUnbindGrant`


## Methods

- `Void Render(HGSDK)`

- `Void EventChangePhone()`

- `Void EventChangePwd()`

- `Void EventShowAgreement()`

- `Void EventLogout()`

- `Void EventOnUnbindGrant()`

- `Void _OnNativeUnbindGrantRet(UnbindGrantMessage)`

- `Void OnDestroy()`

- `Void _UpdateAccountPanel()`

- `Void _InvokeNativeUnbindGrant()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class HGSettingViewAccount : MonoBehaviour, IHotfixable
{
	private GameObject _accountPanel; // 0x18
	private GameObject[] _subAccountPanels; // 0x20
	private GameObject _unbindPanel; // 0x28
	private Text _agreementText; // 0x30
	private HGSDK m_sdk; // 0x38
	private Boolean m_listenToNativeUnbindGrant; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventChangePhone; // 0x8
	private static DelegateBridge __Hotfix0_EventChangePwd; // 0x10
	private static DelegateBridge __Hotfix0_EventShowAgreement; // 0x18
	private static DelegateBridge __Hotfix0_EventLogout; // 0x20
	private static DelegateBridge __Hotfix0_EventOnUnbindGrant; // 0x28
	private static DelegateBridge __Hotfix0__OnNativeUnbindGrantRet; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge __Hotfix0__UpdateAccountPanel; // 0x40
	private static DelegateBridge __Hotfix0__InvokeNativeUnbindGrant; // 0x48
	private static DelegateBridge __Hotfix0__CheckIfShowAccount; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x3564568 VA: 0x7595b7c568
	public Void Render(HGSDK hgSDK) { }
	// RVA: 0x3564728 VA: 0x7595b7c728
	public Void EventChangePhone() { }
	// RVA: 0x35647b4 VA: 0x7595b7c7b4
	public Void EventChangePwd() { }
	// RVA: 0x3564840 VA: 0x7595b7c840
	public Void EventShowAgreement() { }
	// RVA: 0x35648cc VA: 0x7595b7c8cc
	public Void EventLogout() { }
	// RVA: 0x3564ac4 VA: 0x7595b7cac4
	public Void EventOnUnbindGrant() { }
	// RVA: 0x3564d50 VA: 0x7595b7cd50
	private Void _OnNativeUnbindGrantRet(UnbindGrantMessage msg) { }
	// RVA: 0x3564de8 VA: 0x7595b7cde8
	private Void OnDestroy() { }
	// RVA: 0x3564624 VA: 0x7595b7c624
	private Void _UpdateAccountPanel() { }
	// RVA: 0x3564b78 VA: 0x7595b7cb78
	private Void _InvokeNativeUnbindGrant() { }
	// RVA: 0x3564e94 VA: 0x7595b7ce94
	private static Boolean _CheckIfShowAccount() { }
	// RVA: 0x3564f40 VA: 0x7595b7cf40
	public Void .ctor() { }
}
```