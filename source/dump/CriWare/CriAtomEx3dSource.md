# CriAtomEx3dSource

**Namespace:** `CriWare`


## Fields

- `UInt32 currentRandomPositionListMaxLength`

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

- `Void SetOrientation(Vector3, Vector3)`

- `Void SetConeOrientation(Single, Single, Single)`

- `Void SetConeParameter(Single, Single, Single)`

- `Void SetMinMaxDistance(Single, Single)`

- `Void SetInteriorPanField(Single, Single)`

- `Void SetDopplerFactor(Single)`

- `Void SetVolume(Single)`

- `Void SetMaxAngleAisacDelta(Single)`

- `Void SetAttenuationDistanceSetting(Boolean)`

- `Boolean GetAttenuationDistanceSetting()`

- `Void SetRandomPositionConfig(Nullable`1)`

- `Void SetRandomPositionList(Vector3[])`

- `Void Set3dRegion(CriAtomEx3dRegion)`

- `Void SetListenerBasedElevationAngleAisacControlId(UInt16)`

- `Void SetSourceBasedElevationAngleAisacControlId(UInt16)`

- `Void SetDistanceAisacControlId(UInt16)`

- `Boolean IsDestroyable()`

- `NativeVector GetPosition()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomEx3dSource : CriDisposable
{
	private UInt32 currentRandomPositionListMaxLength; // 0x20
	private IntPtr handle; // 0x28

	public IntPtr nativeHandle { get; }

	// RVA: 0x41188ac VA: 0x75967308ac
	public Void .ctor(Boolean enableVoicePriorityDecay, UInt32 randomPositionListMaxLength) { }
	// RVA: 0x4121298 VA: 0x7596739298
	public override Void Dispose() { }
	// RVA: 0x41212a0 VA: 0x75967392a0
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x4121410 VA: 0x7596739410
	public IntPtr get_nativeHandle() { }
	// RVA: 0x41184b4 VA: 0x75967304b4
	public Void Update() { }
	// RVA: 0x4121494 VA: 0x7596739494
	public Void ResetParameters() { }
	// RVA: 0x4118af0 VA: 0x7596730af0
	public Void SetPosition(Single x, Single y, Single z) { }
	// RVA: 0x4118d48 VA: 0x7596730d48
	public Void SetVelocity(Single x, Single y, Single z) { }
	// RVA: 0x4118d70 VA: 0x7596730d70
	public Void SetOrientation(Vector3 front, Vector3 top) { }
	// RVA: 0x41216b4 VA: 0x75967396b4
	public Void SetConeOrientation(Single x, Single y, Single z) { }
	// RVA: 0x4121760 VA: 0x7596739760
	public Void SetConeParameter(Single insideAngle, Single outsideAngle, Single outsideVolume) { }
	// RVA: 0x412180c VA: 0x759673980c
	public Void SetMinMaxDistance(Single minDistance, Single maxDistance) { }
	// RVA: 0x41218a8 VA: 0x75967398a8
	public Void SetInteriorPanField(Single sourceRadius, Single interiorDistance) { }
	// RVA: 0x4121944 VA: 0x7596739944
	public Void SetDopplerFactor(Single dopplerFactor) { }
	// RVA: 0x41219d8 VA: 0x75967399d8
	public Void SetVolume(Single volume) { }
	// RVA: 0x4121a6c VA: 0x7596739a6c
	public Void SetMaxAngleAisacDelta(Single maxDelta) { }
	// RVA: 0x4118780 VA: 0x7596730780
	public Void SetAttenuationDistanceSetting(Boolean flag) { }
	// RVA: 0x41187a4 VA: 0x75967307a4
	public Boolean GetAttenuationDistanceSetting() { }
	// RVA: 0x41182e4 VA: 0x75967302e4
	public Void SetRandomPositionConfig(Nullable`1 config) { }
	// RVA: 0x4121d48 VA: 0x7596739d48
	public Void SetRandomPositionList(Vector3[] positionList) { }
	// RVA: 0x4118454 VA: 0x7596730454
	public Void Set3dRegion(CriAtomEx3dRegion region3d) { }
	// RVA: 0x4121fa0 VA: 0x7596739fa0
	public Void SetListenerBasedElevationAngleAisacControlId(UInt16 aisacControlId) { }
	// RVA: 0x412202c VA: 0x759673a02c
	public Void SetSourceBasedElevationAngleAisacControlId(UInt16 aisacControlId) { }
	// RVA: 0x41220b8 VA: 0x759673a0b8
	public Void SetDistanceAisacControlId(UInt16 aisacControlId) { }
	// RVA: 0x4122144 VA: 0x759673a144
	public Boolean IsDestroyable() { }
	// RVA: 0x41221d0 VA: 0x759673a1d0
	public NativeVector GetPosition() { }
	// RVA: 0x4122254 VA: 0x759673a254
	protected override Void Finalize() { }
	// RVA: 0x41211e0 VA: 0x75967391e0
	private static extern IntPtr criAtomEx3dSource_Create(ref Config config, IntPtr work, Int32 work_size) { }
	// RVA: 0x4121394 VA: 0x7596739394
	private static extern Void criAtomEx3dSource_Destroy(IntPtr ex_3d_source) { }
	// RVA: 0x4121418 VA: 0x7596739418
	private static extern Void criAtomEx3dSource_Update(IntPtr ex_3d_source) { }
	// RVA: 0x412149c VA: 0x759673949c
	private static extern Void criAtomEx3dSource_ResetParameters(IntPtr ex_3d_source) { }
	// RVA: 0x4121518 VA: 0x7596739518
	private static extern Void criAtomEx3dSource_SetPosition(IntPtr ex_3d_source, ref NativeVector position) { }
	// RVA: 0x412159c VA: 0x759673959c
	private static extern Void criAtomEx3dSource_SetVelocity(IntPtr ex_3d_source, ref NativeVector velocity) { }
	// RVA: 0x4121620 VA: 0x7596739620
	private static extern Void criAtomEx3dSource_SetOrientation(IntPtr ex_3d_source, ref NativeVector front, ref NativeVector top) { }
	// RVA: 0x41216dc VA: 0x75967396dc
	private static extern Void criAtomEx3dSource_SetConeOrientation(IntPtr ex_3d_source, ref NativeVector cone_orient) { }
	// RVA: 0x4121768 VA: 0x7596739768
	private static extern Void criAtomEx3dSource_SetConeParameter(IntPtr ex_3d_source, Single inside_angle, Single outside_angle, Single outside_volume) { }
	// RVA: 0x4121814 VA: 0x7596739814
	private static extern Void criAtomEx3dSource_SetMinMaxAttenuationDistance(IntPtr ex_3d_source, Single min_distance, Single max_distance) { }
	// RVA: 0x41218b0 VA: 0x75967398b0
	private static extern Void criAtomEx3dSource_SetInteriorPanField(IntPtr ex_3d_source, Single source_radius, Single interior_distance) { }
	// RVA: 0x412194c VA: 0x759673994c
	private static extern Void criAtomEx3dSource_SetDopplerFactor(IntPtr ex_3d_source, Single doppler_factor) { }
	// RVA: 0x41219e0 VA: 0x75967399e0
	private static extern Void criAtomEx3dSource_SetVolume(IntPtr ex_3d_source, Single volume) { }
	// RVA: 0x4121a74 VA: 0x7596739a74
	private static extern Void criAtomEx3dSource_SetMaxAngleAisacDelta(IntPtr ex_3d_source, Single max_delta) { }
	// RVA: 0x4121b00 VA: 0x7596739b00
	private static extern Void criAtomEx3dSource_SetAttenuationDistanceSetting(IntPtr ex_3d_source, Boolean flag) { }
	// RVA: 0x4121b84 VA: 0x7596739b84
	private static extern Boolean criAtomEx3dSource_GetAttenuationDistanceSetting(IntPtr ex_3d_source) { }
	// RVA: 0x4121c8c VA: 0x7596739c8c
	private static extern Void criAtomEx3dSource_SetRandomPositionConfig(IntPtr ex_3d_source, ref Randomize3dConfig config) { }
	// RVA: 0x4121c08 VA: 0x7596739c08
	private static extern Void criAtomEx3dSource_SetRandomPositionConfig(IntPtr ex_3d_source, IntPtr config) { }
	// RVA: 0x4121e80 VA: 0x7596739e80
	private static extern Void criAtomEx3dSource_SetRandomPositionList(IntPtr ex_3d_source, NativeVector[] position_list, UInt32 length) { }
	// RVA: 0x41220c0 VA: 0x759673a0c0
	private static extern Void criAtomEx3dSource_SetDistanceAisacControlId(IntPtr ex_3d_source, UInt16 aisac_control_id) { }
	// RVA: 0x412214c VA: 0x759673a14c
	private static extern Boolean criAtomEx3dSource_IsDestroyable(IntPtr ex_3d_source) { }
	// RVA: 0x41221d8 VA: 0x759673a1d8
	private static extern NativeVector criAtomEx3dSource_GetPosition(IntPtr ex_3d_source) { }
	// RVA: 0x4121f1c VA: 0x7596739f1c
	private static extern Void criAtomEx3dSource_Set3dRegionHn(IntPtr ex_3d_source, IntPtr ex_3d_region) { }
	// RVA: 0x4121fa8 VA: 0x7596739fa8
	private static extern Void criAtomEx3dSource_SetListenerBasedElevationAngleAisacControlId(IntPtr ex_3d_source, UInt16 aisac_control_id) { }
	// RVA: 0x4122034 VA: 0x759673a034
	private static extern Void criAtomEx3dSource_SetSourceBasedElevationAngleAisacControlId(IntPtr ex_3d_source, UInt16 aisac_control_id) { }
}
```