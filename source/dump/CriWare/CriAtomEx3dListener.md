# CriAtomEx3dListener

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`


## Properties

- `IntPtr nativeHandle`


## Methods

- `Void Dispose(Boolean)`

- `IntPtr get_nativeHandle()`

- `Void Update()`

- `Void ResetParameters()`

- `Void SetPosition(Single, Single, Single)`

- `Void SetVelocity(Single, Single, Single)`

- `Void SetOrientation(Single, Single, Single, Single, Single, Single)`

- `Void SetDistanceFactor(Single)`

- `Void SetDopplerMultiplier(Single)`

- `Void SetFocusPoint(Single, Single, Single)`

- `Void SetDistanceFocusLevel(Single)`

- `Void SetDirectionFocusLevel(Single)`

- `Void Set3dRegion(CriAtomEx3dRegion)`

- `Boolean IsDestroyable()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomEx3dListener : CriDisposable
{
	private IntPtr handle; // 0x20

	public IntPtr nativeHandle { get; }

	// RVA: 0x4114f5c VA: 0x759672cf5c
	public Void .ctor() { }
	// RVA: 0x4120598 VA: 0x7596738598
	public override Void Dispose() { }
	// RVA: 0x41205a0 VA: 0x75967385a0
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x4120710 VA: 0x7596738710
	public IntPtr get_nativeHandle() { }
	// RVA: 0x4115270 VA: 0x759672d270
	public Void Update() { }
	// RVA: 0x4120794 VA: 0x7596738794
	public Void ResetParameters() { }
	// RVA: 0x41151d4 VA: 0x759672d1d4
	public Void SetPosition(Single x, Single y, Single z) { }
	// RVA: 0x4115ca4 VA: 0x759672dca4
	public Void SetVelocity(Single x, Single y, Single z) { }
	// RVA: 0x4115d40 VA: 0x759672dd40
	public Void SetOrientation(Single fx, Single fy, Single fz, Single ux, Single uy, Single uz) { }
	// RVA: 0x4120a18 VA: 0x7596738a18
	public Void SetDistanceFactor(Single distanceFactor) { }
	// RVA: 0x4120b8c VA: 0x7596738b8c
	public Void SetDopplerMultiplier(Single dopplerMultiplier) { }
	// RVA: 0x4120c64 VA: 0x7596738c64
	public Void SetFocusPoint(Single x, Single y, Single z) { }
	// RVA: 0x4120d84 VA: 0x7596738d84
	public Void SetDistanceFocusLevel(Single distanceFocusLevel) { }
	// RVA: 0x4120e90 VA: 0x7596738e90
	public Void SetDirectionFocusLevel(Single directionFocusLevel) { }
	// RVA: 0x4115524 VA: 0x759672d524
	public Void Set3dRegion(CriAtomEx3dRegion region3d) { }
	// RVA: 0x4121020 VA: 0x7596739020
	public Boolean IsDestroyable() { }
	// RVA: 0x41210ac VA: 0x75967390ac
	protected override Void Finalize() { }
	// RVA: 0x4120504 VA: 0x7596738504
	private static extern IntPtr criAtomEx3dListener_Create(ref Config config, IntPtr work, Int32 work_size) { }
	// RVA: 0x4120694 VA: 0x7596738694
	private static extern Void criAtomEx3dListener_Destroy(IntPtr ex_3d_listener) { }
	// RVA: 0x4120718 VA: 0x7596738718
	private static extern Void criAtomEx3dListener_Update(IntPtr ex_3d_listener) { }
	// RVA: 0x4120800 VA: 0x7596738800
	private static extern Void criAtomEx3dListener_ResetParameters(IntPtr ex_3d_listener) { }
	// RVA: 0x412087c VA: 0x759673887c
	private static extern Void criAtomEx3dListener_SetPosition(IntPtr ex_3d_listener, ref NativeVector position) { }
	// RVA: 0x4120900 VA: 0x7596738900
	private static extern Void criAtomEx3dListener_SetVelocity(IntPtr ex_3d_listener, ref NativeVector velocity) { }
	// RVA: 0x4120984 VA: 0x7596738984
	private static extern Void criAtomEx3dListener_SetOrientation(IntPtr ex_3d_listener, ref NativeVector front, ref NativeVector top) { }
	// RVA: 0x4121144 VA: 0x7596739144
	private static extern Void criAtomEx3dListener_SetDistanceFactor(IntPtr ex_3d_listener, Single distance_factor) { }
	// RVA: 0x4120b00 VA: 0x7596738b00
	private static extern Void criAtomEx3dListener_SetDopplerMultiplier(IntPtr ex_3d_listener, Single doppler_multiplier) { }
	// RVA: 0x4120d00 VA: 0x7596738d00
	private static extern Void criAtomEx3dListener_SetFocusPoint(IntPtr ex_3d_listener, ref NativeVector focus_point) { }
	// RVA: 0x4120e04 VA: 0x7596738e04
	private static extern Void criAtomEx3dListener_SetDistanceFocusLevel(IntPtr ex_3d_listener, Single distance_focus_level) { }
	// RVA: 0x4120f10 VA: 0x7596738f10
	private static extern Void criAtomEx3dListener_SetDirectionFocusLevel(IntPtr ex_3d_listener, Single direction_focus_level) { }
	// RVA: 0x4121028 VA: 0x7596739028
	private static extern Boolean criAtomEx3dListener_IsDestroyable(IntPtr ex_3d_listener) { }
	// RVA: 0x4120f9c VA: 0x7596738f9c
	private static extern Void criAtomEx3dListener_Set3dRegionHn(IntPtr ex_3d_listener, IntPtr ex_3d_region) { }
}
```