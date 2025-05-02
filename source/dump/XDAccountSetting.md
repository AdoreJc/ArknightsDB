# XDAccountSetting

**Namespace:** ` `


## Fields

- `Action m_userCenter`

- `Action m_helpCenter`

- `Action m_loginOut`


## Methods

- `Void EventOnPlayerUserCenter()`

- `Void EventOnPlayerHelpCenter()`

- `Void EventOnPlayerQuit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class XDAccountSetting : MonoBehaviour, IHotfixable
{
	private Action m_userCenter; // 0x18
	private Action m_helpCenter; // 0x20
	private Action m_loginOut; // 0x28
	private static DelegateBridge __Hotfix0_EventOnPlayerUserCenter; // 0x0
	private static DelegateBridge __Hotfix0_EventOnPlayerHelpCenter; // 0x8
	private static DelegateBridge __Hotfix0_EventOnPlayerQuit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1b3b024 VA: 0x7594153024
	public Void EventOnPlayerUserCenter() { }
	// RVA: 0x1b3b254 VA: 0x7594153254
	public Void EventOnPlayerHelpCenter() { }
	// RVA: 0x1b3b484 VA: 0x7594153484
	public Void EventOnPlayerQuit() { }
	// RVA: 0x1b3b67c VA: 0x759415367c
	public Void .ctor() { }
}
```