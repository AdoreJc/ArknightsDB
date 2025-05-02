# UIStyleProvider

**Namespace:** `Torappu.UI`


## Fields

- `UIStyle m_style`


## Methods

- `Void Reset(UIStyle, Boolean)`

- `Void AddStyleListener(IUIStyleListener)`

- `Boolean RemoveStyleListener(IUIStyleListener)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIStyleProvider : MonoBehaviour, IHotfixable
{
	private UIStyle m_style; // 0x18
	private HashSet`1 m_listeners; // 0x20
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_AddStyleListener; // 0x8
	private static DelegateBridge __Hotfix0_RemoveStyleListener; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x21bfb78 VA: 0x75947d7b78
	public Void Reset(UIStyle style, Boolean force) { }
	// RVA: 0x21bfd34 VA: 0x75947d7d34
	public Void AddStyleListener(IUIStyleListener listener) { }
	// RVA: 0x21bfef8 VA: 0x75947d7ef8
	public Boolean RemoveStyleListener(IUIStyleListener listene) { }
	// RVA: 0x21bffa4 VA: 0x75947d7fa4
	public Void .ctor() { }
}
```