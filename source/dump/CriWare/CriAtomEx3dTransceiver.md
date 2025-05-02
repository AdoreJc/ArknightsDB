# CriAtomEx3dTransceiver

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`


## Properties

- `IntPtr nativeHandle`


## Methods

- `Void Dispose(Boolean)`

- `IntPtr get_nativeHandle()`

- `Void Update()`

- `Void SetInputPosition(Vector3)`

- `Void SetOutputPosition(Vector3)`

- `Void SetInputOrientation(Vector3, Vector3)`

- `Void SetOutputOrientation(Vector3, Vector3)`

- `Void SetOutputConeParameter(Single, Single, Single)`

- `Void SetOutputMinMaxDistance(Single, Single)`

- `Void SetOutputInteriorPanField(Single, Single)`

- `Void SetInputCrossFadeField(Single, Single)`

- `Void SetOutputVolume(Single)`

- `Void AttachAisac(String)`

- `Void DetachAisac(String)`

- `Void SetMaxAngleAisacDelta(Single)`

- `Void SetDistanceAisacControlId(UInt16)`

- `Void SetListenerBasedAzimuthAngleAisacControlId(UInt16)`

- `Void SetListenerBasedElevationAngleAisacControlId(UInt16)`

- `Void SetTransceiverOutputBasedAzimuthAngleAisacControlId(UInt16)`

- `Void SetTransceiverOutputBasedElevationAngleAisacControlId(UInt16)`

- `Void Set3dRegion(CriAtomEx3dRegion)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomEx3dTransceiver : CriDisposable
{
	private IntPtr handle; // 0x20

	public IntPtr nativeHandle { get; }

	// RVA: 0x4119390 VA: 0x7596731390
	public Void .ctor() { }
	// RVA: 0x4122380 VA: 0x759673a380
	public override Void Dispose() { }
	// RVA: 0x4122388 VA: 0x759673a388
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x41224f8 VA: 0x759673a4f8
	public IntPtr get_nativeHandle() { }
	// RVA: 0x4119238 VA: 0x7596731238
	public Void Update() { }
	// RVA: 0x4119b10 VA: 0x7596731b10
	public Void SetInputPosition(Vector3 position) { }
	// RVA: 0x4119ab4 VA: 0x7596731ab4
	public Void SetOutputPosition(Vector3 position) { }
	// RVA: 0x4119b38 VA: 0x7596731b38
	public Void SetInputOrientation(Vector3 front, Vector3 top) { }
	// RVA: 0x4119adc VA: 0x7596731adc
	public Void SetOutputOrientation(Vector3 front, Vector3 top) { }
	// RVA: 0x4119b7c VA: 0x7596731b7c
	public Void SetOutputConeParameter(Single insideAngle, Single outsideAngle, Single outsideVolume) { }
	// RVA: 0x4119b8c VA: 0x7596731b8c
	public Void SetOutputMinMaxDistance(Single minDistance, Single maxDistance) { }
	// RVA: 0x4119b84 VA: 0x7596731b84
	public Void SetOutputInteriorPanField(Single radius, Single interiorDistance) { }
	// RVA: 0x4119b74 VA: 0x7596731b74
	public Void SetInputCrossFadeField(Single directAudioRadius, Single crossfadeDistance) { }
	// RVA: 0x4119b6c VA: 0x7596731b6c
	public Void SetOutputVolume(Single volume) { }
	// RVA: 0x4119b94 VA: 0x7596731b94
	public Void AttachAisac(String globalAisacName) { }
	// RVA: 0x4122b30 VA: 0x759673ab30
	public Void DetachAisac(String globalAisacName) { }
	// RVA: 0x4119b9c VA: 0x7596731b9c
	public Void SetMaxAngleAisacDelta(Single maxDelta) { }
	// RVA: 0x4122c5c VA: 0x759673ac5c
	public Void SetDistanceAisacControlId(UInt16 aisacControlId) { }
	// RVA: 0x4122ce8 VA: 0x759673ace8
	public Void SetListenerBasedAzimuthAngleAisacControlId(UInt16 aisacControlId) { }
	// RVA: 0x4122d74 VA: 0x759673ad74
	public Void SetListenerBasedElevationAngleAisacControlId(UInt16 aisacControlId) { }
	// RVA: 0x4122e00 VA: 0x759673ae00
	public Void SetTransceiverOutputBasedAzimuthAngleAisacControlId(UInt16 aisacControlId) { }
	// RVA: 0x4122e8c VA: 0x759673ae8c
	public Void SetTransceiverOutputBasedElevationAngleAisacControlId(UInt16 aisacControlId) { }
	// RVA: 0x41191d8 VA: 0x75967311d8
	public Void Set3dRegion(CriAtomEx3dRegion region3d) { }
	// RVA: 0x4122f9c VA: 0x759673af9c
	protected override Void Finalize() { }
}
```