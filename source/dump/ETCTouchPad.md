# ETCTouchPad

**Namespace:** ` `


## Fields

- `OnMoveStartHandler onMoveStart`

- `OnMoveHandler onMove`

- `OnMoveSpeedHandler onMoveSpeed`

- `OnMoveEndHandler onMoveEnd`

- `OnTouchStartHandler onTouchStart`

- `OnTouchUPHandler onTouchUp`

- `OnDownUpHandler OnDownUp`

- `OnDownDownHandler OnDownDown`

- `OnDownLeftHandler OnDownLeft`

- `OnDownRightHandler OnDownRight`

- `OnDownUpHandler OnPressUp`

- `OnDownDownHandler OnPressDown`

- `OnDownLeftHandler OnPressLeft`

- `OnDownRightHandler OnPressRight`

- `ETCAxis axisX`

- `ETCAxis axisY`

- `Boolean isDPI`

- `Image cachedImage`

- `Vector2 tmpAxis`

- `Vector2 OldTmpAxis`

- `GameObject previousDargObject`

- `Boolean isOut`

- `Boolean isOnTouch`

- `Boolean cachedVisible`


## Methods

- `Void OnPointerEnter(PointerEventData)`

- `Void OnBeginDrag(PointerEventData)`

- `Void OnDrag(PointerEventData)`

- `Void OnPointerDown(PointerEventData)`

- `Void OnPointerUp(PointerEventData)`

- `Void OnPointerExit(PointerEventData)`

- `Void UpdateTouchPad()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ETCTouchPad : ETCBase, IBeginDragHandler, IEventSystemHandler, IDragHandler, IPointerEnterHandler, IPointerDownHandler, IPointerUpHandler, IPointerExitHandler
{
	public OnMoveStartHandler onMoveStart; // 0xd8
	public OnMoveHandler onMove; // 0xe0
	public OnMoveSpeedHandler onMoveSpeed; // 0xe8
	public OnMoveEndHandler onMoveEnd; // 0xf0
	public OnTouchStartHandler onTouchStart; // 0xf8
	public OnTouchUPHandler onTouchUp; // 0x100
	public OnDownUpHandler OnDownUp; // 0x108
	public OnDownDownHandler OnDownDown; // 0x110
	public OnDownLeftHandler OnDownLeft; // 0x118
	public OnDownRightHandler OnDownRight; // 0x120
	public OnDownUpHandler OnPressUp; // 0x128
	public OnDownDownHandler OnPressDown; // 0x130
	public OnDownLeftHandler OnPressLeft; // 0x138
	public OnDownRightHandler OnPressRight; // 0x140
	public ETCAxis axisX; // 0x148
	public ETCAxis axisY; // 0x150
	public Boolean isDPI; // 0x158
	private Image cachedImage; // 0x160
	private Vector2 tmpAxis; // 0x168
	private Vector2 OldTmpAxis; // 0x170
	private GameObject previousDargObject; // 0x178
	private Boolean isOut; // 0x180
	private Boolean isOnTouch; // 0x181
	private Boolean cachedVisible; // 0x182


	// RVA: 0x1b391f4 VA: 0x75941511f4
	public Void .ctor() { }
	// RVA: 0x1b39388 VA: 0x7594151388
	protected override Void Awake() { }
	// RVA: 0x1b393f4 VA: 0x75941513f4
	public override Void OnEnable() { }
	// RVA: 0x1b39474 VA: 0x7594151474
	public override Void Start() { }
	// RVA: 0x1b394f8 VA: 0x75941514f8
	protected override Void UpdateControlState() { }
	// RVA: 0x1b39940 VA: 0x7594151940
	protected override Void DoActionBeforeEndOfFrame() { }
	// RVA: 0x1b39970 VA: 0x7594151970
	public Void OnPointerEnter(PointerEventData eventData) { }
	// RVA: 0x1b39b90 VA: 0x7594151b90
	public Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x1b39bc8 VA: 0x7594151bc8
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x1b39b2c VA: 0x7594151b2c
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x1b39ca0 VA: 0x7594151ca0
	public Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x1b39e80 VA: 0x7594151e80
	public Void OnPointerExit(PointerEventData eventData) { }
	// RVA: 0x1b394fc VA: 0x75941514fc
	private Void UpdateTouchPad() { }
	// RVA: 0x1b39ebc VA: 0x7594151ebc
	protected override Void SetVisible(Boolean forceUnvisible) { }
	// RVA: 0x1b39f34 VA: 0x7594151f34
	protected override Void SetActivated() { }
}
```