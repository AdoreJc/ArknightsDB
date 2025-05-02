# CarvingDragContext

**Namespace:** ` `


## Fields

- `CarvingBoardView m_closure`

- `CarvingDragStatus m_carvingDragStatus`

- `RectTransform m_handAreaRect`


## Methods

- `Void SetSlots(List`1)`

- `Void _CalculateBounds()`

- `Void _OnDragEndOnSlot()`

- `Void _OnDragEnd()`

- `RectTransform <>xLuaBaseProxy_GetTokenInst(RectTransform, Vector2, ValueBundle)`

- `Boolean <>xLuaBaseProxy_InitDragContextInternal(ValueBundle)`

- `Boolean <>xLuaBaseProxy_UpdateDragContextInternal()`

- `Void <>xLuaBaseProxy_ClearDragContextInternal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CarvingDragContext : DragWithTokenContext
{
	private CarvingBoardView m_closure; // 0x28
	private CarvingDragStatus m_carvingDragStatus; // 0x30
	private List`1 m_slots; // 0x58
	private RectTransform m_handAreaRect; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetSlots; // 0x8
	private static DelegateBridge __Hotfix0_GetTokenInst; // 0x10
	private static DelegateBridge __Hotfix0_InitDragContextInternal; // 0x18
	private static DelegateBridge __Hotfix0_UpdateDragContextInternal; // 0x20
	private static DelegateBridge __Hotfix0_ClearDragContextInternal; // 0x28
	private static DelegateBridge __Hotfix0__CalculateBounds; // 0x30
	private static DelegateBridge __Hotfix0__OnDragEndOnSlot; // 0x38
	private static DelegateBridge __Hotfix0__OnDragEnd; // 0x40


	// RVA: 0x2da0cf4 VA: 0x75953b8cf4
	public Void .ctor(CarvingBoardView closure, RectTransform handAreaRect) { }
	// RVA: 0x2da0efc VA: 0x75953b8efc
	public Void SetSlots(List`1 carvingSlots) { }
	// RVA: 0x2da1ad4 VA: 0x75953b9ad4
	protected override RectTransform GetTokenInst(RectTransform tokenContainer, Vector2 touchPos, ValueBundle param) { }
	// RVA: 0x2da1d54 VA: 0x75953b9d54
	protected override Boolean InitDragContextInternal(ValueBundle param) { }
	// RVA: 0x2da2314 VA: 0x75953ba314
	protected override Boolean UpdateDragContextInternal() { }
	// RVA: 0x2da2474 VA: 0x75953ba474
	protected override Void ClearDragContextInternal() { }
	// RVA: 0x2da1fb8 VA: 0x75953b9fb8
	private Void _CalculateBounds() { }
	// RVA: 0x2da2598 VA: 0x75953ba598
	private Void _OnDragEndOnSlot() { }
	// RVA: 0x2da2748 VA: 0x75953ba748
	private Void _OnDragEnd() { }
	// RVA: 0x2da2848 VA: 0x75953ba848
	private RectTransform <>xLuaBaseProxy_GetTokenInst(RectTransform P0, Vector2 P1, ValueBundle P2) { }
	// RVA: 0x2da2870 VA: 0x75953ba870
	private Boolean <>xLuaBaseProxy_InitDragContextInternal(ValueBundle P0) { }
	// RVA: 0x2da289c VA: 0x75953ba89c
	private Boolean <>xLuaBaseProxy_UpdateDragContextInternal() { }
	// RVA: 0x2da28a4 VA: 0x75953ba8a4
	private Void <>xLuaBaseProxy_ClearDragContextInternal() { }
}
```