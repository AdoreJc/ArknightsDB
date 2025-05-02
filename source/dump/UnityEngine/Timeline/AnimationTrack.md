# AnimationTrack

**Namespace:** `UnityEngine.Timeline`


## Fields

- `ClipExtrapolation m_InfiniteClipPreExtrapolation`

- `ClipExtrapolation m_InfiniteClipPostExtrapolation`

- `Vector3 m_InfiniteClipOffsetPosition`

- `Vector3 m_InfiniteClipOffsetEulerAngles`

- `Double m_InfiniteClipTimeOffset`

- `Boolean m_InfiniteClipRemoveOffset`

- `Boolean m_InfiniteClipApplyFootIK`

- `LoopMode mInfiniteClipLoop`

- `MatchTargetFields m_MatchTargetFields`

- `Vector3 m_Position`

- `Vector3 m_EulerAngles`

- `AvatarMask m_AvatarMask`

- `Boolean m_ApplyAvatarMask`

- `TrackOffset m_TrackOffset`

- `AnimationClip m_InfiniteClip`

- `Quaternion m_OpenClipOffsetRotation`

- `Quaternion m_Rotation`

- `Boolean m_ApplyOffsets`


## Properties

- `Vector3 position`

- `Quaternion rotation`

- `Vector3 eulerAngles`

- `Boolean applyOffsets`

- `TrackOffset trackOffset`

- `MatchTargetFields matchTargetFields`

- `AnimationClip infiniteClip`

- `AvatarMask avatarMask`

- `Boolean applyAvatarMask`

- `Boolean inClipMode`

- `Vector3 infiniteClipOffsetPosition`

- `Quaternion infiniteClipOffsetRotation`

- `Vector3 infiniteClipOffsetEulerAngles`

- `ClipExtrapolation infiniteClipPreExtrapolation`

- `ClipExtrapolation infiniteClipPostExtrapolation`

- `Vector3 openClipOffsetPosition`

- `Quaternion openClipOffsetRotation`

- `Vector3 openClipOffsetEulerAngles`

- `ClipExtrapolation openClipPreExtrapolation`

- `ClipExtrapolation openClipPostExtrapolation`


## Methods

- `Vector3 get_position()`

- `Void set_position(Vector3)`

- `Quaternion get_rotation()`

- `Void set_rotation(Quaternion)`

- `Vector3 get_eulerAngles()`

- `Void set_eulerAngles(Vector3)`

- `Boolean get_applyOffsets()`

- `Void set_applyOffsets(Boolean)`

- `TrackOffset get_trackOffset()`

- `Void set_trackOffset(TrackOffset)`

- `MatchTargetFields get_matchTargetFields()`

- `Void set_matchTargetFields(MatchTargetFields)`

- `AnimationClip get_infiniteClip()`

- `AvatarMask get_avatarMask()`

- `Void set_avatarMask(AvatarMask)`

- `Boolean get_applyAvatarMask()`

- `Void set_applyAvatarMask(Boolean)`

- `Boolean get_inClipMode()`

- `Vector3 get_infiniteClipOffsetPosition()`

- `Void set_infiniteClipOffsetPosition(Vector3)`

- `Quaternion get_infiniteClipOffsetRotation()`

- `Void set_infiniteClipOffsetRotation(Quaternion)`

- `Vector3 get_infiniteClipOffsetEulerAngles()`

- `Void set_infiniteClipOffsetEulerAngles(Vector3)`

- `ClipExtrapolation get_infiniteClipPreExtrapolation()`

- `Void set_infiniteClipPreExtrapolation(ClipExtrapolation)`

- `ClipExtrapolation get_infiniteClipPostExtrapolation()`

- `Void set_infiniteClipPostExtrapolation(ClipExtrapolation)`

- `Void ResetOffsets()`

- `TimelineClip CreateClip(AnimationClip)`

- `Void CreateInfiniteClip(String)`

- `TimelineClip CreateRecordableClip(String)`

- `Playable CompileTrackPlayable(PlayableGraph, AnimationTrack, GameObject, IntervalTree`1, AppliedOffsetMode)`

- `Int32 GetDefaultBlendCount()`

- `Void AttachDefaultBlend(PlayableGraph, AnimationLayerMixerPlayable, Boolean)`

- `Playable AttachOffsetPlayable(PlayableGraph, Playable, Vector3, Quaternion)`

- `Boolean RequiresMotionXPlayable(AppliedOffsetMode, GameObject)`

- `Boolean HasController(GameObject)`

- `Playable CreateInfiniteTrackPlayable(PlayableGraph, GameObject, IntervalTree`1, AppliedOffsetMode)`

- `Playable ApplyTrackOffset(PlayableGraph, Playable, GameObject, AppliedOffsetMode)`

- `Void AssignAnimationClip(TimelineClip, AnimationClip)`

- `Void GetAnimationClips(List`1)`

- `AppliedOffsetMode GetOffsetMode(GameObject, Boolean)`

- `Boolean IsRootTransformDisabledByMask(GameObject, Transform)`

- `Transform GetGenericRootNode(GameObject)`

- `Vector3 get_openClipOffsetPosition()`

- `Void set_openClipOffsetPosition(Vector3)`

- `Quaternion get_openClipOffsetRotation()`

- `Void set_openClipOffsetRotation(Quaternion)`

- `Vector3 get_openClipOffsetEulerAngles()`

- `Void set_openClipOffsetEulerAngles(Vector3)`

- `ClipExtrapolation get_openClipPreExtrapolation()`

- `Void set_openClipPreExtrapolation(ClipExtrapolation)`

- `ClipExtrapolation get_openClipPostExtrapolation()`

- `Void set_openClipPostExtrapolation(ClipExtrapolation)`


## Dump
```C#
// Dll : Unity.Timeline.dll
// Namespace : UnityEngine.Timeline
public class AnimationTrack : TrackAsset, ILayerable
{
	private const String k_DefaultInfiniteClipName; // 0x0
	private const String k_DefaultRecordableClipName; // 0x0
	private ClipExtrapolation m_InfiniteClipPreExtrapolation; // 0xa0
	private ClipExtrapolation m_InfiniteClipPostExtrapolation; // 0xa4
	private Vector3 m_InfiniteClipOffsetPosition; // 0xa8
	private Vector3 m_InfiniteClipOffsetEulerAngles; // 0xb4
	private Double m_InfiniteClipTimeOffset; // 0xc0
	private Boolean m_InfiniteClipRemoveOffset; // 0xc8
	private Boolean m_InfiniteClipApplyFootIK; // 0xc9
	private LoopMode mInfiniteClipLoop; // 0xcc
	private MatchTargetFields m_MatchTargetFields; // 0xd0
	private Vector3 m_Position; // 0xd4
	private Vector3 m_EulerAngles; // 0xe0
	private AvatarMask m_AvatarMask; // 0xf0
	private Boolean m_ApplyAvatarMask; // 0xf8
	private TrackOffset m_TrackOffset; // 0xfc
	private AnimationClip m_InfiniteClip; // 0x100
	private static readonly Queue`1 s_CachedQueue; // 0x0
	private Quaternion m_OpenClipOffsetRotation; // 0x108
	private Quaternion m_Rotation; // 0x118
	private Boolean m_ApplyOffsets; // 0x128

	public Vector3 position { get; set; }
	public Quaternion rotation { get; set; }
	public Vector3 eulerAngles { get; set; }
	public Boolean applyOffsets { get; set; }
	public TrackOffset trackOffset { get; set; }
	public MatchTargetFields matchTargetFields { get; set; }
	public AnimationClip infiniteClip { get; set; }
	internal Boolean infiniteClipRemoveOffset { get; set; }
	public AvatarMask avatarMask { get; set; }
	public Boolean applyAvatarMask { get; set; }
	public override IEnumerable`1 outputs { get; }
	public Boolean inClipMode { get; }
	public Vector3 infiniteClipOffsetPosition { get; set; }
	public Quaternion infiniteClipOffsetRotation { get; set; }
	public Vector3 infiniteClipOffsetEulerAngles { get; set; }
	internal Boolean infiniteClipApplyFootIK { get; set; }
	internal Double infiniteClipTimeOffset { get; set; }
	public ClipExtrapolation infiniteClipPreExtrapolation { get; set; }
	public ClipExtrapolation infiniteClipPostExtrapolation { get; set; }
	internal LoopMode infiniteClipLoop { get; set; }
	public Vector3 openClipOffsetPosition { get; set; }
	public Quaternion openClipOffsetRotation { get; set; }
	public Vector3 openClipOffsetEulerAngles { get; set; }
	public ClipExtrapolation openClipPreExtrapolation { get; set; }
	public ClipExtrapolation openClipPostExtrapolation { get; set; }

	// RVA: 0x681ceb4 VA: 0x7598e34eb4
	public Vector3 get_position() { }
	// RVA: 0x681cec0 VA: 0x7598e34ec0
	public Void set_position(Vector3 value) { }
	// RVA: 0x681cecc VA: 0x7598e34ecc
	public Quaternion get_rotation() { }
	// RVA: 0x681cef0 VA: 0x7598e34ef0
	public Void set_rotation(Quaternion value) { }
	// RVA: 0x681cf2c VA: 0x7598e34f2c
	public Vector3 get_eulerAngles() { }
	// RVA: 0x681cf38 VA: 0x7598e34f38
	public Void set_eulerAngles(Vector3 value) { }
	// RVA: 0x681cf44 VA: 0x7598e34f44
	public Boolean get_applyOffsets() { }
	// RVA: 0x681cf4c VA: 0x7598e34f4c
	public Void set_applyOffsets(Boolean value) { }
	// RVA: 0x681cf50 VA: 0x7598e34f50
	public TrackOffset get_trackOffset() { }
	// RVA: 0x681cf58 VA: 0x7598e34f58
	public Void set_trackOffset(TrackOffset value) { }
	// RVA: 0x681cf60 VA: 0x7598e34f60
	public MatchTargetFields get_matchTargetFields() { }
	// RVA: 0x681cf68 VA: 0x7598e34f68
	public Void set_matchTargetFields(MatchTargetFields value) { }
	// RVA: 0x681cfd8 VA: 0x7598e34fd8
	public AnimationClip get_infiniteClip() { }
	// RVA: 0x681cfe0 VA: 0x7598e34fe0
	internal Void set_infiniteClip(AnimationClip value) { }
	// RVA: 0x681cff0 VA: 0x7598e34ff0
	internal Boolean get_infiniteClipRemoveOffset() { }
	// RVA: 0x681cff8 VA: 0x7598e34ff8
	internal Void set_infiniteClipRemoveOffset(Boolean value) { }
	// RVA: 0x681d004 VA: 0x7598e35004
	public AvatarMask get_avatarMask() { }
	// RVA: 0x681d00c VA: 0x7598e3500c
	public Void set_avatarMask(AvatarMask value) { }
	// RVA: 0x681d014 VA: 0x7598e35014
	public Boolean get_applyAvatarMask() { }
	// RVA: 0x681d01c VA: 0x7598e3501c
	public Void set_applyAvatarMask(Boolean value) { }
	// RVA: 0x681d028 VA: 0x7598e35028
	internal override Boolean CanCompileClips() { }
	// RVA: 0x681d0e4 VA: 0x7598e350e4
	public override IEnumerable`1 get_outputs() { }
	// RVA: 0x681d19c VA: 0x7598e3519c
	public Boolean get_inClipMode() { }
	// RVA: 0x681d2a4 VA: 0x7598e352a4
	public Vector3 get_infiniteClipOffsetPosition() { }
	// RVA: 0x681d2b0 VA: 0x7598e352b0
	public Void set_infiniteClipOffsetPosition(Vector3 value) { }
	// RVA: 0x681d2bc VA: 0x7598e352bc
	public Quaternion get_infiniteClipOffsetRotation() { }
	// RVA: 0x681d2e0 VA: 0x7598e352e0
	public Void set_infiniteClipOffsetRotation(Quaternion value) { }
	// RVA: 0x681d31c VA: 0x7598e3531c
	public Vector3 get_infiniteClipOffsetEulerAngles() { }
	// RVA: 0x681d328 VA: 0x7598e35328
	public Void set_infiniteClipOffsetEulerAngles(Vector3 value) { }
	// RVA: 0x681d334 VA: 0x7598e35334
	internal Boolean get_infiniteClipApplyFootIK() { }
	// RVA: 0x681d33c VA: 0x7598e3533c
	internal Void set_infiniteClipApplyFootIK(Boolean value) { }
	// RVA: 0x681d348 VA: 0x7598e35348
	internal Double get_infiniteClipTimeOffset() { }
	// RVA: 0x681d350 VA: 0x7598e35350
	internal Void set_infiniteClipTimeOffset(Double value) { }
	// RVA: 0x681d358 VA: 0x7598e35358
	public ClipExtrapolation get_infiniteClipPreExtrapolation() { }
	// RVA: 0x681d360 VA: 0x7598e35360
	public Void set_infiniteClipPreExtrapolation(ClipExtrapolation value) { }
	// RVA: 0x681d368 VA: 0x7598e35368
	public ClipExtrapolation get_infiniteClipPostExtrapolation() { }
	// RVA: 0x681d370 VA: 0x7598e35370
	public Void set_infiniteClipPostExtrapolation(ClipExtrapolation value) { }
	// RVA: 0x681d378 VA: 0x7598e35378
	internal LoopMode get_infiniteClipLoop() { }
	// RVA: 0x681d380 VA: 0x7598e35380
	internal Void set_infiniteClipLoop(LoopMode value) { }
	// RVA: 0x681d388 VA: 0x7598e35388
	private Void ResetOffsets() { }
	// RVA: 0x681d3f8 VA: 0x7598e353f8
	public TimelineClip CreateClip(AnimationClip clip) { }
	// RVA: 0x681d710 VA: 0x7598e35710
	public Void CreateInfiniteClip(String infiniteClipName) { }
	// RVA: 0x681d9ec VA: 0x7598e359ec
	public TimelineClip CreateRecordableClip(String animClipName) { }
	// RVA: 0x681dce4 VA: 0x7598e35ce4
	protected override Void OnCreateClip(TimelineClip clip) { }
	// RVA: 0x681deac VA: 0x7598e35eac
	protected internal override Int32 CalculateItemsHash() { }
	// RVA: 0x681d3f4 VA: 0x7598e353f4
	internal Void UpdateClipOffsets() { }
	// RVA: 0x681e0d4 VA: 0x7598e360d4
	private Playable CompileTrackPlayable(PlayableGraph graph, AnimationTrack track, GameObject go, IntervalTree`1 tree, AppliedOffsetMode mode) { }
	// RVA: 0x681eaf0 VA: 0x7598e36af0
	private Playable UnityEngine.Timeline.ILayerable.CreateLayerMixer(PlayableGraph graph, GameObject go, Int32 inputCount) { }
	// RVA: 0x681eb40 VA: 0x7598e36b40
	internal override Playable CreateMixerPlayableGraph(PlayableGraph graph, GameObject go, IntervalTree`1 tree) { }
	// RVA: 0x681f9e0 VA: 0x7598e379e0
	private Int32 GetDefaultBlendCount() { }
	// RVA: 0x681fee4 VA: 0x7598e37ee4
	private Void AttachDefaultBlend(PlayableGraph graph, AnimationLayerMixerPlayable mixer, Boolean requireOffset) { }
	// RVA: 0x681ff00 VA: 0x7598e37f00
	private Playable AttachOffsetPlayable(PlayableGraph graph, Playable playable, Vector3 pos, Quaternion rot) { }
	// RVA: 0x681fdd4 VA: 0x7598e37dd4
	private Boolean RequiresMotionXPlayable(AppliedOffsetMode mode, GameObject gameObject) { }
	// RVA: 0x681fee8 VA: 0x7598e37ee8
	private static Boolean UsesAbsoluteMotion(AppliedOffsetMode mode) { }
	// RVA: 0x682023c VA: 0x7598e3823c
	private Boolean HasController(GameObject gameObject) { }
	// RVA: 0x6820058 VA: 0x7598e38058
	internal Animator GetBinding(PlayableDirector director) { }
	// RVA: 0x681f9e8 VA: 0x7598e379e8
	private static AnimationLayerMixerPlayable CreateGroupMixer(PlayableGraph graph, GameObject go, Int32 inputCount) { }
	// RVA: 0x681fa58 VA: 0x7598e37a58
	private Playable CreateInfiniteTrackPlayable(PlayableGraph graph, GameObject go, IntervalTree`1 tree, AppliedOffsetMode mode) { }
	// RVA: 0x681e938 VA: 0x7598e36938
	private Playable ApplyTrackOffset(PlayableGraph graph, Playable root, GameObject go, AppliedOffsetMode mode) { }
	// RVA: 0x6820388 VA: 0x7598e38388
	internal override Void GetEvaluationTime(out Double outStart, out Double outDuration) { }
	// RVA: 0x682067c VA: 0x7598e3867c
	internal override Void GetSequenceTime(out Double outStart, out Double outDuration) { }
	// RVA: 0x681d4a0 VA: 0x7598e354a0
	private Void AssignAnimationClip(TimelineClip clip, AnimationClip animClip) { }
	// RVA: 0x68208e8 VA: 0x7598e388e8
	public override Void GatherProperties(PlayableDirector director, IPropertyCollector driver) { }
	// RVA: 0x68208ec VA: 0x7598e388ec
	private Void GetAnimationClips(List`1 animClips) { }
	// RVA: 0x681f970 VA: 0x7598e37970
	private AppliedOffsetMode GetOffsetMode(GameObject go, Boolean animatesRootTransform) { }
	// RVA: 0x681f6f4 VA: 0x7598e376f4
	private Boolean IsRootTransformDisabledByMask(GameObject gameObject, Transform genericRootNode) { }
	// RVA: 0x681f50c VA: 0x7598e3750c
	private Transform GetGenericRootNode(GameObject gameObject) { }
	// RVA: 0x681e554 VA: 0x7598e36554
	internal Boolean AnimatesRootTransform() { }
	// RVA: 0x6820e58 VA: 0x7598e38e58
	private static Transform FindInHierarchyBreadthFirst(Transform t, String name) { }
	// RVA: 0x6821030 VA: 0x7598e39030
	public Vector3 get_openClipOffsetPosition() { }
	// RVA: 0x682103c VA: 0x7598e3903c
	public Void set_openClipOffsetPosition(Vector3 value) { }
	// RVA: 0x6821048 VA: 0x7598e39048
	public Quaternion get_openClipOffsetRotation() { }
	// RVA: 0x682106c VA: 0x7598e3906c
	public Void set_openClipOffsetRotation(Quaternion value) { }
	// RVA: 0x6821070 VA: 0x7598e39070
	public Vector3 get_openClipOffsetEulerAngles() { }
	// RVA: 0x682107c VA: 0x7598e3907c
	public Void set_openClipOffsetEulerAngles(Vector3 value) { }
	// RVA: 0x6821088 VA: 0x7598e39088
	public ClipExtrapolation get_openClipPreExtrapolation() { }
	// RVA: 0x6821090 VA: 0x7598e39090
	public Void set_openClipPreExtrapolation(ClipExtrapolation value) { }
	// RVA: 0x6821098 VA: 0x7598e39098
	public ClipExtrapolation get_openClipPostExtrapolation() { }
	// RVA: 0x68210a0 VA: 0x7598e390a0
	public Void set_openClipPostExtrapolation(ClipExtrapolation value) { }
	// RVA: 0x68210a8 VA: 0x7598e390a8
	internal override Void OnUpgradeFromVersion(Int32 oldVersion) { }
	// RVA: 0x6821240 VA: 0x7598e39240
	public Void .ctor() { }
	// RVA: 0x68214c8 VA: 0x7598e394c8
	private static Void .cctor() { }
}
```