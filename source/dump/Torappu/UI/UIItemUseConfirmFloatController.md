# UIItemUseConfirmFloatController

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _floatHolder`

- `UIItemUseConfirmFloat m_floatInst`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _RenderConfirm(Int32, String, ItemType, String, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIItemUseConfirmFloatController : PageSingleComponent
{
	private RectTransform _floatHolder; // 0x20
	private UIItemUseConfirmFloat m_floatInst; // 0x28
	private Boolean m_isInited; // 0x30
	private static DelegateBridge __Hotfix0_RenderConfirmPanel; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RenderConfirm; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2194460 VA: 0x75947ac460
	public static Void RenderConfirmPanel(Int32 cost, String itemId, ItemType itemType, String confirmText, Action onConfirm) { }
	// RVA: 0x21946f8 VA: 0x75947ac6f8
	private Void _InitIfNot() { }
	// RVA: 0x21945cc VA: 0x75947ac5cc
	private Void _RenderConfirm(Int32 cost, String itemId, ItemType itemType, String confirmText, Action onConfirm) { }
	// RVA: 0x219486c VA: 0x75947ac86c
	public Void .ctor() { }
}
```