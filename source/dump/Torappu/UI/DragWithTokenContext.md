# DragWithTokenContext

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform targetToken`

- `Vector2 targetStartPos`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class DragWithTokenContext : DragContext
{
	public RectTransform targetToken; // 0x18
	public Vector2 targetStartPos; // 0x20
	private static DelegateBridge __Hotfix0_InitDragContext; // 0x0
	private static DelegateBridge __Hotfix0_UpdateDragContext; // 0x8
	private static DelegateBridge __Hotfix0_ClearDragContext; // 0x10
	private static DelegateBridge __Hotfix0_InitDragContextInternal; // 0x18
	private static DelegateBridge __Hotfix0_UpdateDragContextInternal; // 0x20
	private static DelegateBridge __Hotfix0_ClearDragContextInternal; // 0x28
	private static DelegateBridge __Hotfix0_GetTokenInst; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x21c24f4 VA: 0x75947da4f4
	public sealed override Boolean InitDragContext(ValueBundle param) { }
	// RVA: 0x21c264c VA: 0x75947da64c
	public sealed override Boolean UpdateDragContext() { }
	// RVA: 0x21c2758 VA: 0x75947da758
	public sealed override Void ClearDragContext() { }
	// RVA: 0x21c2814 VA: 0x75947da814
	protected virtual Boolean InitDragContextInternal(ValueBundle param) { }
	// RVA: 0x21c289c VA: 0x75947da89c
	protected virtual Boolean UpdateDragContextInternal() { }
	// RVA: 0x21c2904 VA: 0x75947da904
	protected virtual Void ClearDragContextInternal() { }
	// RVA: 0x21c2968 VA: 0x75947da968
	protected virtual RectTransform GetTokenInst(RectTransform tokenContainer, Vector2 touchPos, ValueBundle param) { }
	// RVA: 0x21c2a04 VA: 0x75947daa04
	public Void .ctor() { }
}
```