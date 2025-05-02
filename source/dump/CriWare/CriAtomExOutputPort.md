# CriAtomExOutputPort

**Namespace:** `CriWare`


## Fields

- `IntPtr <NativeHandle>k__BackingField`

- `Boolean hasExistingNativeHandle`


## Properties

- `Boolean isAvailable`


## Methods

- `Boolean get_isAvailable()`

- `Int32 CalculateWorkSize(Config)`

- `Void SetAsrRackId(Int32)`

- `Void SetVibrationChannelLevel(Int32, Single)`

- `Void SetMonauralMix(Boolean)`

- `Boolean IsDestroyable()`

- `Void set_NativeHandle(IntPtr)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExOutputPort : CriDisposable
{
	public const UInt32 MaxNameLength; // 0x0
	private IntPtr <NativeHandle>k__BackingField; // 0x20
	private Boolean hasExistingNativeHandle; // 0x28

	public Boolean isAvailable { get; }
	internal IntPtr NativeHandle { get; set; }

	// RVA: 0x412f97c VA: 0x759674797c
	public Boolean get_isAvailable() { }
	// RVA: 0x412f9d0 VA: 0x75967479d0
	public Int32 CalculateWorkSize(Config config) { }
	// RVA: 0x412fa78 VA: 0x7596747a78
	public Void .ctor(Config config) { }
	// RVA: 0x412fc0c VA: 0x7596747c0c
	internal Void .ctor(IntPtr existingNativeHandle) { }
	// RVA: 0x412fc94 VA: 0x7596747c94
	protected override Void Finalize() { }
	// RVA: 0x412fd34 VA: 0x7596747d34
	public override Void Dispose() { }
	// RVA: 0x412fd44 VA: 0x7596747d44
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x412feb8 VA: 0x7596747eb8
	public Void SetAsrRackId(Int32 rackId) { }
	// RVA: 0x412ff44 VA: 0x7596747f44
	public Void SetVibrationChannelLevel(Int32 channel, Single level) { }
	// RVA: 0x412ffe0 VA: 0x7596747fe0
	public Void SetMonauralMix(Boolean monauralMix) { }
	// RVA: 0x4130070 VA: 0x7596748070
	public Boolean IsDestroyable() { }
	// RVA: 0x41300fc VA: 0x75967480fc
	internal IntPtr get_NativeHandle() { }
	// RVA: 0x4130104 VA: 0x7596748104
	private Void set_NativeHandle(IntPtr value) { }
}
```