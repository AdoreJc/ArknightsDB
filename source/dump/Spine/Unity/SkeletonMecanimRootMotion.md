# SkeletonMecanimRootMotion

**Namespace:** `Spine.Unity`


## Fields

- `Int32 mecanimLayerFlags`

- `Vector2 movementDelta`

- `SkeletonMecanim skeletonMecanim`


## Properties

- `SkeletonMecanim SkeletonMecanim`


## Methods

- `SkeletonMecanim get_SkeletonMecanim()`

- `Void OnClipApplied(Animation, Int32, Single, Single, Single, Boolean)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SkeletonMecanimRootMotion : SkeletonRootMotionBase
{
	private const Int32 DefaultMecanimLayerFlags; // 0x0
	public Int32 mecanimLayerFlags; // 0x80
	protected Vector2 movementDelta; // 0x84
	private SkeletonMecanim skeletonMecanim; // 0x90

	public SkeletonMecanim SkeletonMecanim { get; }

	// RVA: 0x6200380 VA: 0x7598818380
	public SkeletonMecanim get_SkeletonMecanim() { }
	// RVA: 0x6200430 VA: 0x7598818430
	public override Vector2 GetRemainingRootMotion(Int32 layerIndex) { }
	// RVA: 0x620075c VA: 0x759881875c
	public override RootMotionInfo GetRootMotionInfo(Int32 layerIndex) { }
	// RVA: 0x6200950 VA: 0x7598818950
	protected override Void Reset() { }
	// RVA: 0x6200970 VA: 0x7598818970
	protected override Void Start() { }
	// RVA: 0x6200e08 VA: 0x7598818e08
	private Void OnClipApplied(Animation animation, Int32 layerIndex, Single weight, Single time, Single lastTime, Boolean playsBackward) { }
	// RVA: 0x6200e90 VA: 0x7598818e90
	protected override Vector2 CalculateAnimationsMovementDelta() { }
	// RVA: 0x6200ef4 VA: 0x7598818ef4
	public Void .ctor() { }
}
```