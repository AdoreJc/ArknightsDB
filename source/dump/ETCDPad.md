# ETCDPad

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

- `Sprite normalSprite`

- `Color normalColor`

- `Sprite pressedSprite`

- `Color pressedColor`

- `Vector2 tmpAxis`

- `Vector2 OldTmpAxis`

- `Boolean isOnTouch`

- `Image cachedImage`

- `Single buttonSizeCoef`


## Methods

- `Void OnPointerDown(PointerEventData)`

- `Void OnDrag(PointerEventData)`

- `Void OnPointerUp(PointerEventData)`

- `Void UpdateDPad()`

- `Void GetTouchDirection(Vector2, Camera)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ETCDPad : ETCBase, IDragHandler, IEventSystemHandler, IPointerDownHandler, IPointerUpHandler
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
	public Sprite normalSprite; // 0x158
	public Color normalColor; // 0x160
	public Sprite pressedSprite; // 0x170
	public Color pressedColor; // 0x178
	private Vector2 tmpAxis; // 0x188
	private Vector2 OldTmpAxis; // 0x190
	private Boolean isOnTouch; // 0x198
	private Image cachedImage; // 0x1a0
	public Single buttonSizeCoef; // 0x1a8


	// RVA: 0x1b2fdc8 VA: 0x7594147dc8
	public Void .ctor() { }
	// RVA: 0x1b2ff24 VA: 0x7594147f24
	public override Void Start() { }
	// RVA: 0x1b2ffd8 VA: 0x7594147fd8
	protected override Void UpdateControlState() { }
	// RVA: 0x1b3047c VA: 0x759414847c
	protected override Void DoActionBeforeEndOfFrame() { }
	// RVA: 0x1b304a4 VA: 0x75941484a4
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x1b30750 VA: 0x7594148750
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x1b307c4 VA: 0x75941487c4
	public Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x1b2ffdc VA: 0x7594147fdc
	private Void UpdateDPad() { }
	// RVA: 0x1b308a4 VA: 0x75941488a4
	protected override Void SetVisible(Boolean forceUnvisible) { }
	// RVA: 0x1b30908 VA: 0x7594148908
	protected override Void SetActivated() { }
	// RVA: 0x1b3052c VA: 0x759414852c
	private Void GetTouchDirection(Vector2 position, Camera cam) { }
}
```