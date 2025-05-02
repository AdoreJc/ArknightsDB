# U8SDKCallback

**Namespace:** `U8.SDK`


## Methods

- `Void OnInitSuc(String)`

- `Void OnInitFail(String)`

- `Void OnLoginSuc(String)`

- `Void OnLoginFail(String)`

- `Void OnLogout(String)`

- `Void OnSwitchAccount()`

- `Void OnPaySuc(String)`

- `Void OnPayFail(String)`

- `Void OnSDKError(String)`

- `Void OnExtraInfo(String)`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : U8.SDK
public class U8SDKCallback : MonoBehaviour
{
	private static U8SDKCallback m_instance; // 0x0
	private static Object m_lock; // 0x8


	// RVA: 0x67d5a10 VA: 0x7598deda10
	public static U8SDKCallback InitCallback() { }
	// RVA: 0x67e55a8 VA: 0x7598dfd5a8
	public Void OnInitSuc(String extConfigs) { }
	// RVA: 0x67e55d0 VA: 0x7598dfd5d0
	public Void OnInitFail(String info) { }
	// RVA: 0x67e55f8 VA: 0x7598dfd5f8
	public Void OnLoginSuc(String extension) { }
	// RVA: 0x67e5620 VA: 0x7598dfd620
	public Void OnLoginFail(String info) { }
	// RVA: 0x67e5648 VA: 0x7598dfd648
	public Void OnLogout(String info) { }
	// RVA: 0x67e5660 VA: 0x7598dfd660
	public Void OnSwitchAccount() { }
	// RVA: 0x67e5678 VA: 0x7598dfd678
	public Void OnPaySuc(String jsonData) { }
	// RVA: 0x67e5698 VA: 0x7598dfd698
	public Void OnPayFail(String failMsg) { }
	// RVA: 0x67e56b8 VA: 0x7598dfd6b8
	public Void OnSDKError(String jsonData) { }
	// RVA: 0x67e5744 VA: 0x7598dfd744
	public Void OnExtraInfo(String jsonData) { }
	// RVA: 0x67e57ac VA: 0x7598dfd7ac
	public Void .ctor() { }
	// RVA: 0x67e57b4 VA: 0x7598dfd7b4
	private static Void .cctor() { }
}
```