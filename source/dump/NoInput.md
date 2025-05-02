# NoInput

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
private class NoInput : IInput
{

	public Int32 touchCount { get; }
	public Boolean mousePresent { get; }

	// RVA: 0x6933fc0 VA: 0x7598f4bfc0
	public Boolean GetButtonDown(String button) { }
	// RVA: 0x6933fc8 VA: 0x7598f4bfc8
	public Single GetAxisRaw(String axis) { }
	// RVA: 0x6933fd0 VA: 0x7598f4bfd0
	public Int32 get_touchCount() { }
	// RVA: 0x6933fd8 VA: 0x7598f4bfd8
	public Touch GetTouch(Int32 index) { }
	// RVA: 0x6933fec VA: 0x7598f4bfec
	public Boolean get_mousePresent() { }
	// RVA: 0x6932808 VA: 0x7598f4a808
	public Void .ctor() { }
}
```