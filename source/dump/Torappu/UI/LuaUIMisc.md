# LuaUIMisc

**Namespace:** `Torappu.UI`


## Fields

- `Action m_onConfirm`

- `Action m_onCancel`


## Methods

- `Void Dispose()`

- `Void _OnConfirm()`

- `Void _OnCancel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class LuaUIMisc : IDisposable, IHotfixable
{
	private Action m_onConfirm; // 0x10
	private Action m_onCancel; // 0x18
	private static DelegateBridge __Hotfix0_ShowGainedItems; // 0x0
	private static DelegateBridge __Hotfix0_OpenGuidebookExt; // 0x8
	private static DelegateBridge __Hotfix0_Dispose; // 0x10
	private static DelegateBridge __Hotfix0__OnConfirm; // 0x18
	private static DelegateBridge __Hotfix0__OnCancel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x21c79f8 VA: 0x75947df9f8
	public static LuaUIMisc ShowGainedItems(List`1 items, Style style, Action onConfirm) { }
	// RVA: 0x21c7bb4 VA: 0x75947dfbb4
	public static LuaUIMisc OpenGuidebookExt(String[] pageids, Int32 forceRead, Action onFinish) { }
	// RVA: 0x21c7cbc VA: 0x75947dfcbc
	public Void Dispose() { }
	// RVA: 0x21c7d3c VA: 0x75947dfd3c
	private Void _OnConfirm() { }
	// RVA: 0x21c7dc0 VA: 0x75947dfdc0
	private Void _OnCancel() { }
	// RVA: 0x21c7b44 VA: 0x75947dfb44
	public Void .ctor() { }
}
```