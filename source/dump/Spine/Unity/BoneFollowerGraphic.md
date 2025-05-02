# BoneFollowerGraphic

**Namespace:** `Spine.Unity`


## Fields

- `SkeletonGraphic skeletonGraphic`

- `Boolean initializeOnAwake`

- `String boneName`

- `Boolean followBoneRotation`

- `Boolean followSkeletonFlip`

- `Boolean followLocalScale`

- `Boolean followXYPosition`

- `Boolean followZPosition`

- `AxisOrientation maintainedAxisOrientation`

- `Bone bone`

- `Transform skeletonTransform`

- `Boolean skeletonTransformIsParent`

- `Boolean valid`


## Properties

- `SkeletonGraphic SkeletonGraphic`


## Methods

- `SkeletonGraphic get_SkeletonGraphic()`

- `Void set_SkeletonGraphic(SkeletonGraphic)`

- `Boolean SetBone(String)`

- `Void Awake()`

- `Void Initialize()`

- `Void LateUpdate()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class BoneFollowerGraphic : MonoBehaviour
{
	public SkeletonGraphic skeletonGraphic; // 0x18
	public Boolean initializeOnAwake; // 0x20
	public String boneName; // 0x28
	public Boolean followBoneRotation; // 0x30
	public Boolean followSkeletonFlip; // 0x31
	public Boolean followLocalScale; // 0x32
	public Boolean followXYPosition; // 0x33
	public Boolean followZPosition; // 0x34
	public AxisOrientation maintainedAxisOrientation; // 0x38
	public Bone bone; // 0x40
	private Transform skeletonTransform; // 0x48
	private Boolean skeletonTransformIsParent; // 0x50
	public Boolean valid; // 0x51

	public SkeletonGraphic SkeletonGraphic { get; set; }

	// RVA: 0x61fc694 VA: 0x7598814694
	public SkeletonGraphic get_SkeletonGraphic() { }
	// RVA: 0x61fc69c VA: 0x759881469c
	public Void set_SkeletonGraphic(SkeletonGraphic value) { }
	// RVA: 0x61fc7f8 VA: 0x75988147f8
	public Boolean SetBone(String name) { }
	// RVA: 0x61fc908 VA: 0x7598814908
	public Void Awake() { }
	// RVA: 0x61fc6b8 VA: 0x75988146b8
	public Void Initialize() { }
	// RVA: 0x61fc928 VA: 0x7598814928
	public Void LateUpdate() { }
	// RVA: 0x61fcef0 VA: 0x7598814ef0
	public Void .ctor() { }
}
```