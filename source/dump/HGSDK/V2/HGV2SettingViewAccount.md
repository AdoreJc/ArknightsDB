# HGV2SettingViewAccount

**Namespace:** `HGSDK.V2`


## Fields

- `HGSDKV2 m_sdk`

- `Boolean m_listenToNativeUnbindGrant`


## Methods

- `Void Render(HGSDKV2)`

- `Void EventLogout()`

- `Void EventShowAgreement()`

- `Void EventOnUnbindGrant()`

- `Void _OnNativeUnbindGrantRet(UnbindGrantMessage)`

- `Void OnDestroy()`

- `Void _InvokeNativeUnbindGrant()`

- `Void _DoLogout()`

- `Void <EventLogout>b__3_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.V2
public class HGV2SettingViewAccount : MonoBehaviour, IHotfixable
{
	private HGSDKV2 m_sdk; // 0x18
	private Boolean m_listenToNativeUnbindGrant; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventLogout; // 0x8
	private static DelegateBridge __Hotfix0_EventShowAgreement; // 0x10
	private static DelegateBridge __Hotfix0_EventOnUnbindGrant; // 0x18
	private static DelegateBridge __Hotfix0__OnNativeUnbindGrantRet; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0__InvokeNativeUnbindGrant; // 0x30
	private static DelegateBridge __Hotfix0__DoLogout; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x354fb44 VA: 0x7595b67b44
	public Void Render(HGSDKV2 hgSDK) { }
	// RVA: 0x354fbc8 VA: 0x7595b67bc8
	public Void EventLogout() { }
	// RVA: 0x354fd60 VA: 0x7595b67d60
	public Void EventShowAgreement() { }
	// RVA: 0x354fdec VA: 0x7595b67dec
	public Void EventOnUnbindGrant() { }
	// RVA: 0x3550044 VA: 0x7595b68044
	private Void _OnNativeUnbindGrantRet(UnbindGrantMessage msg) { }
	// RVA: 0x3550168 VA: 0x7595b68168
	private Void OnDestroy() { }
	// RVA: 0x354fe6c VA: 0x7595b67e6c
	private Void _InvokeNativeUnbindGrant() { }
	// RVA: 0x35500dc VA: 0x7595b680dc
	private Void _DoLogout() { }
	// RVA: 0x3550214 VA: 0x7595b68214
	public Void .ctor() { }
	// RVA: 0x3550284 VA: 0x7595b68284
	private Void <EventLogout>b__3_0() { }
}
```