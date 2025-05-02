# ColorTimeline

**Namespace:** `Spine`


## Properties

- `Int32 SlotIndex`


## Methods

- `Void set_SlotIndex(Int32)`

- `Int32 get_SlotIndex()`

- `Void set_Frames(Single[])`

- `Void SetFrame(Int32, Single, Single, Single, Single, Single)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class ColorTimeline : CurveTimeline, ISlotTimeline
{
	public const Int32 ENTRIES; // 0x0
	protected const Int32 PREV_TIME; // 0x0
	protected const Int32 PREV_R; // 0x0
	protected const Int32 PREV_G; // 0x0
	protected const Int32 PREV_B; // 0x0
	protected const Int32 PREV_A; // 0x0
	protected const Int32 R; // 0x0
	protected const Int32 G; // 0x0
	protected const Int32 B; // 0x0
	protected const Int32 A; // 0x0
	internal Int32 slotIndex; // 0x18
	internal Single[] frames; // 0x20

	public override Int32 PropertyId { get; }
	public Int32 SlotIndex { get; set; }
	public Single[] Frames { get; set; }

	// RVA: 0x61c6160 VA: 0x75987de160
	public Void .ctor(Int32 frameCount) { }
	// RVA: 0x61c61d0 VA: 0x75987de1d0
	public override Int32 get_PropertyId() { }
	// RVA: 0x61c61e0 VA: 0x75987de1e0
	public Void set_SlotIndex(Int32 value) { }
	// RVA: 0x61c6240 VA: 0x75987de240
	public Int32 get_SlotIndex() { }
	// RVA: 0x61c6248 VA: 0x75987de248
	public Single[] get_Frames() { }
	// RVA: 0x61c6250 VA: 0x75987de250
	public Void set_Frames(Single[] value) { }
	// RVA: 0x61c6258 VA: 0x75987de258
	public Void SetFrame(Int32 frameIndex, Single time, Single r, Single g, Single b, Single a) { }
	// RVA: 0x61c62dc VA: 0x75987de2dc
	public override Void Apply(Skeleton skeleton, Single lastTime, Single time, ExposedList`1 firedEvents, Single alpha, MixBlend blend, MixDirection direction) { }
}
```