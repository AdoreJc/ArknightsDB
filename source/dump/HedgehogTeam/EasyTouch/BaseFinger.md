# BaseFinger

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `Int32 fingerIndex`

- `Int32 touchCount`

- `Vector2 startPosition`

- `Vector2 position`

- `Vector2 deltaPosition`

- `Single actionTime`

- `Single deltaTime`

- `Camera pickedCamera`

- `GameObject pickedObject`

- `Boolean isGuiCamera`

- `Boolean isOverGui`

- `GameObject pickedUIElement`

- `Single altitudeAngle`

- `Single azimuthAngle`

- `Single maximumPossiblePressure`

- `Single pressure`

- `Single radius`

- `Single radiusVariance`

- `TouchType touchType`


## Methods

- `Gesture GetGesture()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class BaseFinger
{
	public Int32 fingerIndex; // 0x10
	public Int32 touchCount; // 0x14
	public Vector2 startPosition; // 0x18
	public Vector2 position; // 0x20
	public Vector2 deltaPosition; // 0x28
	public Single actionTime; // 0x30
	public Single deltaTime; // 0x34
	public Camera pickedCamera; // 0x38
	public GameObject pickedObject; // 0x40
	public Boolean isGuiCamera; // 0x48
	public Boolean isOverGui; // 0x49
	public GameObject pickedUIElement; // 0x50
	public Single altitudeAngle; // 0x58
	public Single azimuthAngle; // 0x5c
	public Single maximumPossiblePressure; // 0x60
	public Single pressure; // 0x64
	public Single radius; // 0x68
	public Single radiusVariance; // 0x6c
	public TouchType touchType; // 0x70


	// RVA: 0x375f2ac VA: 0x7595d772ac
	public Gesture GetGesture() { }
	// RVA: 0x375f38c VA: 0x7595d7738c
	public Void .ctor() { }
}
```