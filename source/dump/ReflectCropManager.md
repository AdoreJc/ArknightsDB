# ReflectCropManager

**Namespace:** ` `


## Fields

- `ReflectIdx assignedID`


## Properties

- `Boolean CropSuccess`

- `ReflectIdx AssignedID`

- `String OpaqueCBName`

- `String TransparentCBName`

- `String CropKeyword`

- `String CropProp`


## Methods

- `Boolean get_CropSuccess()`

- `ReflectIdx get_AssignedID()`

- `String get_OpaqueCBName()`

- `String get_TransparentCBName()`

- `String get_CropKeyword()`

- `String get_CropProp()`

- `Boolean ApplyReflectID(ReflectCamera)`

- `Void ReleaseReflectID()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ReflectCropManager
{
	private ReflectIdx assignedID; // 0x10

	public Boolean CropSuccess { get; }
	public ReflectIdx AssignedID { get; }
	public String OpaqueCBName { get; }
	public String TransparentCBName { get; }
	public String CropKeyword { get; }
	public String CropProp { get; }

	// RVA: 0x35bbfd8 VA: 0x7595bd3fd8
	public Boolean get_CropSuccess() { }
	// RVA: 0x35c0b0c VA: 0x7595bd8b0c
	public ReflectIdx get_AssignedID() { }
	// RVA: 0x35bc9e0 VA: 0x7595bd49e0
	public String get_OpaqueCBName() { }
	// RVA: 0x35bca64 VA: 0x7595bd4a64
	public String get_TransparentCBName() { }
	// RVA: 0x35be4ec VA: 0x7595bd64ec
	public String get_CropKeyword() { }
	// RVA: 0x35c024c VA: 0x7595bd824c
	public String get_CropProp() { }
	// RVA: 0x35bc7d8 VA: 0x7595bd47d8
	public Boolean ApplyReflectID(ReflectCamera camera) { }
	// RVA: 0x35bf5d4 VA: 0x7595bd75d4
	public Void ReleaseReflectID() { }
	// RVA: 0x35c0864 VA: 0x7595bd8864
	public Void .ctor() { }
}
```