# TwoFingerGesture

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `GestureType currentGesture`

- `GestureType oldGesture`

- `Int32 finger0`

- `Int32 finger1`

- `Single startTimeAction`

- `Single timeSinceStartAction`

- `Vector2 startPosition`

- `Vector2 position`

- `Vector2 deltaPosition`

- `Vector2 oldStartPosition`

- `Single startDistance`

- `Single fingerDistance`

- `Single oldFingerDistance`

- `Boolean lockPinch`

- `Boolean lockTwist`

- `Single lastPinch`

- `Single lastTwistAngle`

- `GameObject pickedObject`

- `GameObject oldPickedObject`

- `Camera pickedCamera`

- `Boolean isGuiCamera`

- `Boolean isOverGui`

- `GameObject pickedUIElement`

- `Boolean dragStart`

- `Boolean swipeStart`

- `Boolean inSingleDoubleTaps`

- `Single tapCurentTime`


## Methods

- `Void ClearPickedObjectData()`

- `Void ClearPickedUIData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class TwoFingerGesture
{
	public GestureType currentGesture; // 0x10
	public GestureType oldGesture; // 0x14
	public Int32 finger0; // 0x18
	public Int32 finger1; // 0x1c
	public Single startTimeAction; // 0x20
	public Single timeSinceStartAction; // 0x24
	public Vector2 startPosition; // 0x28
	public Vector2 position; // 0x30
	public Vector2 deltaPosition; // 0x38
	public Vector2 oldStartPosition; // 0x40
	public Single startDistance; // 0x48
	public Single fingerDistance; // 0x4c
	public Single oldFingerDistance; // 0x50
	public Boolean lockPinch; // 0x54
	public Boolean lockTwist; // 0x55
	public Single lastPinch; // 0x58
	public Single lastTwistAngle; // 0x5c
	public GameObject pickedObject; // 0x60
	public GameObject oldPickedObject; // 0x68
	public Camera pickedCamera; // 0x70
	public Boolean isGuiCamera; // 0x78
	public Boolean isOverGui; // 0x79
	public GameObject pickedUIElement; // 0x80
	public Boolean dragStart; // 0x88
	public Boolean swipeStart; // 0x89
	public Boolean inSingleDoubleTaps; // 0x8a
	public Single tapCurentTime; // 0x8c


	// RVA: 0x3dcf2b8 VA: 0x75963e72b8
	public Void ClearPickedObjectData() { }
	// RVA: 0x3dcf2f8 VA: 0x75963e72f8
	public Void ClearPickedUIData() { }
	// RVA: 0x3dcf308 VA: 0x75963e7308
	public Void .ctor() { }
}
```