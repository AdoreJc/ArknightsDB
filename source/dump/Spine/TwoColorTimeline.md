# TwoColorTimeline

**Namespace:** `Spine`


## Properties

- `Int32 SlotIndex`


## Methods

- `Void set_SlotIndex(Int32)`

- `Int32 get_SlotIndex()`

- `Void SetFrame(Int32, Single, Single, Single, Single, Single, Single, Single, Single)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class TwoColorTimeline : CurveTimeline, ISlotTimeline
{
	public const Int32 ENTRIES; // 0x0
	protected const Int32 PREV_TIME; // 0x0
	protected const Int32 PREV_R; // 0x0
	protected const Int32 PREV_G; // 0x0
	protected const Int32 PREV_B; // 0x0
	protected const Int32 PREV_A; // 0x0
	protected const Int32 PREV_R2; // 0x0
	protected const Int32 PREV_G2; // 0x0
	protected const Int32 PREV_B2; // 0x0
	protected const Int32 R; // 0x0
	protected const Int32 G; // 0x0
	protected const Int32 B; // 0x0
	protected const Int32 A; // 0x0
	protected const Int32 R2; // 0x0
	protected const Int32 G2; // 0x0
	protected const Int32 B2; // 0x0
	internal Int32 slotIndex; // 0x18
	internal Single[] frames; // 0x20

	public override Int32 PropertyId { get; }
	public Int32 SlotIndex { get; set; }
	public Single[] Frames { get; }

	// RVA: 0x61c6648 VA: 0x75987de648
	public Void .ctor(Int32 frameCount) { }
	// RVA: 0x61c66b8 VA: 0x75987de6b8
	public override Int32 get_PropertyId() { }
	// RVA: 0x61c66c8 VA: 0x75987de6c8
	public Void set_SlotIndex(Int32 value) { }
	// RVA: 0x61c6728 VA: 0x75987de728
	public Int32 get_SlotIndex() { }
	// RVA: 0x61c6730 VA: 0x75987de730
	public Single[] get_Frames() { }
	// RVA: 0x61c6738 VA: 0x75987de738
	public Void SetFrame(Int32 frameIndex, Single time, Single r, Single g, Single b, Single a, Single r2, Single g2, Single b2) { }
	// RVA: 0x61c6800 VA: 0x75987de800
	public override Void Apply(Skeleton skeleton, Single lastTime, Single time, ExposedList`1 firedEvents, Single alpha, MixBlend blend, MixDirection direction) { }
}
```