# AppetizerTrace

**Namespace:** `Torappu.Appetizer`


## Fields

- `String m_HGLoginMethod`


## Methods

- `Void NotifyHGLoginWithPhone()`

- `Void NotifyHGLoginWithAccount()`

- `Void NotifyHGLoginWithGuest()`

- `Void NotifyHGLoginWithToken()`

- `Void LoginTrace()`

- `Void _DoTrace(Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Appetizer
public class AppetizerTrace : Singleton`1
{
	private String m_HGLoginMethod; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_NotifyHGLoginWithPhone; // 0x8
	private static DelegateBridge __Hotfix0_NotifyHGLoginWithAccount; // 0x10
	private static DelegateBridge __Hotfix0_NotifyHGLoginWithGuest; // 0x18
	private static DelegateBridge __Hotfix0_NotifyHGLoginWithToken; // 0x20
	private static DelegateBridge __Hotfix0_LoginTrace; // 0x28
	private static DelegateBridge __Hotfix0__DoTrace; // 0x30


	// RVA: 0x3eed3ac VA: 0x75965053ac
	private Void .ctor() { }
	// RVA: 0x3eed468 VA: 0x7596505468
	public Void NotifyHGLoginWithPhone() { }
	// RVA: 0x3eed4ec VA: 0x75965054ec
	public Void NotifyHGLoginWithAccount() { }
	// RVA: 0x3eed570 VA: 0x7596505570
	public Void NotifyHGLoginWithGuest() { }
	// RVA: 0x3eed5f4 VA: 0x75965055f4
	public Void NotifyHGLoginWithToken() { }
	// RVA: 0x3eed678 VA: 0x7596505678
	public Void LoginTrace() { }
	// RVA: 0x3eed948 VA: 0x7596505948
	private Void _DoTrace(Dictionary`2 dict) { }
}
```