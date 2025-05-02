# EventTimeline

**Namespace:** `Spine`


## Properties

- `Int32 PropertyId`

- `Int32 FrameCount`


## Methods

- `Int32 get_PropertyId()`

- `Int32 get_FrameCount()`

- `Void set_Frames(Single[])`

- `Void set_Events(Event[])`

- `Void SetFrame(Int32, Event)`

- `Void Apply(Skeleton, Single, Single, ExposedList`1, Single, MixBlend, MixDirection)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class EventTimeline : Timeline
{
	internal Single[] frames; // 0x10
	private Event[] events; // 0x18

	public Int32 PropertyId { get; }
	public Int32 FrameCount { get; }
	public Single[] Frames { get; set; }
	public Event[] Events { get; set; }

	// RVA: 0x61c7d7c VA: 0x75987dfd7c
	public Void .ctor(Int32 frameCount) { }
	// RVA: 0x61c7e1c VA: 0x75987dfe1c
	public Int32 get_PropertyId() { }
	// RVA: 0x61c7e24 VA: 0x75987dfe24
	public Int32 get_FrameCount() { }
	// RVA: 0x61c7e40 VA: 0x75987dfe40
	public Single[] get_Frames() { }
	// RVA: 0x61c7e48 VA: 0x75987dfe48
	public Void set_Frames(Single[] value) { }
	// RVA: 0x61c7e50 VA: 0x75987dfe50
	public Event[] get_Events() { }
	// RVA: 0x61c7e58 VA: 0x75987dfe58
	public Void set_Events(Event[] value) { }
	// RVA: 0x61c7e60 VA: 0x75987dfe60
	public Void SetFrame(Int32 frameIndex, Event e) { }
	// RVA: 0x61c7ef4 VA: 0x75987dfef4
	public Void Apply(Skeleton skeleton, Single lastTime, Single time, ExposedList`1 firedEvents, Single alpha, MixBlend blend, MixDirection direction) { }
}
```