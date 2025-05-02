# Input

**Namespace:** ` `


## Properties

- `Int32 touchCount`

- `Boolean mousePresent`


## Methods

- `Boolean GetButtonDown(String)`

- `Single GetAxisRaw(String)`

- `Int32 get_touchCount()`

- `Touch GetTouch(Int32)`

- `Boolean get_mousePresent()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : 
private class Input : IInput
{

	public Int32 touchCount { get; }
	public Boolean mousePresent { get; }

	// RVA: 0x6933f60 VA: 0x7598f4bf60
	public Boolean GetButtonDown(String button) { }
	// RVA: 0x6933f6c VA: 0x7598f4bf6c
	public Single GetAxisRaw(String axis) { }
	// RVA: 0x6933f78 VA: 0x7598f4bf78
	public Int32 get_touchCount() { }
	// RVA: 0x6933f80 VA: 0x7598f4bf80
	public Touch GetTouch(Int32 index) { }
	// RVA: 0x6933fb8 VA: 0x7598f4bfb8
	public Boolean get_mousePresent() { }
	// RVA: 0x6932800 VA: 0x7598f4a800
	public Void .ctor() { }
}
```