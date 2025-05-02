# CriAtomListener

**Namespace:** `CriWare`


## Fields

- `CriAtomEx3dListener <nativeListener>k__BackingField`

- `CriAtomRegion regionOnStart`

- `Boolean activateListenerOnEnable`

- `Vector3 lastPosition`

- `CriAtomRegion currentRegion`

- `Boolean _isActive`


## Properties

- `CriAtomEx3dListener nativeListener`

- `Boolean isActive`

- `CriAtomRegion region3d`


## Methods

- `CriAtomEx3dListener get_nativeListener()`

- `Void set_nativeListener(CriAtomEx3dListener)`

- `Boolean get_isActive()`

- `Void set_isActive(Boolean)`

- `CriAtomRegion get_region3d()`

- `Void set_region3d(CriAtomRegion)`

- `Void Awake()`

- `Void Start()`

- `Void OnDestroy()`

- `Void UpdatePosition()`

- `Void ActivateListener(Boolean)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomListener : CriMonoBehaviour
{
	private CriAtomEx3dListener <nativeListener>k__BackingField; // 0x28
	private CriAtomRegion regionOnStart; // 0x30
	public Boolean activateListenerOnEnable; // 0x38
	private static List`1 listenersList; // 0x0
	private static CriAtomListener exclusiveListener; // 0x8
	private static CriAtomEx3dListener dummyNativeListener; // 0x10
	private Vector3 lastPosition; // 0x3c
	private CriAtomRegion currentRegion; // 0x48
	private Boolean _isActive; // 0x50

	public CriAtomEx3dListener nativeListener { get; set; }
	public Boolean isActive { get; set; }
	public CriAtomRegion region3d { get; set; }
	internal static CriAtomEx3dListener DummyNativeListener { get; }

	// RVA: 0x4113d5c VA: 0x759672bd5c
	public static Void CreateDummyNativeListener() { }
	// RVA: 0x4113e80 VA: 0x759672be80
	public static Void DestroyDummyNativeListener() { }
	// RVA: 0x4115014 VA: 0x759672d014
	public CriAtomEx3dListener get_nativeListener() { }
	// RVA: 0x411501c VA: 0x759672d01c
	protected Void set_nativeListener(CriAtomEx3dListener value) { }
	// RVA: 0x4115024 VA: 0x759672d024
	public Boolean get_isActive() { }
	// RVA: 0x411502c VA: 0x759672d02c
	public Void set_isActive(Boolean value) { }
	// RVA: 0x41152dc VA: 0x759672d2dc
	public CriAtomRegion get_region3d() { }
	// RVA: 0x41152e4 VA: 0x759672d2e4
	public Void set_region3d(CriAtomRegion value) { }
	// RVA: 0x41155b8 VA: 0x759672d5b8
	internal static CriAtomEx3dListener get_DummyNativeListener() { }
	// RVA: 0x4115610 VA: 0x759672d610
	private Void Awake() { }
	// RVA: 0x411578c VA: 0x759672d78c
	private Void Start() { }
	// RVA: 0x4115808 VA: 0x759672d808
	protected override Void OnEnable() { }
	// RVA: 0x4115ac0 VA: 0x759672dac0
	protected override Void OnDisable() { }
	// RVA: 0x4115b9c VA: 0x759672db9c
	private Void OnDestroy() { }
	// RVA: 0x4115c90 VA: 0x759672dc90
	public override Void CriInternalUpdate() { }
	// RVA: 0x4115c94 VA: 0x759672dc94
	public override Void CriInternalLateUpdate() { }
	// RVA: 0x4115090 VA: 0x759672d090
	private Void UpdatePosition() { }
	// RVA: 0x4115828 VA: 0x759672d828
	public Void ActivateListener(Boolean exclusive) { }
	// RVA: 0x4115e04 VA: 0x759672de04
	public Void .ctor() { }
	// RVA: 0x4115e14 VA: 0x759672de14
	private static Void .cctor() { }
}
```