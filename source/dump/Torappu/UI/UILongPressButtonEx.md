# UILongPressButtonEx

**Namespace:** `Torappu.UI`


## Fields

- `Int32 _longPressThreshold`

- `Int32 _longPressInterval`

- `Boolean m_isPressing`

- `DateTime m_pressStartTime`

- `DateTime m_lastLongPressUpdateTime`

- `State m_state`

- `Action <onClick>k__BackingField`


## Properties

- `Boolean interactable`

- `Action onClick`


## Methods

- `Boolean get_interactable()`

- `Void set_interactable(Boolean)`

- `Action get_onClick()`

- `Void set_onClick(Action)`

- `Void set_onLongPress(Func`1)`

- `Void Update()`

- `Void _FinishPointDown()`

- `Void _UpdateLongPress()`

- `Void <>xLuaBaseProxy_OnPointerDown(PointerEventData)`

- `Void <>xLuaBaseProxy_OnPointerExit(PointerEventData)`

- `Void <>xLuaBaseProxy_OnPointerUp(PointerEventData)`

- `Void <>xLuaBaseProxy_OnDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UILongPressButtonEx : Selectable, IHotfixable
{
	private Int32 _longPressThreshold; // 0xf8
	private Int32 _longPressInterval; // 0xfc
	private Boolean m_isPressing; // 0x100
	private DateTime m_pressStartTime; // 0x108
	private DateTime m_lastLongPressUpdateTime; // 0x110
	private State m_state; // 0x118
	private Action <onClick>k__BackingField; // 0x120
	private Func`1 <onLongPress>k__BackingField; // 0x128
	private static DelegateBridge __Hotfix0_get_interactable; // 0x0
	private static DelegateBridge __Hotfix0_set_interactable; // 0x8
	private static DelegateBridge __Hotfix0_get_onClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onLongPress; // 0x20
	private static DelegateBridge __Hotfix0_set_onLongPress; // 0x28
	private static DelegateBridge __Hotfix0_OnPointerDown; // 0x30
	private static DelegateBridge __Hotfix0_OnPointerExit; // 0x38
	private static DelegateBridge __Hotfix0_OnPointerUp; // 0x40
	private static DelegateBridge __Hotfix0_Update; // 0x48
	private static DelegateBridge __Hotfix0_OnDisable; // 0x50
	private static DelegateBridge __Hotfix0__FinishPointDown; // 0x58
	private static DelegateBridge __Hotfix0__UpdateLongPress; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Boolean interactable { get; set; }
	public Action onClick { get; set; }
	public Func`1 onLongPress { get; set; }

	// RVA: 0x221a1d0 VA: 0x75948321d0
	public Boolean get_interactable() { }
	// RVA: 0x221a238 VA: 0x7594832238
	public Void set_interactable(Boolean value) { }
	// RVA: 0x221a3a0 VA: 0x75948323a0
	public Action get_onClick() { }
	// RVA: 0x221a408 VA: 0x7594832408
	public Void set_onClick(Action value) { }
	// RVA: 0x221a48c VA: 0x759483248c
	public Func`1 get_onLongPress() { }
	// RVA: 0x221a4f4 VA: 0x75948324f4
	public Void set_onLongPress(Func`1 value) { }
	// RVA: 0x221a578 VA: 0x7594832578
	public override Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x221a648 VA: 0x7594832648
	public override Void OnPointerExit(PointerEventData eventData) { }
	// RVA: 0x221a6f8 VA: 0x75948326f8
	public override Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x221a7c0 VA: 0x75948327c0
	private Void Update() { }
	// RVA: 0x221aa68 VA: 0x7594832a68
	protected override Void OnDisable() { }
	// RVA: 0x221a2f0 VA: 0x75948322f0
	private Void _FinishPointDown() { }
	// RVA: 0x221a988 VA: 0x7594832988
	private Void _UpdateLongPress() { }
	// RVA: 0x221aaf8 VA: 0x7594832af8
	public Void .ctor() { }
	// RVA: 0x221abd8 VA: 0x7594832bd8
	private Void <>xLuaBaseProxy_OnPointerDown(PointerEventData P0) { }
	// RVA: 0x221abe0 VA: 0x7594832be0
	private Void <>xLuaBaseProxy_OnPointerExit(PointerEventData P0) { }
	// RVA: 0x221abe8 VA: 0x7594832be8
	private Void <>xLuaBaseProxy_OnPointerUp(PointerEventData P0) { }
	// RVA: 0x221abf0 VA: 0x7594832bf0
	private Void <>xLuaBaseProxy_OnDisable() { }
}
```