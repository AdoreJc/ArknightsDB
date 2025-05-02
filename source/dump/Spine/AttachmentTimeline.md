# AttachmentTimeline

**Namespace:** `Spine`


## Properties

- `Int32 PropertyId`

- `Int32 FrameCount`

- `Int32 SlotIndex`


## Methods

- `Int32 get_PropertyId()`

- `Int32 get_FrameCount()`

- `Void set_SlotIndex(Int32)`

- `Int32 get_SlotIndex()`

- `Void set_Frames(Single[])`

- `Void set_AttachmentNames(String[])`

- `Void SetFrame(Int32, Single, String)`

- `Void Apply(Skeleton, Single, Single, ExposedList`1, Single, MixBlend, MixDirection)`

- `Void SetAttachment(Skeleton, Slot, String)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class AttachmentTimeline : Timeline, ISlotTimeline
{
	internal Int32 slotIndex; // 0x10
	internal Single[] frames; // 0x18
	internal String[] attachmentNames; // 0x20

	public Int32 PropertyId { get; }
	public Int32 FrameCount { get; }
	public Int32 SlotIndex { get; set; }
	public Single[] Frames { get; set; }
	public String[] AttachmentNames { get; set; }

	// RVA: 0x61c6d48 VA: 0x75987ded48
	public Void .ctor(Int32 frameCount) { }
	// RVA: 0x61c6de8 VA: 0x75987dede8
	public Int32 get_PropertyId() { }
	// RVA: 0x61c6df8 VA: 0x75987dedf8
	public Int32 get_FrameCount() { }
	// RVA: 0x61c6e14 VA: 0x75987dee14
	public Void set_SlotIndex(Int32 value) { }
	// RVA: 0x61c6e74 VA: 0x75987dee74
	public Int32 get_SlotIndex() { }
	// RVA: 0x61c6e7c VA: 0x75987dee7c
	public Single[] get_Frames() { }
	// RVA: 0x61c6e84 VA: 0x75987dee84
	public Void set_Frames(Single[] value) { }
	// RVA: 0x61c6e8c VA: 0x75987dee8c
	public String[] get_AttachmentNames() { }
	// RVA: 0x61c6e94 VA: 0x75987dee94
	public Void set_AttachmentNames(String[] value) { }
	// RVA: 0x61c6e9c VA: 0x75987dee9c
	public Void SetFrame(Int32 frameIndex, Single time, String attachmentName) { }
	// RVA: 0x61c6f2c VA: 0x75987def2c
	public Void Apply(Skeleton skeleton, Single lastTime, Single time, ExposedList`1 firedEvents, Single alpha, MixBlend blend, MixDirection direction) { }
	// RVA: 0x61c7024 VA: 0x75987df024
	private Void SetAttachment(Skeleton skeleton, Slot slot, String attachmentName) { }
}
```