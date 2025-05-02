# AnimationPlayableAsset

**Namespace:** `UnityEngine.Timeline`


## Fields

- `AnimationClip m_Clip`

- `Vector3 m_Position`

- `Vector3 m_EulerAngles`

- `Boolean m_UseTrackMatchFields`

- `MatchTargetFields m_MatchTargetFields`

- `Boolean m_RemoveStartOffset`

- `Boolean m_ApplyFootIK`

- `LoopMode m_Loop`

- `AppliedOffsetMode <appliedOffsetMode>k__BackingField`

- `Int32 m_Version`

- `Quaternion m_Rotation`


## Properties

- `Vector3 position`

- `Quaternion rotation`

- `Vector3 eulerAngles`

- `Boolean useTrackMatchFields`

- `MatchTargetFields matchTargetFields`

- `Boolean removeStartOffset`

- `Boolean applyFootIK`

- `LoopMode loop`

- `AnimationClip clip`

- `ClipCaps clipCaps`


## Methods

- `Vector3 get_position()`

- `Void set_position(Vector3)`

- `Quaternion get_rotation()`

- `Void set_rotation(Quaternion)`

- `Vector3 get_eulerAngles()`

- `Void set_eulerAngles(Vector3)`

- `Boolean get_useTrackMatchFields()`

- `Void set_useTrackMatchFields(Boolean)`

- `MatchTargetFields get_matchTargetFields()`

- `Void set_matchTargetFields(MatchTargetFields)`

- `Boolean get_removeStartOffset()`

- `Void set_removeStartOffset(Boolean)`

- `Boolean get_applyFootIK()`

- `Void set_applyFootIK(Boolean)`

- `LoopMode get_loop()`

- `Void set_loop(LoopMode)`

- `AnimationClip get_clip()`

- `Void set_clip(AnimationClip)`

- `ClipCaps get_clipCaps()`

- `Void ResetOffsets()`

- `Void GatherProperties(PlayableDirector, IPropertyCollector)`

- `Void OnUpgradeFromVersion(Int32)`


## Dump
```C#
// Dll : Unity.Timeline.dll
// Namespace : UnityEngine.Timeline
public class AnimationPlayableAsset : PlayableAsset, ITimelineClipAsset, IPropertyPreview, ISerializationCallbackReceiver
{
	private AnimationClip m_Clip; // 0x18
	private Vector3 m_Position; // 0x20
	private Vector3 m_EulerAngles; // 0x2c
	private Boolean m_UseTrackMatchFields; // 0x38
	private MatchTargetFields m_MatchTargetFields; // 0x3c
	private Boolean m_RemoveStartOffset; // 0x40
	private Boolean m_ApplyFootIK; // 0x41
	private LoopMode m_Loop; // 0x44
	private AppliedOffsetMode <appliedOffsetMode>k__BackingField; // 0x48
	private static readonly Int32 k_LatestVersion; // 0x0
	private Int32 m_Version; // 0x4c
	private Quaternion m_Rotation; // 0x50

	public Vector3 position { get; set; }
	public Quaternion rotation { get; set; }
	public Vector3 eulerAngles { get; set; }
	public Boolean useTrackMatchFields { get; set; }
	public MatchTargetFields matchTargetFields { get; set; }
	public Boolean removeStartOffset { get; set; }
	public Boolean applyFootIK { get; set; }
	public LoopMode loop { get; set; }
	internal Boolean hasRootTransforms { get; }
	internal AppliedOffsetMode appliedOffsetMode { get; set; }
	public AnimationClip clip { get; set; }
	public override Double duration { get; }
	public override IEnumerable`1 outputs { get; }
	public ClipCaps clipCaps { get; }

	// RVA: 0x681bcc8 VA: 0x7598e33cc8
	public Vector3 get_position() { }
	// RVA: 0x681bcd4 VA: 0x7598e33cd4
	public Void set_position(Vector3 value) { }
	// RVA: 0x681bce0 VA: 0x7598e33ce0
	public Quaternion get_rotation() { }
	// RVA: 0x681bd04 VA: 0x7598e33d04
	public Void set_rotation(Quaternion value) { }
	// RVA: 0x681bd40 VA: 0x7598e33d40
	public Vector3 get_eulerAngles() { }
	// RVA: 0x681bd4c VA: 0x7598e33d4c
	public Void set_eulerAngles(Vector3 value) { }
	// RVA: 0x681bd58 VA: 0x7598e33d58
	public Boolean get_useTrackMatchFields() { }
	// RVA: 0x681bd60 VA: 0x7598e33d60
	public Void set_useTrackMatchFields(Boolean value) { }
	// RVA: 0x681bd6c VA: 0x7598e33d6c
	public MatchTargetFields get_matchTargetFields() { }
	// RVA: 0x681bd74 VA: 0x7598e33d74
	public Void set_matchTargetFields(MatchTargetFields value) { }
	// RVA: 0x681bd7c VA: 0x7598e33d7c
	public Boolean get_removeStartOffset() { }
	// RVA: 0x681bd84 VA: 0x7598e33d84
	public Void set_removeStartOffset(Boolean value) { }
	// RVA: 0x681bd90 VA: 0x7598e33d90
	public Boolean get_applyFootIK() { }
	// RVA: 0x681bd98 VA: 0x7598e33d98
	public Void set_applyFootIK(Boolean value) { }
	// RVA: 0x681bda4 VA: 0x7598e33da4
	public LoopMode get_loop() { }
	// RVA: 0x681bdac VA: 0x7598e33dac
	public Void set_loop(LoopMode value) { }
	// RVA: 0x681bdb4 VA: 0x7598e33db4
	internal Boolean get_hasRootTransforms() { }
	// RVA: 0x681bf24 VA: 0x7598e33f24
	internal AppliedOffsetMode get_appliedOffsetMode() { }
	// RVA: 0x681bf2c VA: 0x7598e33f2c
	internal Void set_appliedOffsetMode(AppliedOffsetMode value) { }
	// RVA: 0x681bf34 VA: 0x7598e33f34
	public AnimationClip get_clip() { }
	// RVA: 0x681bf3c VA: 0x7598e33f3c
	public Void set_clip(AnimationClip value) { }
	// RVA: 0x681c004 VA: 0x7598e34004
	public override Double get_duration() { }
	// RVA: 0x681c1e8 VA: 0x7598e341e8
	public override IEnumerable`1 get_outputs() { }
	// RVA: 0x681c2a0 VA: 0x7598e342a0
	public override Playable CreatePlayable(PlayableGraph graph, GameObject go) { }
	// RVA: 0x681c378 VA: 0x7598e34378
	internal static Playable CreatePlayable(PlayableGraph graph, AnimationClip clip, Vector3 positionOffset, Vector3 eulerOffset, Boolean removeStartOffset, AppliedOffsetMode mode, Boolean applyFootIK, LoopMode loop) { }
	// RVA: 0x681c760 VA: 0x7598e34760
	private static Boolean ShouldApplyOffset(AppliedOffsetMode mode, AnimationClip clip) { }
	// RVA: 0x681c740 VA: 0x7598e34740
	private static Boolean ShouldApplyScaleRemove(AppliedOffsetMode mode) { }
	// RVA: 0x681c7d4 VA: 0x7598e347d4
	public ClipCaps get_clipCaps() { }
	// RVA: 0x681c8bc VA: 0x7598e348bc
	public Void ResetOffsets() { }
	// RVA: 0x681c928 VA: 0x7598e34928
	public Void GatherProperties(PlayableDirector director, IPropertyCollector driver) { }
	// RVA: 0x681be58 VA: 0x7598e33e58
	internal static Boolean HasRootTransforms(AnimationClip clip) { }
	// RVA: 0x681c9d4 VA: 0x7598e349d4
	private Void UnityEngine.ISerializationCallbackReceiver.OnBeforeSerialize() { }
	// RVA: 0x681ca34 VA: 0x7598e34a34
	private Void UnityEngine.ISerializationCallbackReceiver.OnAfterDeserialize() { }
	// RVA: 0x681cab8 VA: 0x7598e34ab8
	private Void OnUpgradeFromVersion(Int32 oldVersion) { }
	// RVA: 0x681cb14 VA: 0x7598e34b14
	public Void .ctor() { }
	// RVA: 0x681cc18 VA: 0x7598e34c18
	private static Void .cctor() { }
}
```