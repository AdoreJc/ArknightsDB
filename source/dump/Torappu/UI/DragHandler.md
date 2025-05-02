# DragHandler

**Namespace:** `Torappu.UI`


## Fields

- `TContext m_dragContext`


## Properties

- `TContext dragContext`


## Methods

- `TContext get_dragContext()`

- `Void set_dragContext(TContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class DragHandler`1 : DragHandler
{
	private TContext m_dragContext; // 0x0
	private static DelegateBridge __Hotfix0_get_dragContext; // 0x0
	private static DelegateBridge __Hotfix0_set_dragContext; // 0x0
	private static DelegateBridge __Hotfix0_CreateDrag; // 0x0
	private static DelegateBridge __Hotfix0_UpdateDrag; // 0x0
	private static DelegateBridge __Hotfix0_ClearDrag; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0

	protected TContext dragContext { get; set; }

	// RVA: 0x VA: 0x0
	protected TContext get_dragContext() { }
	// RVA: 0x VA: 0x0
	public Void set_dragContext(TContext value) { }
	// RVA: 0x VA: 0x0
	protected sealed override Boolean CreateDrag(PointerEventData eventData, ValueBundle param) { }
	// RVA: 0x VA: 0x0
	protected sealed override Boolean UpdateDrag() { }
	// RVA: 0x VA: 0x0
	protected sealed override Void ClearDrag() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```