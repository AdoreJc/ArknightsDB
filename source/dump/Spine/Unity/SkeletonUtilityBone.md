# SkeletonUtilityBone

**Namespace:** `Spine.Unity`


## Fields

- `String boneName`

- `Transform parentReference`

- `Mode mode`

- `Boolean position`

- `Boolean rotation`

- `Boolean scale`

- `Boolean zPosition`

- `Single overrideAlpha`

- `SkeletonUtility hierarchy`

- `Bone bone`

- `Boolean transformLerpComplete`

- `Boolean valid`

- `Transform cachedTransform`

- `Transform skeletonTransform`

- `Boolean incompatibleTransformMode`


## Properties

- `Boolean IncompatibleTransformMode`


## Methods

- `Boolean get_IncompatibleTransformMode()`

- `Void Reset()`

- `Void OnEnable()`

- `Void HandleOnReset()`

- `Void OnDisable()`

- `Void DoUpdate(UpdatePhase)`

- `Void AddBoundingBox(String, String, String)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SkeletonUtilityBone : MonoBehaviour
{
	public String boneName; // 0x18
	public Transform parentReference; // 0x20
	public Mode mode; // 0x28
	public Boolean position; // 0x2c
	public Boolean rotation; // 0x2d
	public Boolean scale; // 0x2e
	public Boolean zPosition; // 0x2f
	public Single overrideAlpha; // 0x30
	public SkeletonUtility hierarchy; // 0x38
	public Bone bone; // 0x40
	public Boolean transformLerpComplete; // 0x48
	public Boolean valid; // 0x49
	private Transform cachedTransform; // 0x50
	private Transform skeletonTransform; // 0x58
	private Boolean incompatibleTransformMode; // 0x60

	public Boolean IncompatibleTransformMode { get; }

	// RVA: 0x6217b7c VA: 0x759882fb7c
	public Boolean get_IncompatibleTransformMode() { }
	// RVA: 0x621780c VA: 0x759882f80c
	public Void Reset() { }
	// RVA: 0x6217b84 VA: 0x759882fb84
	private Void OnEnable() { }
	// RVA: 0x6217cd4 VA: 0x759882fcd4
	private Void HandleOnReset() { }
	// RVA: 0x6217cd8 VA: 0x759882fcd8
	private Void OnDisable() { }
	// RVA: 0x6216648 VA: 0x759882e648
	public Void DoUpdate(UpdatePhase phase) { }
	// RVA: 0x6217db4 VA: 0x759882fdb4
	public static Boolean BoneTransformModeIncompatible(Bone bone) { }
	// RVA: 0x6217de4 VA: 0x759882fde4
	public Void AddBoundingBox(String skinName, String slotName, String attachmentName) { }
	// RVA: 0x6217e64 VA: 0x759882fe64
	public Void .ctor() { }
}
```