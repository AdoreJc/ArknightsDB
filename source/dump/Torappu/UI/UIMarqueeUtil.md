# UIMarqueeUtil

**Namespace:** `Torappu.UI`


## Fields

- `UIMarqueeHandler m_marqueeHandler`

- `IEnumerator m_showCoroutine`


## Methods

- `Void _OnSceneChanged(String, String)`

- `Void OnRegister()`

- `Void _OnCoroutineClose()`

- `Void _OnHandlerMsg(UpdateSubMsg)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIMarqueeUtil : Singleton`1
{
	private List`1 m_centers; // 0x10
	private UIMarqueeHandler m_marqueeHandler; // 0x18
	private IEnumerator m_showCoroutine; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__OnSceneChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnRegister; // 0x10
	private static DelegateBridge __Hotfix0__OnCoroutineClose; // 0x18
	private static DelegateBridge __Hotfix0__OnHandlerMsg; // 0x20


	// RVA: 0x21059cc VA: 0x759471d9cc
	private Void .ctor() { }
	// RVA: 0x2105a98 VA: 0x759471da98
	private Void _OnSceneChanged(String fromSceneName, String toSceneName) { }
	// RVA: 0x2105cb4 VA: 0x759471dcb4
	public Void OnRegister() { }
	// RVA: 0x2106018 VA: 0x759471e018
	private Void _OnCoroutineClose() { }
	// RVA: 0x21060f4 VA: 0x759471e0f4
	private Void _OnHandlerMsg(UpdateSubMsg msg) { }
}
```