# MecanimTranslator

**Namespace:** ` `


## Fields

- `Boolean autoReset`

- `Boolean useCustomMixMode`

- `OnClipAppliedDelegate _OnClipApplied`

- `Animator animator`


## Properties

- `Animator Animator`

- `Int32 MecanimLayerCount`


## Methods

- `Void add__OnClipApplied(OnClipAppliedDelegate)`

- `Void remove__OnClipApplied(OnClipAppliedDelegate)`

- `Void add_OnClipApplied(OnClipAppliedDelegate)`

- `Void remove_OnClipApplied(OnClipAppliedDelegate)`

- `Animator get_Animator()`

- `Int32 get_MecanimLayerCount()`

- `Void Initialize(Animator, SkeletonDataAsset)`

- `Boolean ApplyAnimation(Skeleton, AnimatorClipInfo, AnimatorStateInfo, Int32, Single, MixBlend, Boolean)`

- `Boolean ApplyInterruptionAnimation(Skeleton, Boolean, AnimatorClipInfo, AnimatorStateInfo, Int32, Single, MixBlend, Single, Boolean)`

- `Void OnClipAppliedCallback(Animation, AnimatorStateInfo, Int32, Single, Boolean, Single)`

- `Void Apply(Skeleton)`

- `Void InitClipInfosForLayers()`

- `Void ClearClipInfosForLayers()`

- `MixMode GetMixMode(Int32, MixBlend)`

- `Void GetStateUpdatesFromAnimator(Int32)`

- `Void GetAnimatorClipInfos(Int32, out, out, out, out, out, out, out, out)`

- `Void GetAnimatorStateInfos(Int32, out, out, out, out, out)`

- `Animation GetAnimation(AnimationClip)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : 
public class MecanimTranslator
{
	private const Single WeightEpsilon; // 0x0
	public Boolean autoReset; // 0x10
	public Boolean useCustomMixMode; // 0x11
	public MixMode[] layerMixModes; // 0x18
	public MixBlend[] layerBlendModes; // 0x20
	private OnClipAppliedDelegate _OnClipApplied; // 0x28
	private readonly Dictionary`2 animationTable; // 0x30
	private readonly Dictionary`2 clipNameHashCodeTable; // 0x38
	private readonly List`1 previousAnimations; // 0x40
	protected ClipInfos[] layerClipInfos; // 0x48
	private Animator animator; // 0x50

	public Animator Animator { get; }
	public Int32 MecanimLayerCount { get; }
	public String[] MecanimLayerNames { get; }

	// RVA: 0x62095f8 VA: 0x75988215f8
	protected Void add__OnClipApplied(OnClipAppliedDelegate value) { }
	// RVA: 0x6209694 VA: 0x7598821694
	protected Void remove__OnClipApplied(OnClipAppliedDelegate value) { }
	// RVA: 0x6200e04 VA: 0x7598818e04
	public Void add_OnClipApplied(OnClipAppliedDelegate value) { }
	// RVA: 0x6200e00 VA: 0x7598818e00
	public Void remove_OnClipApplied(OnClipAppliedDelegate value) { }
	// RVA: 0x6209730 VA: 0x7598821730
	public Animator get_Animator() { }
	// RVA: 0x6209738 VA: 0x7598821738
	public Int32 get_MecanimLayerCount() { }
	// RVA: 0x62097bc VA: 0x75988217bc
	public String[] get_MecanimLayerNames() { }
	// RVA: 0x620836c VA: 0x759882036c
	public Void Initialize(Animator animator, SkeletonDataAsset skeletonDataAsset) { }
	// RVA: 0x6209a74 VA: 0x7598821a74
	private Boolean ApplyAnimation(Skeleton skeleton, AnimatorClipInfo info, AnimatorStateInfo stateInfo, Int32 layerIndex, Single layerWeight, MixBlend layerBlendMode, Boolean useClipWeight1) { }
	// RVA: 0x6209ea8 VA: 0x7598821ea8
	private Boolean ApplyInterruptionAnimation(Skeleton skeleton, Boolean interpolateWeightTo1, AnimatorClipInfo info, AnimatorStateInfo stateInfo, Int32 layerIndex, Single layerWeight, MixBlend layerBlendMode, Single interruptingClipTimeAddition, Boolean useClipWeight1) { }
	// RVA: 0x6209dc0 VA: 0x7598821dc0
	private Void OnClipAppliedCallback(Animation clip, AnimatorStateInfo stateInfo, Int32 layerIndex, Single time, Boolean isLooping, Single weight) { }
	// RVA: 0x62086ac VA: 0x75988206ac
	public Void Apply(Skeleton skeleton) { }
	// RVA: 0x62004e8 VA: 0x75988184e8
	public KeyValuePair`2 GetActiveAnimationAndTime(Int32 layer) { }
	// RVA: 0x6209d64 VA: 0x7598821d64
	private static Single AnimationTime(Single normalizedTime, Single clipLength, Boolean loop, Boolean reversed) { }
	// RVA: 0x620a08c VA: 0x759882208c
	private static Single AnimationTime(Single normalizedTime, Single clipLength, Boolean reversed) { }
	// RVA: 0x620a0cc VA: 0x75988220cc
	private Void InitClipInfosForLayers() { }
	// RVA: 0x6209924 VA: 0x7598821924
	private Void ClearClipInfosForLayers() { }
	// RVA: 0x620a638 VA: 0x7598822638
	private MixMode GetMixMode(Int32 layer, MixBlend layerBlendMode) { }
	// RVA: 0x620a220 VA: 0x7598822220
	private Void GetStateUpdatesFromAnimator(Int32 layer) { }
	// RVA: 0x620a4f0 VA: 0x75988224f0
	private Void GetAnimatorClipInfos(Int32 layer, out Boolean isInterruptionActive, out Int32 clipInfoCount, out Int32 nextClipInfoCount, out Int32 interruptingClipInfoCount, out IList`1 clipInfo, out IList`1 nextClipInfo, out IList`1 interruptingClipInfo, out Boolean shallInterpolateWeightTo1) { }
	// RVA: 0x620a5ac VA: 0x75988225ac
	private Void GetAnimatorStateInfos(Int32 layer, out Boolean isInterruptionActive, out AnimatorStateInfo stateInfo, out AnimatorStateInfo nextStateInfo, out AnimatorStateInfo interruptingStateInfo, out Single interruptingClipTimeAddition) { }
	// RVA: 0x6209c70 VA: 0x7598821c70
	private Animation GetAnimation(AnimationClip clip) { }
	// RVA: 0x620813c VA: 0x759882013c
	public Void .ctor() { }
}
```