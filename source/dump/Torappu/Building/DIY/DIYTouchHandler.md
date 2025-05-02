# DIYTouchHandler

**Namespace:** `Torappu.Building.DIY`


## Fields

- `BaseRaycaster _raycaster`

- `Camera _targetCamera`

- `Single _dragThreshold`

- `String _advancedLayer`

- `Boolean _useHolderAxis`

- `Boolean _useFixedThreshold`

- `IFurnitureController m_currentHolderController`

- `Vector3 m_dragOriginPosition`

- `Vector2 m_dragOriginPosition2Screen`

- `GameObject m_currentDragOrigin`

- `Vector2 m_moveFactor`

- `Vector2 m_moveDragThreshold`

- `DragState m_dragState`

- `Boolean m_dragging`

- `Vector2 m_emptyDragOrigin`

- `RaycastResult m_CurrentPointResult`

- `Single m_CurrentPointWaitTime`

- `Vector2 m_CurrentPointOriginOffset`

- `Boolean m_CurrentPointHasBegin`

- `Boolean m_CurrentPointHasInterrupt`

- `Single pointWaitBeginTime`

- `Single pointWaitStartTime`

- `Boolean selectImmediatelyWhenSelected`

- `Boolean canDragOutsideWhenWait`

- `Action targetPointEmpty`


## Methods

- `Void add_targetPointEmpty(Action)`

- `Void remove_targetPointEmpty(Action)`

- `Void add_targetDragEmpty(Action`1)`

- `Void remove_targetDragEmpty(Action`1)`

- `Void add_targetBeginDrag(Action`2)`

- `Void remove_targetBeginDrag(Action`2)`

- `Void add_targetStartDrag(Action`1)`

- `Void remove_targetStartDrag(Action`1)`

- `Void add_targetEndDrag(Action`1)`

- `Void remove_targetEndDrag(Action`1)`

- `Void add_targetDragged(Action`3)`

- `Void remove_targetDragged(Action`3)`

- `Void add_indicatorButtonPressed(Action`1)`

- `Void remove_indicatorButtonPressed(Action`1)`

- `Void OnPointerUp(PointerEventData)`

- `Void OnPointerDown(PointerEventData)`

- `Void Update()`

- `Void _TargetBeginDrag()`

- `Void RegisterControllerManually(IFurnitureController)`

- `Void UnRegisterControllerManually()`

- `Void _TargetDragImmediately(PointerEventData)`

- `Void _TargetStartDrag()`

- `Void _TargetEndDrag()`

- `Void _TargetStopDrag()`

- `Void _RefreshCurrentHolderController()`

- `Void _RefreshMoveFactor()`

- `Boolean DragFurniture(PointerEventData)`

- `Void OnDrag(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class DIYTouchHandler : MonoBehaviour, IPointerUpHandler, IEventSystemHandler, IPointerDownHandler, IDragHandler, IHotfixable
{
	private BaseRaycaster _raycaster; // 0x18
	private Camera _targetCamera; // 0x20
	private Single _dragThreshold; // 0x28
	private String _advancedLayer; // 0x30
	private Boolean _useHolderAxis; // 0x38
	private Boolean _useFixedThreshold; // 0x39
	private IFurnitureController m_currentHolderController; // 0x40
	private Vector3 m_dragOriginPosition; // 0x48
	private Vector2 m_dragOriginPosition2Screen; // 0x54
	private GameObject m_currentDragOrigin; // 0x60
	private Vector2 m_moveFactor; // 0x68
	private Vector2 m_moveDragThreshold; // 0x70
	private DragState m_dragState; // 0x78
	private Boolean m_dragging; // 0x7c
	private Vector2 m_emptyDragOrigin; // 0x80
	private List`1 m_pointResult; // 0x88
	private RaycastResult m_CurrentPointResult; // 0x90
	private Single m_CurrentPointWaitTime; // 0xe0
	private Vector2 m_CurrentPointOriginOffset; // 0xe4
	private Boolean m_CurrentPointHasBegin; // 0xec
	private Boolean m_CurrentPointHasInterrupt; // 0xed
	private Single pointWaitBeginTime; // 0xf0
	private Single pointWaitStartTime; // 0xf4
	private Boolean selectImmediatelyWhenSelected; // 0xf8
	private Boolean canDragOutsideWhenWait; // 0xf9
	private Action targetPointEmpty; // 0x100
	private Action`1 targetDragEmpty; // 0x108
	private Action`2 targetBeginDrag; // 0x110
	private Action`1 targetStartDrag; // 0x118
	private Action`1 targetEndDrag; // 0x120
	private Action`3 targetDragged; // 0x128
	private Action`1 indicatorButtonPressed; // 0x130
	private static DelegateBridge __Hotfix0_add_targetPointEmpty; // 0x0
	private static DelegateBridge __Hotfix0_remove_targetPointEmpty; // 0x8
	private static DelegateBridge __Hotfix0_add_targetDragEmpty; // 0x10
	private static DelegateBridge __Hotfix0_remove_targetDragEmpty; // 0x18
	private static DelegateBridge __Hotfix0_add_targetBeginDrag; // 0x20
	private static DelegateBridge __Hotfix0_remove_targetBeginDrag; // 0x28
	private static DelegateBridge __Hotfix0_add_targetStartDrag; // 0x30
	private static DelegateBridge __Hotfix0_remove_targetStartDrag; // 0x38
	private static DelegateBridge __Hotfix0_add_targetEndDrag; // 0x40
	private static DelegateBridge __Hotfix0_remove_targetEndDrag; // 0x48
	private static DelegateBridge __Hotfix0_add_targetDragged; // 0x50
	private static DelegateBridge __Hotfix0_remove_targetDragged; // 0x58
	private static DelegateBridge __Hotfix0_add_indicatorButtonPressed; // 0x60
	private static DelegateBridge __Hotfix0_remove_indicatorButtonPressed; // 0x68
	private static DelegateBridge __Hotfix0_OnPointerUp; // 0x70
	private static DelegateBridge __Hotfix0_OnPointerDown; // 0x78
	private static DelegateBridge __Hotfix0_Update; // 0x80
	private static DelegateBridge __Hotfix0__TargetBeginDrag; // 0x88
	private static DelegateBridge __Hotfix0_RegisterControllerManually; // 0x90
	private static DelegateBridge __Hotfix0_UnRegisterControllerManually; // 0x98
	private static DelegateBridge __Hotfix0__TargetDragImmediately; // 0xa0
	private static DelegateBridge __Hotfix0__TargetStartDrag; // 0xa8
	private static DelegateBridge __Hotfix0__TargetEndDrag; // 0xb0
	private static DelegateBridge __Hotfix0__TargetStopDrag; // 0xb8
	private static DelegateBridge __Hotfix0__RefreshCurrentHolderController; // 0xc0
	private static DelegateBridge __Hotfix0__RefreshMoveFactor; // 0xc8
	private static DelegateBridge __Hotfix0_DragFurniture; // 0xd0
	private static DelegateBridge __Hotfix0_OnDrag; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe0


	// RVA: 0x37e4ec8 VA: 0x7595dfcec8
	public Void add_targetPointEmpty(Action value) { }
	// RVA: 0x37e4fa8 VA: 0x7595dfcfa8
	public Void remove_targetPointEmpty(Action value) { }
	// RVA: 0x37e5088 VA: 0x7595dfd088
	public Void add_targetDragEmpty(Action`1 value) { }
	// RVA: 0x37e5180 VA: 0x7595dfd180
	public Void remove_targetDragEmpty(Action`1 value) { }
	// RVA: 0x37e5278 VA: 0x7595dfd278
	public Void add_targetBeginDrag(Action`2 value) { }
	// RVA: 0x37e5370 VA: 0x7595dfd370
	public Void remove_targetBeginDrag(Action`2 value) { }
	// RVA: 0x37e5468 VA: 0x7595dfd468
	public Void add_targetStartDrag(Action`1 value) { }
	// RVA: 0x37e5560 VA: 0x7595dfd560
	public Void remove_targetStartDrag(Action`1 value) { }
	// RVA: 0x37e5658 VA: 0x7595dfd658
	public Void add_targetEndDrag(Action`1 value) { }
	// RVA: 0x37e5750 VA: 0x7595dfd750
	public Void remove_targetEndDrag(Action`1 value) { }
	// RVA: 0x37e5848 VA: 0x7595dfd848
	public Void add_targetDragged(Action`3 value) { }
	// RVA: 0x37e5940 VA: 0x7595dfd940
	public Void remove_targetDragged(Action`3 value) { }
	// RVA: 0x37e5a38 VA: 0x7595dfda38
	public Void add_indicatorButtonPressed(Action`1 value) { }
	// RVA: 0x37e5b30 VA: 0x7595dfdb30
	public Void remove_indicatorButtonPressed(Action`1 value) { }
	// RVA: 0x37e5c28 VA: 0x7595dfdc28
	public Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x37e5fec VA: 0x7595dfdfec
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x37e6c68 VA: 0x7595dfec68
	private Void Update() { }
	// RVA: 0x37e5ef8 VA: 0x7595dfdef8
	private Void _TargetBeginDrag() { }
	// RVA: 0x37e71f8 VA: 0x7595dff1f8
	public Void RegisterControllerManually(IFurnitureController controller) { }
	// RVA: 0x37e727c VA: 0x7595dff27c
	public Void UnRegisterControllerManually() { }
	// RVA: 0x37e6ae4 VA: 0x7595dfeae4
	private Void _TargetDragImmediately(PointerEventData eventData) { }
	// RVA: 0x37e6d48 VA: 0x7595dfed48
	private Void _TargetStartDrag() { }
	// RVA: 0x37e5dc4 VA: 0x7595dfddc4
	private Void _TargetEndDrag() { }
	// RVA: 0x37e5e58 VA: 0x7595dfde58
	private Void _TargetStopDrag() { }
	// RVA: 0x37e6de4 VA: 0x7595dfede4
	private Void _RefreshCurrentHolderController() { }
	// RVA: 0x37e6ee8 VA: 0x7595dfeee8
	private Void _RefreshMoveFactor() { }
	// RVA: 0x37e72f8 VA: 0x7595dff2f8
	private Boolean DragFurniture(PointerEventData eventData) { }
	// RVA: 0x37e7ad4 VA: 0x7595dffad4
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x37e7de4 VA: 0x7595dffde4
	public Void .ctor() { }
}
```