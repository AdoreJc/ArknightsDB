# TrackEntry

**Namespace:** `Spine`


## Fields

- `TrackEntryDelegate Start`

- `TrackEntryDelegate Interrupt`

- `TrackEntryDelegate End`

- `TrackEntryDelegate Dispose`

- `TrackEntryDelegate Complete`

- `TrackEntryEventDelegate Event`


## Properties

- `Int32 TrackIndex`

- `Animation Animation`

- `Boolean Loop`

- `Single Delay`

- `Single TrackTime`

- `Single TrackEnd`

- `Single AnimationStart`

- `Single AnimationEnd`

- `Single AnimationLast`

- `Single AnimationTime`

- `Single TimeScale`

- `Single Alpha`

- `Single EventThreshold`

- `Single AttachmentThreshold`

- `Single DrawOrderThreshold`

- `TrackEntry Next`

- `Boolean IsComplete`

- `Single MixTime`

- `Single MixDuration`

- `MixBlend MixBlend`

- `TrackEntry MixingFrom`

- `TrackEntry MixingTo`

- `Boolean HoldPrevious`


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

- `Void Reset()`

- `Int32 get_TrackIndex()`

- `Animation get_Animation()`

- `Boolean get_Loop()`

- `Void set_Loop(Boolean)`

- `Single get_Delay()`

- `Void set_Delay(Single)`

- `Single get_TrackTime()`

- `Void set_TrackTime(Single)`

- `Single get_TrackEnd()`

- `Void set_TrackEnd(Single)`

- `Single get_AnimationStart()`

- `Void set_AnimationStart(Single)`

- `Single get_AnimationEnd()`

- `Void set_AnimationEnd(Single)`

- `Single get_AnimationLast()`

- `Void set_AnimationLast(Single)`

- `Single get_AnimationTime()`

- `Single get_TimeScale()`

- `Void set_TimeScale(Single)`

- `Single get_Alpha()`

- `Void set_Alpha(Single)`

- `Single get_EventThreshold()`

- `Void set_EventThreshold(Single)`

- `Single get_AttachmentThreshold()`

- `Void set_AttachmentThreshold(Single)`

- `Single get_DrawOrderThreshold()`

- `Void set_DrawOrderThreshold(Single)`

- `TrackEntry get_Next()`

- `Boolean get_IsComplete()`

- `Single get_MixTime()`

- `Void set_MixTime(Single)`

- `Single get_MixDuration()`

- `Void set_MixDuration(Single)`

- `MixBlend get_MixBlend()`

- `Void set_MixBlend(MixBlend)`

- `TrackEntry get_MixingFrom()`

- `TrackEntry get_MixingTo()`

- `Boolean get_HoldPrevious()`

- `Void set_HoldPrevious(Boolean)`

- `Void ResetRotationDirections()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class TrackEntry : IPoolable
{
	internal Animation animation; // 0x10
	internal TrackEntry next; // 0x18
	internal TrackEntry mixingFrom; // 0x20
	internal TrackEntry mixingTo; // 0x28
	private TrackEntryDelegate Start; // 0x30
	private TrackEntryDelegate Interrupt; // 0x38
	private TrackEntryDelegate End; // 0x40
	private TrackEntryDelegate Dispose; // 0x48
	private TrackEntryDelegate Complete; // 0x50
	private TrackEntryEventDelegate Event; // 0x58
	internal Int32 trackIndex; // 0x60
	internal Boolean loop; // 0x64
	internal Boolean holdPrevious; // 0x65
	internal Single eventThreshold; // 0x68
	internal Single attachmentThreshold; // 0x6c
	internal Single drawOrderThreshold; // 0x70
	internal Single animationStart; // 0x74
	internal Single animationEnd; // 0x78
	internal Single animationLast; // 0x7c
	internal Single nextAnimationLast; // 0x80
	internal Single delay; // 0x84
	internal Single trackTime; // 0x88
	internal Single trackLast; // 0x8c
	internal Single nextTrackLast; // 0x90
	internal Single trackEnd; // 0x94
	internal Single timeScale; // 0x98
	internal Single alpha; // 0x9c
	internal Single mixTime; // 0xa0
	internal Single mixDuration; // 0xa4
	internal Single interruptAlpha; // 0xa8
	internal Single totalAlpha; // 0xac
	internal MixBlend mixBlend; // 0xb0
	internal readonly ExposedList`1 timelineMode; // 0xb8
	internal readonly ExposedList`1 timelineHoldMix; // 0xc0
	internal readonly ExposedList`1 timelinesRotation; // 0xc8

	public Int32 TrackIndex { get; }
	public Animation Animation { get; }
	public Boolean Loop { get; set; }
	public Single Delay { get; set; }
	public Single TrackTime { get; set; }
	public Single TrackEnd { get; set; }
	public Single AnimationStart { get; set; }
	public Single AnimationEnd { get; set; }
	public Single AnimationLast { get; set; }
	public Single AnimationTime { get; }
	public Single TimeScale { get; set; }
	public Single Alpha { get; set; }
	public Single EventThreshold { get; set; }
	public Single AttachmentThreshold { get; set; }
	public Single DrawOrderThreshold { get; set; }
	public TrackEntry Next { get; }
	public Boolean IsComplete { get; }
	public Single MixTime { get; set; }
	public Single MixDuration { get; set; }
	public MixBlend MixBlend { get; set; }
	public TrackEntry MixingFrom { get; }
	public TrackEntry MixingTo { get; }
	public Boolean HoldPrevious { get; set; }

	// RVA: 0x61ce578 VA: 0x75987e6578
	public Void add_Start(TrackEntryDelegate value) { }
	// RVA: 0x61ce614 VA: 0x75987e6614
	public Void remove_Start(TrackEntryDelegate value) { }
	// RVA: 0x61ce6b0 VA: 0x75987e66b0
	public Void add_Interrupt(TrackEntryDelegate value) { }
	// RVA: 0x61ce74c VA: 0x75987e674c
	public Void remove_Interrupt(TrackEntryDelegate value) { }
	// RVA: 0x61ce7e8 VA: 0x75987e67e8
	public Void add_End(TrackEntryDelegate value) { }
	// RVA: 0x61ce884 VA: 0x75987e6884
	public Void remove_End(TrackEntryDelegate value) { }
	// RVA: 0x61ce920 VA: 0x75987e6920
	public Void add_Dispose(TrackEntryDelegate value) { }
	// RVA: 0x61ce9bc VA: 0x75987e69bc
	public Void remove_Dispose(TrackEntryDelegate value) { }
	// RVA: 0x61cea58 VA: 0x75987e6a58
	public Void add_Complete(TrackEntryDelegate value) { }
	// RVA: 0x61ceaf4 VA: 0x75987e6af4
	public Void remove_Complete(TrackEntryDelegate value) { }
	// RVA: 0x61ceb90 VA: 0x75987e6b90
	public Void add_Event(TrackEntryEventDelegate value) { }
	// RVA: 0x61cec2c VA: 0x75987e6c2c
	public Void remove_Event(TrackEntryEventDelegate value) { }
	// RVA: 0x61cecc8 VA: 0x75987e6cc8
	internal Void OnStart() { }
	// RVA: 0x61cece8 VA: 0x75987e6ce8
	internal Void OnInterrupt() { }
	// RVA: 0x61ced08 VA: 0x75987e6d08
	internal Void OnEnd() { }
	// RVA: 0x61ced28 VA: 0x75987e6d28
	internal Void OnDispose() { }
	// RVA: 0x61ced48 VA: 0x75987e6d48
	internal Void OnComplete() { }
	// RVA: 0x61ced68 VA: 0x75987e6d68
	internal Void OnEvent(Event e) { }
	// RVA: 0x61ced90 VA: 0x75987e6d90
	public Void Reset() { }
	// RVA: 0x61ceed8 VA: 0x75987e6ed8
	public Int32 get_TrackIndex() { }
	// RVA: 0x61ceee0 VA: 0x75987e6ee0
	public Animation get_Animation() { }
	// RVA: 0x61ceee8 VA: 0x75987e6ee8
	public Boolean get_Loop() { }
	// RVA: 0x61ceef0 VA: 0x75987e6ef0
	public Void set_Loop(Boolean value) { }
	// RVA: 0x61ceefc VA: 0x75987e6efc
	public Single get_Delay() { }
	// RVA: 0x61cef04 VA: 0x75987e6f04
	public Void set_Delay(Single value) { }
	// RVA: 0x61cef0c VA: 0x75987e6f0c
	public Single get_TrackTime() { }
	// RVA: 0x61cef14 VA: 0x75987e6f14
	public Void set_TrackTime(Single value) { }
	// RVA: 0x61cef1c VA: 0x75987e6f1c
	public Single get_TrackEnd() { }
	// RVA: 0x61cef24 VA: 0x75987e6f24
	public Void set_TrackEnd(Single value) { }
	// RVA: 0x61cef2c VA: 0x75987e6f2c
	public Single get_AnimationStart() { }
	// RVA: 0x61cef34 VA: 0x75987e6f34
	public Void set_AnimationStart(Single value) { }
	// RVA: 0x61cef3c VA: 0x75987e6f3c
	public Single get_AnimationEnd() { }
	// RVA: 0x61cef44 VA: 0x75987e6f44
	public Void set_AnimationEnd(Single value) { }
	// RVA: 0x61cef4c VA: 0x75987e6f4c
	public Single get_AnimationLast() { }
	// RVA: 0x61cef54 VA: 0x75987e6f54
	public Void set_AnimationLast(Single value) { }
	// RVA: 0x61cba48 VA: 0x75987e3a48
	public Single get_AnimationTime() { }
	// RVA: 0x61cef5c VA: 0x75987e6f5c
	public Single get_TimeScale() { }
	// RVA: 0x61cef64 VA: 0x75987e6f64
	public Void set_TimeScale(Single value) { }
	// RVA: 0x61cef6c VA: 0x75987e6f6c
	public Single get_Alpha() { }
	// RVA: 0x61cef74 VA: 0x75987e6f74
	public Void set_Alpha(Single value) { }
	// RVA: 0x61cef7c VA: 0x75987e6f7c
	public Single get_EventThreshold() { }
	// RVA: 0x61cef84 VA: 0x75987e6f84
	public Void set_EventThreshold(Single value) { }
	// RVA: 0x61cef8c VA: 0x75987e6f8c
	public Single get_AttachmentThreshold() { }
	// RVA: 0x61cef94 VA: 0x75987e6f94
	public Void set_AttachmentThreshold(Single value) { }
	// RVA: 0x61cef9c VA: 0x75987e6f9c
	public Single get_DrawOrderThreshold() { }
	// RVA: 0x61cefa4 VA: 0x75987e6fa4
	public Void set_DrawOrderThreshold(Single value) { }
	// RVA: 0x61cefac VA: 0x75987e6fac
	public TrackEntry get_Next() { }
	// RVA: 0x61cefb4 VA: 0x75987e6fb4
	public Boolean get_IsComplete() { }
	// RVA: 0x61cefcc VA: 0x75987e6fcc
	public Single get_MixTime() { }
	// RVA: 0x61cefd4 VA: 0x75987e6fd4
	public Void set_MixTime(Single value) { }
	// RVA: 0x61cefdc VA: 0x75987e6fdc
	public Single get_MixDuration() { }
	// RVA: 0x61cefe4 VA: 0x75987e6fe4
	public Void set_MixDuration(Single value) { }
	// RVA: 0x61cefec VA: 0x75987e6fec
	public MixBlend get_MixBlend() { }
	// RVA: 0x61ceff4 VA: 0x75987e6ff4
	public Void set_MixBlend(MixBlend value) { }
	// RVA: 0x61ceffc VA: 0x75987e6ffc
	public TrackEntry get_MixingFrom() { }
	// RVA: 0x61cf004 VA: 0x75987e7004
	public TrackEntry get_MixingTo() { }
	// RVA: 0x61cf00c VA: 0x75987e700c
	public Boolean get_HoldPrevious() { }
	// RVA: 0x61cf014 VA: 0x75987e7014
	public Void set_HoldPrevious(Boolean value) { }
	// RVA: 0x61cf020 VA: 0x75987e7020
	public Void ResetRotationDirections() { }
	// RVA: 0x61cf074 VA: 0x75987e7074
	public override String ToString() { }
	// RVA: 0x61cf0c8 VA: 0x75987e70c8
	public Void .ctor() { }
}
```