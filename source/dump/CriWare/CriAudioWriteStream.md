# CriAudioWriteStream

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
public class CriAudioWriteStream
{
	private InternalDelegate internalDelegate; // 0x10
	private IntPtr <callbackFunction>k__BackingField; // 0x18
	private IntPtr <callbackPointer>k__BackingField; // 0x20

	public IntPtr callbackFunction { get; set; }
	public IntPtr callbackPointer { get; set; }

	// RVA: 0x413b518 VA: 0x7596753518
	public IntPtr get_callbackFunction() { }
	// RVA: 0x413b520 VA: 0x7596753520
	private Void set_callbackFunction(IntPtr value) { }
	// RVA: 0x413b528 VA: 0x7596753528
	public IntPtr get_callbackPointer() { }
	// RVA: 0x413b530 VA: 0x7596753530
	private Void set_callbackPointer(IntPtr value) { }
	// RVA: 0x413b538 VA: 0x7596753538
	public Void .ctor(IntPtr callbackFunction, IntPtr callbackPointer) { }
	// RVA: 0x413b564 VA: 0x7596753564
	public Void .ctor(Delegate callback, Int32 numChannels, Int32 bufferSize) { }
}
```