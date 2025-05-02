# ElevatorMovingState

**Namespace:** ` `


## Fields

- `VRoom targetRoom`

- `Tween movingTween`

- `Boolean isMovingUp`


## Properties

- `Boolean isMoving`


## Methods

- `Boolean get_isMoving()`

- `Void ResetTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ElevatorMovingState
{
	public VRoom targetRoom; // 0x10
	public Tween movingTween; // 0x18
	public Boolean isMovingUp; // 0x20

	public Boolean isMoving { get; }

	// RVA: 0x3d00240 VA: 0x7596318240
	public Boolean get_isMoving() { }
	// RVA: 0x3d01240 VA: 0x7596319240
	public Void ResetTween() { }
	// RVA: 0x3d01238 VA: 0x7596319238
	public Void .ctor() { }
}
```