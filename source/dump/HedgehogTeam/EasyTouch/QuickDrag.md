# QuickDrag

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `OnDragStart onDragStart`

- `OnDrag onDrag`

- `OnDragEnd onDragEnd`

- `Boolean isStopOncollisionEnter`

- `Vector3 deltaPosition`

- `Boolean isOnDrag`

- `Gesture lastGesture`


## Methods

- `Void OnDestroy()`

- `Void UnsubscribeEvent()`

- `Void OnCollisionEnter()`

- `Void On_TouchStart(Gesture)`

- `Void On_TouchDown(Gesture)`

- `Void On_TouchUp(Gesture)`

- `Void On_DragStart(Gesture)`

- `Void On_Drag(Gesture)`

- `Void On_DragEnd(Gesture)`

- `Vector3 GetPositionAxes(Vector3)`

- `Void StopDrag()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class QuickDrag : QuickBase
{
	public OnDragStart onDragStart; // 0x70
	public OnDrag onDrag; // 0x78
	public OnDragEnd onDragEnd; // 0x80
	public Boolean isStopOncollisionEnter; // 0x88
	private Vector3 deltaPosition; // 0x8c
	private Boolean isOnDrag; // 0x98
	private Gesture lastGesture; // 0xa0


	// RVA: 0x375b7b8 VA: 0x7595d737b8
	public Void .ctor() { }
	// RVA: 0x375b878 VA: 0x7595d73878
	public override Void OnEnable() { }
	// RVA: 0x375ba84 VA: 0x7595d73a84
	public override Void OnDisable() { }
	// RVA: 0x375bc94 VA: 0x7595d73c94
	private Void OnDestroy() { }
	// RVA: 0x375ba88 VA: 0x7595d73a88
	private Void UnsubscribeEvent() { }
	// RVA: 0x375bc98 VA: 0x7595d73c98
	private Void OnCollisionEnter() { }
	// RVA: 0x375bd9c VA: 0x7595d73d9c
	private Void On_TouchStart(Gesture gesture) { }
	// RVA: 0x375bed4 VA: 0x7595d73ed4
	private Void On_TouchDown(Gesture gesture) { }
	// RVA: 0x375c0a8 VA: 0x7595d740a8
	private Void On_TouchUp(Gesture gesture) { }
	// RVA: 0x375c0f4 VA: 0x7595d740f4
	private Void On_DragStart(Gesture gesture) { }
	// RVA: 0x375c30c VA: 0x7595d7430c
	private Void On_Drag(Gesture gesture) { }
	// RVA: 0x375c600 VA: 0x7595d74600
	private Void On_DragEnd(Gesture gesture) { }
	// RVA: 0x375c4ec VA: 0x7595d744ec
	private Vector3 GetPositionAxes(Vector3 position) { }
	// RVA: 0x375bcb0 VA: 0x7595d73cb0
	public Void StopDrag() { }
}
```