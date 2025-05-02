# AnimationState

**Namespace:** `Spine`


## Fields

- `AnimationStateData data`

- `TrackEntryDelegate Start`

- `TrackEntryDelegate Interrupt`

- `TrackEntryDelegate End`

- `TrackEntryDelegate Dispose`

- `TrackEntryDelegate Complete`

- `TrackEntryEventDelegate Event`

- `Boolean animationsChanged`

- `Single timeScale`

- `Int32 unkeyedState`


## Properties

- `Single TimeScale`

- `AnimationStateData Data`


## Methods

- `Void add_Start(TrackEntryDelegate)`

- `Void remove_Start(TrackEntryDelegate)`

- `Void add_Interrupt(TrackEntryDelegate)`

- `Void remove_Interrupt(TrackEntryDelegate)`

- `Void add_End(TrackEntryDelegate)`

- `Void remove_End(TrackEntryDelegate)`

- `Void add_Dispose(TrackEntryDelegate)`

- `Void remove_Dispose(TrackEntryDelegate)`

- `Void add_Complete(TrackEntryDelegate)`

- `Void remove_Complete(TrackEntryDelegate)`

- `Void add_Event(TrackEntryEventDelegate)`

- `Void remove_Event(TrackEntryEventDelegate)`

- `Void AssignEventSubscribersFrom(AnimationState)`

- `Void AddEventSubscribersFrom(AnimationState)`

- `Void Update(Single)`

- `Boolean UpdateMixingFrom(TrackEntry, Single)`

- `Boolean Apply(Skeleton)`

- `Boolean ApplyEventTimelinesOnly(Skeleton)`

- `Single ApplyMixingFrom(TrackEntry, Skeleton, MixBlend)`

- `Single ApplyMixingFromEventTimelinesOnly(TrackEntry, Skeleton)`

- `Void ApplyAttachmentTimeline(AttachmentTimeline, Skeleton, Single, MixBlend, Boolean)`

- `Void SetAttachment(Skeleton, Slot, String, Boolean)`

- `Void QueueEvents(TrackEntry, Single)`

- `Void ClearTracks()`

- `Void ClearTrack(Int32)`

- `Void SetCurrent(Int32, TrackEntry, Boolean)`

- `TrackEntry SetAnimation(Int32, String, Boolean)`

- `TrackEntry SetAnimation(Int32, Animation, Boolean)`

- `TrackEntry AddAnimation(Int32, String, Boolean, Single)`

- `TrackEntry AddAnimation(Int32, Animation, Boolean, Single)`

- `TrackEntry SetEmptyAnimation(Int32, Single)`

- `TrackEntry AddEmptyAnimation(Int32, Single, Single)`

- `Void SetEmptyAnimations(Single)`

- `TrackEntry ExpandToIndex(Int32)`

- `TrackEntry NewTrackEntry(Int32, Animation, Boolean, TrackEntry)`

- `Void DisposeNext(TrackEntry)`

- `Void AnimationsChanged()`

- `Void ComputeHold(TrackEntry)`

- `TrackEntry GetCurrent(Int32)`

- `Void ClearListenerNotifications()`

- `Single get_TimeScale()`

- `Void set_TimeScale(Single)`

- `AnimationStateData get_Data()`

- `Void set_Data(AnimationStateData)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class AnimationState
{
	private static readonly Animation EmptyAnimation; // 0x0
	internal const Int32 Subsequent; // 0x0
	internal const Int32 First; // 0x0
	internal const Int32 HoldSubsequent; // 0x0
	internal const Int32 HoldFirst; // 0x0
	internal const Int32 HoldMix; // 0x0
	internal const Int32 Setup; // 0x0
	internal const Int32 Current; // 0x0
	protected AnimationStateData data; // 0x10
	private readonly ExposedList`1 tracks; // 0x18
	private readonly ExposedList`1 events; // 0x20
	private TrackEntryDelegate Start; // 0x28
	private TrackEntryDelegate Interrupt; // 0x30
	private TrackEntryDelegate End; // 0x38
	private TrackEntryDelegate Dispose; // 0x40
	private TrackEntryDelegate Complete; // 0x48
	private TrackEntryEventDelegate Event; // 0x50
	private readonly EventQueue queue; // 0x58
	private readonly HashSet`1 propertyIDs; // 0x60
	private Boolean animationsChanged; // 0x68
	private Single timeScale; // 0x6c
	private Int32 unkeyedState; // 0x70
	private readonly Pool`1 trackEntryPool; // 0x78

	public Single TimeScale { get; set; }
	public AnimationStateData Data { get; set; }
	public ExposedList`1 Tracks { get; }

	// RVA: 0x61c97a4 VA: 0x75987e17a4
	internal Void OnStart(TrackEntry entry) { }
	// RVA: 0x61c97c0 VA: 0x75987e17c0
	internal Void OnInterrupt(TrackEntry entry) { }
	// RVA: 0x61c97dc VA: 0x75987e17dc
	internal Void OnEnd(TrackEntry entry) { }
	// RVA: 0x61c97f8 VA: 0x75987e17f8
	internal Void OnDispose(TrackEntry entry) { }
	// RVA: 0x61c9814 VA: 0x75987e1814
	internal Void OnComplete(TrackEntry entry) { }
	// RVA: 0x61c9830 VA: 0x75987e1830
	internal Void OnEvent(TrackEntry entry, Event e) { }
	// RVA: 0x61c984c VA: 0x75987e184c
	public Void add_Start(TrackEntryDelegate value) { }
	// RVA: 0x61c98e8 VA: 0x75987e18e8
	public Void remove_Start(TrackEntryDelegate value) { }
	// RVA: 0x61c9984 VA: 0x75987e1984
	public Void add_Interrupt(TrackEntryDelegate value) { }
	// RVA: 0x61c9a20 VA: 0x75987e1a20
	public Void remove_Interrupt(TrackEntryDelegate value) { }
	// RVA: 0x61c9abc VA: 0x75987e1abc
	public Void add_End(TrackEntryDelegate value) { }
	// RVA: 0x61c9b58 VA: 0x75987e1b58
	public Void remove_End(TrackEntryDelegate value) { }
	// RVA: 0x61c9bf4 VA: 0x75987e1bf4
	public Void add_Dispose(TrackEntryDelegate value) { }
	// RVA: 0x61c9c90 VA: 0x75987e1c90
	public Void remove_Dispose(TrackEntryDelegate value) { }
	// RVA: 0x61c9d2c VA: 0x75987e1d2c
	public Void add_Complete(TrackEntryDelegate value) { }
	// RVA: 0x61c9dc8 VA: 0x75987e1dc8
	public Void remove_Complete(TrackEntryDelegate value) { }
	// RVA: 0x61c9e64 VA: 0x75987e1e64
	public Void add_Event(TrackEntryEventDelegate value) { }
	// RVA: 0x61c9f00 VA: 0x75987e1f00
	public Void remove_Event(TrackEntryEventDelegate value) { }
	// RVA: 0x61c9f9c VA: 0x75987e1f9c
	public Void AssignEventSubscribersFrom(AnimationState src) { }
	// RVA: 0x61ca018 VA: 0x75987e2018
	public Void AddEventSubscribersFrom(AnimationState src) { }
	// RVA: 0x61ca07c VA: 0x75987e207c
	public Void .ctor(AnimationStateData data) { }
	// RVA: 0x61ca3e8 VA: 0x75987e23e8
	public Void Update(Single delta) { }
	// RVA: 0x61ca910 VA: 0x75987e2910
	private Boolean UpdateMixingFrom(TrackEntry to, Single delta) { }
	// RVA: 0x61caccc VA: 0x75987e2ccc
	public Boolean Apply(Skeleton skeleton) { }
	// RVA: 0x61cc2d4 VA: 0x75987e42d4
	public Boolean ApplyEventTimelinesOnly(Skeleton skeleton) { }
	// RVA: 0x61cb3f8 VA: 0x75987e33f8
	private Single ApplyMixingFrom(TrackEntry to, Skeleton skeleton, MixBlend blend) { }
	// RVA: 0x61cc5b8 VA: 0x75987e45b8
	private Single ApplyMixingFromEventTimelinesOnly(TrackEntry to, Skeleton skeleton) { }
	// RVA: 0x61cbaf8 VA: 0x75987e3af8
	private Void ApplyAttachmentTimeline(AttachmentTimeline timeline, Skeleton skeleton, Single time, MixBlend blend, Boolean attachments) { }
	// RVA: 0x61cc804 VA: 0x75987e4804
	private Void SetAttachment(Skeleton skeleton, Slot slot, String attachmentName, Boolean attachments) { }
	// RVA: 0x61cbc0c VA: 0x75987e3c0c
	private static Void ApplyRotateTimeline(RotateTimeline timeline, Skeleton skeleton, Single time, Single alpha, MixBlend blend, Single[] timelinesRotation, Int32 i, Boolean firstFrame) { }
	// RVA: 0x61cc164 VA: 0x75987e4164
	private Void QueueEvents(TrackEntry entry, Single animationTime) { }
	// RVA: 0x61ccacc VA: 0x75987e4acc
	public Void ClearTracks() { }
	// RVA: 0x61ccb7c VA: 0x75987e4b7c
	public Void ClearTrack(Int32 trackIndex) { }
	// RVA: 0x61ca5f0 VA: 0x75987e25f0
	private Void SetCurrent(Int32 index, TrackEntry current, Boolean interrupt) { }
	// RVA: 0x61ccf7c VA: 0x75987e4f7c
	public TrackEntry SetAnimation(Int32 trackIndex, String animationName, Boolean loop) { }
	// RVA: 0x61cd048 VA: 0x75987e5048
	public TrackEntry SetAnimation(Int32 trackIndex, Animation animation, Boolean loop) { }
	// RVA: 0x61cd2dc VA: 0x75987e52dc
	public TrackEntry AddAnimation(Int32 trackIndex, String animationName, Boolean loop, Single delay) { }
	// RVA: 0x61cd3b8 VA: 0x75987e53b8
	public TrackEntry AddAnimation(Int32 trackIndex, Animation animation, Boolean loop, Single delay) { }
	// RVA: 0x61cd710 VA: 0x75987e5710
	public TrackEntry SetEmptyAnimation(Int32 trackIndex, Single mixDuration) { }
	// RVA: 0x61cd7a4 VA: 0x75987e57a4
	public TrackEntry AddEmptyAnimation(Int32 trackIndex, Single mixDuration, Single delay) { }
	// RVA: 0x61cd84c VA: 0x75987e584c
	public Void SetEmptyAnimations(Single mixDuration) { }
	// RVA: 0x61ccc90 VA: 0x75987e4c90
	private TrackEntry ExpandToIndex(Int32 index) { }
	// RVA: 0x61cd1e0 VA: 0x75987e51e0
	private TrackEntry NewTrackEntry(Int32 trackIndex, Animation animation, Boolean loop, TrackEntry last) { }
	// RVA: 0x61ca8c0 VA: 0x75987e28c0
	private Void DisposeNext(TrackEntry entry) { }
	// RVA: 0x61cb318 VA: 0x75987e3318
	private Void AnimationsChanged() { }
	// RVA: 0x61cda1c VA: 0x75987e5a1c
	private Void ComputeHold(TrackEntry entry) { }
	// RVA: 0x61cdeb8 VA: 0x75987e5eb8
	public TrackEntry GetCurrent(Int32 trackIndex) { }
	// RVA: 0x61cdf04 VA: 0x75987e5f04
	public Void ClearListenerNotifications() { }
	// RVA: 0x61cdf8c VA: 0x75987e5f8c
	public Single get_TimeScale() { }
	// RVA: 0x61cdf94 VA: 0x75987e5f94
	public Void set_TimeScale(Single value) { }
	// RVA: 0x61cdf9c VA: 0x75987e5f9c
	public AnimationStateData get_Data() { }
	// RVA: 0x61cdfa4 VA: 0x75987e5fa4
	public Void set_Data(AnimationStateData value) { }
	// RVA: 0x61ce024 VA: 0x75987e6024
	public ExposedList`1 get_Tracks() { }
	// RVA: 0x61ce02c VA: 0x75987e602c
	public override String ToString() { }
	// RVA: 0x61ce188 VA: 0x75987e6188
	private static Void .cctor() { }
	// RVA: 0x61ce268 VA: 0x75987e6268
	private Void <.ctor>b__45_0() { }
}
```