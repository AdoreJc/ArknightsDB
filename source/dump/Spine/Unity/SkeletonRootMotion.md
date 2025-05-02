# SkeletonRootMotion

**Namespace:** `Spine.Unity`


## Fields

- `Int32 animationTrackFlags`

- `AnimationState animationState`

- `Canvas canvas`


## Methods

- `Void ApplyMixAlphaToDelta(ref, TrackEntry, TrackEntry)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine.Unity
public class SkeletonRootMotion : SkeletonRootMotionBase
{
	private const Int32 DefaultAnimationTrackFlags; // 0x0
	public Int32 animationTrackFlags; // 0x80
	private AnimationState animationState; // 0x88
	private Canvas canvas; // 0x90

	protected override Single AdditionalScale { get; }

	// RVA: 0x6201000 VA: 0x7598819000
	public override Vector2 GetRemainingRootMotion(Int32 trackIndex) { }
	// RVA: 0x6201088 VA: 0x7598819088
	public override RootMotionInfo GetRootMotionInfo(Int32 trackIndex) { }
	// RVA: 0x6201104 VA: 0x7598819104
	protected override Single get_AdditionalScale() { }
	// RVA: 0x6201188 VA: 0x7598819188
	protected override Void Reset() { }
	// RVA: 0x62011a4 VA: 0x75988191a4
	protected override Void Start() { }
	// RVA: 0x6201328 VA: 0x7598819328
	protected override Vector2 CalculateAnimationsMovementDelta() { }
	// RVA: 0x62014c0 VA: 0x75988194c0
	private Void ApplyMixAlphaToDelta(ref Vector2 currentDelta, TrackEntry next, TrackEntry track) { }
	// RVA: 0x6201584 VA: 0x7598819584
	public Void .ctor() { }
}
```