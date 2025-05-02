# XDLoginSwitchAccountPlugin

**Namespace:** `XDSDK`


## Fields

- `Action m_onLogin`

- `Action m_onSwitchAccount`


## Methods

- `Void Init(InjectSwitchAccountOptions)`

- `Void EventOnLoginClicked()`

- `Void EventOnSwitchAccountClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XDSDK
public class XDLoginSwitchAccountPlugin : MonoBehaviour, IHotfixable
{
	private Action m_onLogin; // 0x18
	private Action m_onSwitchAccount; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_EventOnLoginClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnSwitchAccountClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2584ebc VA: 0x7594b9cebc
	public Void Init(InjectSwitchAccountOptions options) { }
	// RVA: 0x2589810 VA: 0x7594ba1810
	public Void EventOnLoginClicked() { }
	// RVA: 0x25898a0 VA: 0x7594ba18a0
	public Void EventOnSwitchAccountClicked() { }
	// RVA: 0x2589930 VA: 0x7594ba1930
	public Void .ctor() { }
}
```