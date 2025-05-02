# Gesture

**Namespace:** `HedgehogTeam.EasyTouch`


## Fields

- `SwipeDirection swipe`

- `Single swipeLength`

- `Vector2 swipeVector`

- `Single deltaPinch`

- `Single twistAngle`

- `Single twoFingerDistance`

- `EvtType type`


## Methods

- `Object Clone()`

- `Vector3 GetTouchToWorldPoint(Single)`

- `Vector3 GetTouchToWorldPoint(Vector3)`

- `Single GetSwipeOrDragAngle()`

- `Vector2 NormalizedPosition()`

- `Boolean IsOverUIElement()`

- `Boolean IsOverRectTransform(RectTransform, Camera)`

- `GameObject GetCurrentFirstPickedUIElement(Boolean)`

- `GameObject GetCurrentPickedObject(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HedgehogTeam.EasyTouch
public class Gesture : BaseFinger, ICloneable
{
	public SwipeDirection swipe; // 0x74
	public Single swipeLength; // 0x78
	public Vector2 swipeVector; // 0x7c
	public Single deltaPinch; // 0x84
	public Single twistAngle; // 0x88
	public Single twoFingerDistance; // 0x8c
	public EvtType type; // 0x90


	// RVA: 0x3dcef44 VA: 0x75963e6f44
	public Object Clone() { }
	// RVA: 0x3dcef4c VA: 0x75963e6f4c
	public Vector3 GetTouchToWorldPoint(Single z) { }
	// RVA: 0x3dcef84 VA: 0x75963e6f84
	public Vector3 GetTouchToWorldPoint(Vector3 position3D) { }
	// RVA: 0x3dcf00c VA: 0x75963e700c
	public Single GetSwipeOrDragAngle() { }
	// RVA: 0x3dcf160 VA: 0x75963e7160
	public Vector2 NormalizedPosition() { }
	// RVA: 0x3dcf1c4 VA: 0x75963e71c4
	public Boolean IsOverUIElement() { }
	// RVA: 0x3dcf1d0 VA: 0x75963e71d0
	public Boolean IsOverRectTransform(RectTransform tr, Camera camera) { }
	// RVA: 0x3dcf290 VA: 0x75963e7290
	public GameObject GetCurrentFirstPickedUIElement(Boolean isTwoFinger) { }
	// RVA: 0x3dcf2a0 VA: 0x75963e72a0
	public GameObject GetCurrentPickedObject(Boolean isTwoFinger) { }
	// RVA: 0x3dcf2b0 VA: 0x75963e72b0
	public Void .ctor() { }
}
```