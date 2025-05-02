# TranslateTimeline

**Namespace:** `Spine`


## Properties

- `Int32 BoneIndex`


## Methods

- `Void set_BoneIndex(Int32)`

- `Int32 get_BoneIndex()`

- `Void set_Frames(Single[])`

- `Void SetFrame(Int32, Single, Single, Single)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class TranslateTimeline : CurveTimeline, IBoneTimeline
{
	public const Int32 ENTRIES; // 0x0
	protected const Int32 PREV_TIME; // 0x0
	protected const Int32 PREV_X; // 0x0
	protected const Int32 PREV_Y; // 0x0
	protected const Int32 X; // 0x0
	protected const Int32 Y; // 0x0
	internal Int32 boneIndex; // 0x18
	internal Single[] frames; // 0x20

	public override Int32 PropertyId { get; }
	public Int32 BoneIndex { get; set; }
	public Single[] Frames { get; set; }

	// RVA: 0x61c5504 VA: 0x75987dd504
	public Void .ctor(Int32 frameCount) { }
	// RVA: 0x61c5574 VA: 0x75987dd574
	public override Int32 get_PropertyId() { }
	// RVA: 0x61c5584 VA: 0x75987dd584
	public Void set_BoneIndex(Int32 value) { }
	// RVA: 0x61c55e4 VA: 0x75987dd5e4
	public Int32 get_BoneIndex() { }
	// RVA: 0x61c55ec VA: 0x75987dd5ec
	public Single[] get_Frames() { }
	// RVA: 0x61c55f4 VA: 0x75987dd5f4
	public Void set_Frames(Single[] value) { }
	// RVA: 0x61c55fc VA: 0x75987dd5fc
	public Void SetFrame(Int32 frameIndex, Single time, Single x, Single y) { }
	// RVA: 0x61c5658 VA: 0x75987dd658
	public override Void Apply(Skeleton skeleton, Single lastTime, Single time, ExposedList`1 firedEvents, Single alpha, MixBlend blend, MixDirection direction) { }
}
```