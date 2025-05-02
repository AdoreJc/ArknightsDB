# CriAtomTransceiver

**Namespace:** `CriWare`


## Fields

- `CriAtomEx3dTransceiver <transceiverHn>k__BackingField`

- `Vector3 <inputPos>k__BackingField`

- `Vector3 <inputFront>k__BackingField`

- `Vector3 <inputUp>k__BackingField`

- `CriAtomRegion regionOnStart`

- `Boolean useDedicatedInput`

- `GameObject dedicatedInput`

- `Single outputVolume`

- `Single directAudioRadius`

- `Single crossFadeDistance`

- `Single coneInsideAngle`

- `Single coneOutsideAngle`

- `Single coneOutsideVolume`

- `Single transceiverRadius`

- `Single interiorDistance`

- `Single minAttenuation`

- `Single maxAttenuation`

- `String globalAisacName`

- `Single maxAngleAisacDelta`

- `String distanceAisacControlId`

- `String listenerAzimuthAisacControlId`

- `String listenerElevationAisacControlId`

- `String outputAzimuthAisacControlId`

- `String outputElevationAisacControlId`

- `Boolean inspectorAisacSettingFoldout`

- `Boolean isInitialized`

- `Boolean dedicatedInputNotSetWarned`

- `CriAtomRegion currentRegion`


## Properties

- `CriAtomEx3dTransceiver transceiverHn`

- `Vector3 inputPos`

- `Vector3 inputFront`

- `Vector3 inputUp`

- `CriAtomRegion region3d`


## Methods

- `CriAtomEx3dTransceiver get_transceiverHn()`

- `Void set_transceiverHn(CriAtomEx3dTransceiver)`

- `Vector3 get_inputPos()`

- `Void set_inputPos(Vector3)`

- `Vector3 get_inputFront()`

- `Void set_inputFront(Vector3)`

- `Vector3 get_inputUp()`

- `Void set_inputUp(Vector3)`

- `CriAtomRegion get_region3d()`

- `Void set_region3d(CriAtomRegion)`

- `Void Awake()`

- `Void Start()`

- `Void OnDestroy()`

- `Void ApplyCurrentPosition()`

- `Void ApplyParameters()`

- `Void TrySetAisacControlId(String, SetControlIdMethod)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomTransceiver : CriMonoBehaviour
{
	private CriAtomEx3dTransceiver <transceiverHn>k__BackingField; // 0x28
	private Vector3 <inputPos>k__BackingField; // 0x30
	private Vector3 <inputFront>k__BackingField; // 0x3c
	private Vector3 <inputUp>k__BackingField; // 0x48
	private CriAtomRegion regionOnStart; // 0x58
	private Boolean useDedicatedInput; // 0x60
	private GameObject dedicatedInput; // 0x68
	private Single outputVolume; // 0x70
	private Single directAudioRadius; // 0x74
	private Single crossFadeDistance; // 0x78
	private Single coneInsideAngle; // 0x7c
	private Single coneOutsideAngle; // 0x80
	private Single coneOutsideVolume; // 0x84
	private Single transceiverRadius; // 0x88
	private Single interiorDistance; // 0x8c
	public Single minAttenuation; // 0x90
	public Single maxAttenuation; // 0x94
	private String globalAisacName; // 0x98
	private Single maxAngleAisacDelta; // 0xa0
	private String distanceAisacControlId; // 0xa8
	private String listenerAzimuthAisacControlId; // 0xb0
	private String listenerElevationAisacControlId; // 0xb8
	private String outputAzimuthAisacControlId; // 0xc0
	private String outputElevationAisacControlId; // 0xc8
	public Boolean inspectorAisacSettingFoldout; // 0xd0
	private Boolean isInitialized; // 0xd1
	private Boolean dedicatedInputNotSetWarned; // 0xd2
	private CriAtomRegion currentRegion; // 0xd8

	public CriAtomEx3dTransceiver transceiverHn { get; set; }
	public Vector3 inputPos { get; set; }
	public Vector3 inputFront { get; set; }
	public Vector3 inputUp { get; set; }
	public CriAtomRegion region3d { get; set; }

	// RVA: 0x4119178 VA: 0x7596731178
	public CriAtomEx3dTransceiver get_transceiverHn() { }
	// RVA: 0x4119180 VA: 0x7596731180
	protected Void set_transceiverHn(CriAtomEx3dTransceiver value) { }
	// RVA: 0x4119188 VA: 0x7596731188
	public Vector3 get_inputPos() { }
	// RVA: 0x4119194 VA: 0x7596731194
	private Void set_inputPos(Vector3 value) { }
	// RVA: 0x41191a0 VA: 0x75967311a0
	public Vector3 get_inputFront() { }
	// RVA: 0x41191ac VA: 0x75967311ac
	private Void set_inputFront(Vector3 value) { }
	// RVA: 0x41191b8 VA: 0x75967311b8
	public Vector3 get_inputUp() { }
	// RVA: 0x41191c4 VA: 0x75967311c4
	private Void set_inputUp(Vector3 value) { }
	// RVA: 0x41191d0 VA: 0x75967311d0
	public CriAtomRegion get_region3d() { }
	// RVA: 0x4117528 VA: 0x759672f528
	public Void set_region3d(CriAtomRegion value) { }
	// RVA: 0x4119240 VA: 0x7596731240
	private Void Awake() { }
	// RVA: 0x411924c VA: 0x759673124c
	private Void Start() { }
	// RVA: 0x41192c8 VA: 0x75967312c8
	protected override Void OnEnable() { }
	// RVA: 0x41192ec VA: 0x75967312ec
	private Void OnDestroy() { }
	// RVA: 0x41192f8 VA: 0x75967312f8
	protected virtual Void InternalInitialize() { }
	// RVA: 0x4119448 VA: 0x7596731448
	protected virtual Void InternalFinalize() { }
	// RVA: 0x41194d0 VA: 0x75967314d0
	protected virtual Void InitializeParameters() { }
	// RVA: 0x4119aac VA: 0x7596731aac
	public override Void CriInternalUpdate() { }
	// RVA: 0x4119ab0 VA: 0x7596731ab0
	public override Void CriInternalLateUpdate() { }
	// RVA: 0x4119560 VA: 0x7596731560
	private Void ApplyCurrentPosition() { }
	// RVA: 0x4119834 VA: 0x7596731834
	private Void ApplyParameters() { }
	// RVA: 0x4119c78 VA: 0x7596731c78
	private Void TrySetAisacControlId(String strId, SetControlIdMethod callback) { }
	// RVA: 0x4119d94 VA: 0x7596731d94
	public Void .ctor() { }
}
```