# PointFollower

**Namespace:** `Spine.Unity`


## Fields

- `SkeletonRenderer skeletonRenderer`

- `String slotName`

- `String pointAttachmentName`

- `Boolean followRotation`

- `Boolean followSkeletonFlip`

- `Boolean followSkeletonZPosition`

- `Transform skeletonTransform`

- `Boolean skeletonTransformIsParent`

- `PointAttachment point`

- `Bone bone`

- `Boolean valid`


## Properties

- `SkeletonRenderer SkeletonRenderer`

- `ISkeletonComponent SkeletonComponent`

- `Boolean IsValid`


## Methods

- `SkeletonRenderer get_SkeletonRenderer()`

- `ISkeletonComponent get_SkeletonComponent()`

- `Boolean get_IsValid()`

- `Void Initialize()`

- `Void HandleRebuildRenderer(SkeletonRenderer)`

- `Void UpdateReferences()`

- `Void OnDestroy()`

- `Void LateUpdate()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class PointFollower : MonoBehaviour, IHasSkeletonRenderer, IHasSkeletonComponent
{
	public SkeletonRenderer skeletonRenderer; // 0x18
	public String slotName; // 0x20
	public String pointAttachmentName; // 0x28
	public Boolean followRotation; // 0x30
	public Boolean followSkeletonFlip; // 0x31
	public Boolean followSkeletonZPosition; // 0x32
	private Transform skeletonTransform; // 0x38
	private Boolean skeletonTransformIsParent; // 0x40
	private PointAttachment point; // 0x48
	private Bone bone; // 0x50
	private Boolean valid; // 0x58

	public SkeletonRenderer SkeletonRenderer { get; }
	public ISkeletonComponent SkeletonComponent { get; }
	public Boolean IsValid { get; }

	// RVA: 0x61ffc34 VA: 0x7598817c34
	public SkeletonRenderer get_SkeletonRenderer() { }
	// RVA: 0x61ffc3c VA: 0x7598817c3c
	public ISkeletonComponent get_SkeletonComponent() { }
	// RVA: 0x61ffc44 VA: 0x7598817c44
	public Boolean get_IsValid() { }
	// RVA: 0x61ffc4c VA: 0x7598817c4c
	public Void Initialize() { }
	// RVA: 0x61fff58 VA: 0x7598817f58
	private Void HandleRebuildRenderer(SkeletonRenderer skeletonRenderer) { }
	// RVA: 0x61ffce0 VA: 0x7598817ce0
	private Void UpdateReferences() { }
	// RVA: 0x61fff84 VA: 0x7598817f84
	private Void OnDestroy() { }
	// RVA: 0x6200054 VA: 0x7598818054
	public Void LateUpdate() { }
	// RVA: 0x6200370 VA: 0x7598818370
	public Void .ctor() { }
}
```