# LoginNativeLicense

**Namespace:** `Torappu.UI.Login`


## Fields

- `Boolean m_isLicenseInvoking`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Boolean IsInvoking()`

- `Void InvokeLicense(Callback)`

- `Void _HookAlertNativeLicenseDialog()`

- `Void Dispose()`

- `Void _EventOnLicenseRetMessage(NativeLicenseRet)`

- `Void <_HookAlertNativeLicenseDialog>b__9_0()`

- `Void <_HookAlertNativeLicenseDialog>b__9_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Login
public class LoginNativeLicense : Singleton`1, IDisposable
{
	private HashSet`1 m_callbacks; // 0x10
	private Boolean m_isLicenseInvoking; // 0x18
	private Boolean m_isInited; // 0x19
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_IsInvoking; // 0x10
	private static DelegateBridge __Hotfix0_InvokeLicense; // 0x18
	private static DelegateBridge __Hotfix0__HookAlertNativeLicenseDialog; // 0x20
	private static DelegateBridge __Hotfix0_Dispose; // 0x28
	private static DelegateBridge __Hotfix0__CreateInvokeParam; // 0x30
	private static DelegateBridge __Hotfix0_UseNativeLicense; // 0x38
	private static DelegateBridge __Hotfix0_ShowLicense4Display; // 0x40
	private static DelegateBridge __Hotfix0__EventOnLicenseRetMessage; // 0x48


	// RVA: 0x27b1d9c VA: 0x7594dc9d9c
	private Void .ctor() { }
	// RVA: 0x27b1e80 VA: 0x7594dc9e80
	private Void _InitIfNot() { }
	// RVA: 0x27b1fe4 VA: 0x7594dc9fe4
	public Boolean IsInvoking() { }
	// RVA: 0x27b204c VA: 0x7594dca04c
	public Void InvokeLicense(Callback callback) { }
	// RVA: 0x27b2154 VA: 0x7594dca154
	private Void _HookAlertNativeLicenseDialog() { }
	// RVA: 0x27b24c0 VA: 0x7594dca4c0
	public Void Dispose() { }
	// RVA: 0x27b2368 VA: 0x7594dca368
	private static String _CreateInvokeParam() { }
	// RVA: 0x27b16a8 VA: 0x7594dc96a8
	public static Boolean UseNativeLicense() { }
	// RVA: 0x27b25a4 VA: 0x7594dca5a4
	public static Void ShowLicense4Display() { }
	// RVA: 0x27b263c VA: 0x7594dca63c
	private Void _EventOnLicenseRetMessage(NativeLicenseRet licenseRet) { }
	// RVA: 0x27b29dc VA: 0x7594dca9dc
	private Void <_HookAlertNativeLicenseDialog>b__9_0() { }
	// RVA: 0x27b2a3c VA: 0x7594dcaa3c
	private Void <_HookAlertNativeLicenseDialog>b__9_1() { }
}
```