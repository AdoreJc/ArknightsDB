# UIJoystickController

**Namespace:** `Torappu.UI`


## Fields

- `Component m_host`

- `String m_joystickName`

- `Action m_onDragStop`

- `TickFunction m_tickFunction`

- `PointerEventData m_pendingPointerDownEventData`

- `PointerEventData m_dragPointerDownEventData`


## Properties

- `Boolean isDragging`


## Methods

- `Boolean get_isDragging()`

- `Void Start(String, Action)`

- `Void StartDrag(PointerEventData)`

- `Void SetJoystickActive(Boolean)`

- `Void Tick()`

- `ETCJoystick _GetValidJoystick()`

- `Void _TickForPendingPointDown()`

- `Void _BeginDrag(PointerEventData)`

- `Void _TriggerJoystickOnDrug()`

- `Void _TriggerJoystickPointerUp(PointerEventData)`

- `Void _TickDrag()`

- `Void _StopDrag()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIJoystickController : IHotfixable
{
	private Component m_host; // 0x10
	private String m_joystickName; // 0x18
	private Action m_onDragStop; // 0x20
	private TickFunction m_tickFunction; // 0x28
	private PointerEventData m_pendingPointerDownEventData; // 0x30
	private PointerEventData m_dragPointerDownEventData; // 0x38
	private static DelegateBridge __Hotfix0_get_isDragging; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge _c__Hotfix1_ctor; // 0x10
	private static DelegateBridge __Hotfix0_Start; // 0x18
	private static DelegateBridge __Hotfix0_StartDrag; // 0x20
	private static DelegateBridge __Hotfix0_SetJoystickActive; // 0x28
	private static DelegateBridge __Hotfix0_Tick; // 0x30
	private static DelegateBridge __Hotfix0__CreateYieldWaitForValid; // 0x38
	private static DelegateBridge __Hotfix0__GetValidJoystick; // 0x40
	private static DelegateBridge __Hotfix0__TickForPendingPointDown; // 0x48
	private static DelegateBridge __Hotfix0__BeginDrag; // 0x50
	private static DelegateBridge __Hotfix0__TriggerJoystickOnDrug; // 0x58
	private static DelegateBridge __Hotfix0__TriggerJoystickPointerUp; // 0x60
	private static DelegateBridge __Hotfix0__TickDrag; // 0x68
	private static DelegateBridge __Hotfix0__StopDrag; // 0x70

	public Boolean isDragging { get; }

	// RVA: 0x21953c8 VA: 0x75947ad3c8
	public Boolean get_isDragging() { }
	// RVA: 0x2195438 VA: 0x75947ad438
	private Void .ctor() { }
	// RVA: 0x2194d5c VA: 0x75947acd5c
	public Void .ctor(Component host) { }
	// RVA: 0x2194df0 VA: 0x75947acdf0
	public Void Start(String joystickName, Action onDragStop) { }
	// RVA: 0x2195298 VA: 0x75947ad298
	public Void StartDrag(PointerEventData eventData) { }
	// RVA: 0x21956ac VA: 0x75947ad6ac
	public Void SetJoystickActive(Boolean isActived) { }
	// RVA: 0x2194af4 VA: 0x75947acaf4
	public Void Tick() { }
	// RVA: 0x21954a8 VA: 0x75947ad4a8
	private Func`2 _CreateYieldWaitForValid(String joystickName) { }
	// RVA: 0x21957b4 VA: 0x75947ad7b4
	private ETCJoystick _GetValidJoystick() { }
	// RVA: 0x2195854 VA: 0x75947ad854
	private Void _TickForPendingPointDown() { }
	// RVA: 0x21955ac VA: 0x75947ad5ac
	private Void _BeginDrag(PointerEventData eventData) { }
	// RVA: 0x21959bc VA: 0x75947ad9bc
	private Void _TriggerJoystickOnDrug() { }
	// RVA: 0x2195a88 VA: 0x75947ada88
	private Void _TriggerJoystickPointerUp(PointerEventData eventData) { }
	// RVA: 0x21958f8 VA: 0x75947ad8f8
	private Void _TickDrag() { }
	// RVA: 0x2195b6c VA: 0x75947adb6c
	private Void _StopDrag() { }
}
```