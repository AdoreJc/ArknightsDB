# CriAtomExSoundObject

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`


## Properties

- `IntPtr nativeHandle`


## Methods

- `IntPtr get_nativeHandle()`

- `Void AddPlayer(CriAtomExPlayer)`

- `Void DeletePlayer(CriAtomExPlayer)`

- `Void DeleteAllPlayers()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExSoundObject : CriDisposable
{
	private IntPtr handle; // 0x20

	public IntPtr nativeHandle { get; }

	// RVA: 0x4138e18 VA: 0x7596750e18
	public IntPtr get_nativeHandle() { }
	// RVA: 0x4138e20 VA: 0x7596750e20
	public Void .ctor(Boolean enableVoiceLimitScope, Boolean enableCategoryCueLimitScope) { }
	// RVA: 0x4139038 VA: 0x7596751038
	public override Void Dispose() { }
	// RVA: 0x4139180 VA: 0x7596751180
	public Void AddPlayer(CriAtomExPlayer player) { }
	// RVA: 0x4139220 VA: 0x7596751220
	public Void DeletePlayer(CriAtomExPlayer player) { }
	// RVA: 0x41392c0 VA: 0x75967512c0
	public Void DeleteAllPlayers() { }
	// RVA: 0x4139344 VA: 0x7596751344
	protected override Void Finalize() { }
	// RVA: 0x4138f78 VA: 0x7596750f78
	private static extern IntPtr criAtomExSoundObject_Create(ref Config config, IntPtr work, Int32 work_size) { }
	// RVA: 0x4139104 VA: 0x7596751104
	private static extern Void criAtomExSoundObject_Destroy(IntPtr soundObject) { }
	// RVA: 0x413919c VA: 0x759675119c
	private static extern Void criAtomExSoundObject_AddPlayer(IntPtr soundObject, IntPtr player) { }
	// RVA: 0x413923c VA: 0x759675123c
	private static extern Void criAtomExSoundObject_DeletePlayer(IntPtr soundObject, IntPtr player) { }
	// RVA: 0x41392c8 VA: 0x75967512c8
	private static extern Void criAtomExSoundObject_DeleteAllPlayers(IntPtr soundObject) { }
}
```