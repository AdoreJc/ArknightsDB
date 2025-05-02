# ETCButton

**Namespace:** ` `


## Fields

- `OnDownHandler onDown`

- `OnPressedHandler onPressed`

- `OnPressedValueandler onPressedValue`

- `OnUPHandler onUp`

- `ETCAxis axis`

- `Sprite normalSprite`

- `Color normalColor`

- `Sprite pressedSprite`

- `Color pressedColor`

- `Image cachedImage`

- `Boolean isOnPress`

- `GameObject previousDargObject`

- `Boolean isOnTouch`


## Methods

- `Void OnPointerEnter(PointerEventData)`

- `Void OnPointerDown(PointerEventData)`

- `Void OnPointerUp(PointerEventData)`

- `Void OnPointerExit(PointerEventData)`

- `Void UpdateButton()`

- `Void ApllyState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ETCButton : ETCBase, IPointerEnterHandler, IEventSystemHandler, IPointerDownHandler, IPointerUpHandler, IPointerExitHandler
{
	public OnDownHandler onDown; // 0xd8
	public OnPressedHandler onPressed; // 0xe0
	public OnPressedValueandler onPressedValue; // 0xe8
	public OnUPHandler onUp; // 0xf0
	public ETCAxis axis; // 0xf8
	public Sprite normalSprite; // 0x100
	public Color normalColor; // 0x108
	public Sprite pressedSprite; // 0x118
	public Color pressedColor; // 0x120
	private Image cachedImage; // 0x130
	private Boolean isOnPress; // 0x138
	private GameObject previousDargObject; // 0x140
	private Boolean isOnTouch; // 0x148


	// RVA: 0x1b2f4d4 VA: 0x75941474d4
	public Void .ctor() { }
	// RVA: 0x1b2f5a0 VA: 0x75941475a0
	protected override Void Awake() { }
	// RVA: 0x1b2f600 VA: 0x7594147600
	public override Void Start() { }
	// RVA: 0x1b2f660 VA: 0x7594147660
	protected override Void UpdateControlState() { }
	// RVA: 0x1b2f80c VA: 0x759414780c
	protected override Void DoActionBeforeEndOfFrame() { }
	// RVA: 0x1b2f824 VA: 0x7594147824
	public Void OnPointerEnter(PointerEventData eventData) { }
	// RVA: 0x1b2f99c VA: 0x759414799c
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x1b2fb20 VA: 0x7594147b20
	public Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x1b2fc84 VA: 0x7594147c84
	public Void OnPointerExit(PointerEventData eventData) { }
	// RVA: 0x1b2f664 VA: 0x7594147664
	private Void UpdateButton() { }
	// RVA: 0x1b2fccc VA: 0x7594147ccc
	protected override Void SetVisible(Boolean forceUnvisible) { }
	// RVA: 0x1b2fa2c VA: 0x7594147a2c
	private Void ApllyState() { }
	// RVA: 0x1b2fd30 VA: 0x7594147d30
	protected override Void SetActivated() { }
}
```