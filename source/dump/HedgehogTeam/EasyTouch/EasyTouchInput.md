# EasyTouchInput

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `Boolean bComplex`

- `Vector2 deltaFingerPosition`

- `Vector2 oldFinger2Position`

- `Vector2 complexCenter`


## Methods

- `Int32 TouchCount()`

- `Int32 getTouchCount(Boolean)`

- `Finger GetMouseTouch(Int32, Finger)`

- `Vector2 GetSecondFingerPosition()`

- `Vector2 GetPointerPosition(Int32)`

- `Vector2 GetPinchTwist2Finger(Boolean)`

- `Vector2 GetComplex2finger()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class EasyTouchInput
{
	private Vector2[] oldMousePosition; // 0x10
	private Int32[] tapCount; // 0x18
	private Single[] startActionTime; // 0x20
	private Single[] deltaTime; // 0x28
	private Single[] tapeTime; // 0x30
	private Boolean bComplex; // 0x38
	private Vector2 deltaFingerPosition; // 0x3c
	private Vector2 oldFinger2Position; // 0x44
	private Vector2 complexCenter; // 0x4c


	// RVA: 0x3dce4a4 VA: 0x75963e64a4
	public Int32 TouchCount() { }
	// RVA: 0x3dce4ac VA: 0x75963e64ac
	private Int32 getTouchCount(Boolean realTouch) { }
	// RVA: 0x3dce5dc VA: 0x75963e65dc
	public Finger GetMouseTouch(Int32 fingerIndex, Finger myFinger) { }
	// RVA: 0x3dceb48 VA: 0x75963e6b48
	public Vector2 GetSecondFingerPosition() { }
	// RVA: 0x3dceb28 VA: 0x75963e6b28
	private Vector2 GetPointerPosition(Int32 index) { }
	// RVA: 0x3dcece0 VA: 0x75963e6ce0
	private Vector2 GetPinchTwist2Finger(Boolean newSim) { }
	// RVA: 0x3dcec68 VA: 0x75963e6c68
	private Vector2 GetComplex2finger() { }
	// RVA: 0x3dcee04 VA: 0x75963e6e04
	public Void .ctor() { }
}
```