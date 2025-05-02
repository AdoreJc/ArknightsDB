# CriAudioReadStream

**Namespace:** `CriWare`


## Fields

- `InternalDelegate internalDelegate`

- `IntPtr <callbackFunction>k__BackingField`

- `IntPtr <callbackPointer>k__BackingField`


## Properties

- `IntPtr callbackFunction`

- `IntPtr callbackPointer`


## Methods

- `IntPtr get_callbackFunction()`

- `Void set_callbackFunction(IntPtr)`

- `IntPtr get_callbackPointer()`

- `Void set_callbackPointer(IntPtr)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAudioReadStream
{
	private InternalDelegate internalDelegate; // 0x10
	private IntPtr <callbackFunction>k__BackingField; // 0x18
	private IntPtr <callbackPointer>k__BackingField; // 0x20

	public IntPtr callbackFunction { get; set; }
	public IntPtr callbackPointer { get; set; }

	// RVA: 0x413ae10 VA: 0x7596752e10
	public IntPtr get_callbackFunction() { }
	// RVA: 0x413ae18 VA: 0x7596752e18
	private Void set_callbackFunction(IntPtr value) { }
	// RVA: 0x413ae20 VA: 0x7596752e20
	public IntPtr get_callbackPointer() { }
	// RVA: 0x413ae28 VA: 0x7596752e28
	private Void set_callbackPointer(IntPtr value) { }
	// RVA: 0x413ae30 VA: 0x7596752e30
	public Void .ctor(IntPtr callbackFunction, IntPtr callbackPointer) { }
	// RVA: 0x413ae5c VA: 0x7596752e5c
	public Void .ctor(Delegate callback, Int32 numChannels, Int32 bufferSize) { }
}
```