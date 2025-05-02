# CriAtomExTween

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`


## Properties

- `Single Value`

- `Boolean IsActive`


## Methods

- `Single get_Value()`

- `Boolean get_IsActive()`

- `Void MoveTo(UInt16, Single)`

- `Void MoveFrom(UInt16, Single)`

- `Void Stop()`

- `Void Reset()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExTween : CriDisposable
{
	private IntPtr handle; // 0x20

	internal IntPtr nativeHandle { get; }
	public Single Value { get; }
	public Boolean IsActive { get; }

	// RVA: 0x41393e0 VA: 0x75967513e0
	internal IntPtr get_nativeHandle() { }
	// RVA: 0x41393e8 VA: 0x75967513e8
	public Void .ctor() { }
	// RVA: 0x41393f4 VA: 0x75967513f4
	public Void .ctor(Parameter parameterId) { }
	// RVA: 0x4139550 VA: 0x7596751550
	public Void .ctor(UInt32 aisacId) { }
	// RVA: 0x4139400 VA: 0x7596751400
	public Void .ctor(ParameterType parameterType, UInt32 targetId) { }
	// RVA: 0x41395f0 VA: 0x75967515f0
	public override Void Dispose() { }
	// RVA: 0x4139600 VA: 0x7596751600
	public Single get_Value() { }
	// RVA: 0x4139684 VA: 0x7596751684
	public Boolean get_IsActive() { }
	// RVA: 0x4139710 VA: 0x7596751710
	public Void MoveTo(UInt16 durationMs, Single value) { }
	// RVA: 0x41397ac VA: 0x75967517ac
	public Void MoveFrom(UInt16 durationMs, Single value) { }
	// RVA: 0x4139848 VA: 0x7596751848
	public Void Stop() { }
	// RVA: 0x41398cc VA: 0x75967518cc
	public Void Reset() { }
	// RVA: 0x4139950 VA: 0x7596751950
	protected override Void Finalize() { }
	// RVA: 0x41399f0 VA: 0x75967519f0
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x413955c VA: 0x759675155c
	private static extern IntPtr criAtomExTween_Create(ref Config config, IntPtr work, Int32 work_size) { }
	// RVA: 0x4139ae0 VA: 0x7596751ae0
	private static extern Void criAtomExTween_Destroy(IntPtr tween) { }
	// RVA: 0x4139608 VA: 0x7596751608
	private static extern Single criAtomExTween_GetValue(IntPtr tween) { }
	// RVA: 0x4139718 VA: 0x7596751718
	private static extern Void criAtomExTween_MoveTo(IntPtr tween, UInt16 time_ms, Single value) { }
	// RVA: 0x41397b4 VA: 0x75967517b4
	private static extern Void criAtomExTween_MoveFrom(IntPtr tween, UInt16 time_ms, Single value) { }
	// RVA: 0x4139850 VA: 0x7596751850
	private static extern Void criAtomExTween_Stop(IntPtr tween) { }
	// RVA: 0x41398d4 VA: 0x75967518d4
	private static extern Void criAtomExTween_Reset(IntPtr tween) { }
	// RVA: 0x413968c VA: 0x759675168c
	private static extern Boolean criAtomExTween_IsActive(IntPtr tween) { }
}
```