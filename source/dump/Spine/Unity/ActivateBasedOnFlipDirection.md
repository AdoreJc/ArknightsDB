# ActivateBasedOnFlipDirection

**Namespace:** `Spine.Unity`


## Fields

- `SkeletonRenderer skeletonRenderer`

- `SkeletonGraphic skeletonGraphic`

- `GameObject activeOnNormalX`

- `GameObject activeOnFlippedX`

- `ISkeletonComponent skeletonComponent`

- `Boolean wasFlippedXBefore`


## Methods

- `Void Start()`

- `Void FixedUpdate()`

- `Void HandleFlip(Boolean)`

- `Void ResetJointPositions(HingeJoint2D[])`

- `Void CompensateMovementAfterFlipX(Transform, Transform)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class ActivateBasedOnFlipDirection : MonoBehaviour
{
	public SkeletonRenderer skeletonRenderer; // 0x18
	public SkeletonGraphic skeletonGraphic; // 0x20
	public GameObject activeOnNormalX; // 0x28
	public GameObject activeOnFlippedX; // 0x30
	private HingeJoint2D[] jointsNormalX; // 0x38
	private HingeJoint2D[] jointsFlippedX; // 0x40
	private ISkeletonComponent skeletonComponent; // 0x48
	private Boolean wasFlippedXBefore; // 0x50


	// RVA: 0x6213920 VA: 0x759882b920
	private Void Start() { }
	// RVA: 0x6213a00 VA: 0x759882ba00
	private Void FixedUpdate() { }
	// RVA: 0x6213ad8 VA: 0x759882bad8
	private Void HandleFlip(Boolean isFlippedX) { }
	// RVA: 0x6213b90 VA: 0x759882bb90
	private Void ResetJointPositions(HingeJoint2D[] joints) { }
	// RVA: 0x6213c4c VA: 0x759882bc4c
	private Void CompensateMovementAfterFlipX(Transform toActivate, Transform toDeactivate) { }
	// RVA: 0x6213d14 VA: 0x759882bd14
	public Void .ctor() { }
}
```