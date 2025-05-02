# UIPageCoroutineHost

**Namespace:** `Torappu.UI`


## Fields

- `UIPage m_page`


## Methods

- `Coroutine StartCoroutine(IEnumerator)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPageCoroutineHost : ICoroutineHost, IHotfixable
{
	private UIPage m_page; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_StartCoroutine; // 0x8


	// RVA: 0x2225950 VA: 0x759483d950
	public Void .ctor(UIPage page) { }
	// RVA: 0x22259e4 VA: 0x759483d9e4
	public Coroutine StartCoroutine(IEnumerator routine) { }
}
```