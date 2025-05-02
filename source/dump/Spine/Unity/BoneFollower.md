# BoneFollower

**Namespace:** `Spine.Unity`


## Fields

- `Boolean <EnableManualUpdate>k__BackingField`

- `SkeletonRenderer skeletonRenderer`

- `String boneName`

- `Boolean followXYPosition`

- `Boolean followZPosition`

- `Boolean followBoneRotation`

- `Boolean followSkeletonFlip`

- `Boolean followLocalScale`

- `AxisOrientation maintainedAxisOrientation`

- `Boolean initializeOnAwake`

- `Boolean valid`

- `Bone bone`

- `Transform skeletonTransform`

- `Boolean skeletonTransformIsParent`


## Properties

- `Boolean EnableManualUpdate`

- `SkeletonRenderer SkeletonRenderer`


## Methods

- `Boolean get_EnableManualUpdate()`

- `Void set_EnableManualUpdate(Boolean)`

- `SkeletonRenderer get_SkeletonRenderer()`

- `Void set_SkeletonRenderer(SkeletonRenderer)`

- `Boolean SetBone(String)`

- `Void Awake()`

- `Void HandleRebuildRenderer(SkeletonRenderer)`

- `Void Initialize()`

- `Void OnDestroy()`

- `Void LateUpdate()`

- `Void DoLateUpdate()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class BoneFollower : MonoBehaviour
{
	private Boolean <EnableManualUpdate>k__BackingField; // 0x18
	public SkeletonRenderer skeletonRenderer; // 0x20
	public String boneName; // 0x28
	public Boolean followXYPosition; // 0x30
	public Boolean followZPosition; // 0x31
	public Boolean followBoneRotation; // 0x32
	public Boolean followSkeletonFlip; // 0x33
	public Boolean followLocalScale; // 0x34
	public AxisOrientation maintainedAxisOrientation; // 0x38
	public Boolean initializeOnAwake; // 0x3c
	public Boolean valid; // 0x3d
	public Bone bone; // 0x40
	private Transform skeletonTransform; // 0x48
	private Boolean skeletonTransformIsParent; // 0x50

	public Boolean EnableManualUpdate { get; set; }
	public SkeletonRenderer SkeletonRenderer { get; set; }

	// RVA: 0x61fbc60 VA: 0x7598813c60
	public Boolean get_EnableManualUpdate() { }
	// RVA: 0x61fbc68 VA: 0x7598813c68
	public Void set_EnableManualUpdate(Boolean value) { }
	// RVA: 0x61fbc74 VA: 0x7598813c74
	public SkeletonRenderer get_SkeletonRenderer() { }
	// RVA: 0x61fbc7c VA: 0x7598813c7c
	public Void set_SkeletonRenderer(SkeletonRenderer value) { }
	// RVA: 0x61fbe6c VA: 0x7598813e6c
	public Boolean SetBone(String name) { }
	// RVA: 0x61fbf54 VA: 0x7598813f54
	public Void Awake() { }
	// RVA: 0x61fbf64 VA: 0x7598813f64
	public Void HandleRebuildRenderer(SkeletonRenderer skeletonRenderer) { }
	// RVA: 0x61fbc98 VA: 0x7598813c98
	public Void Initialize() { }
	// RVA: 0x61fc0a0 VA: 0x75988140a0
	private Void OnDestroy() { }
	// RVA: 0x61fc170 VA: 0x7598814170
	public Void LateUpdate() { }
	// RVA: 0x61fc180 VA: 0x7598814180
	public Void DoLateUpdate() { }
	// RVA: 0x61fc678 VA: 0x7598814678
	public Void .ctor() { }
}
```