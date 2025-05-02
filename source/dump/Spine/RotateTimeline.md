# RotateTimeline

**Namespace:** `Spine`


## Properties

- `Int32 BoneIndex`


## Methods

- `Void set_BoneIndex(Int32)`

- `Int32 get_BoneIndex()`

- `Void set_Frames(Single[])`

- `Void SetFrame(Int32, Single, Single)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class RotateTimeline : CurveTimeline, IBoneTimeline
{
	public const Int32 ENTRIES; // 0x0
	internal const Int32 PREV_TIME; // 0x0
	internal const Int32 PREV_ROTATION; // 0x0
	internal const Int32 ROTATION; // 0x0
	internal Int32 boneIndex; // 0x18
	internal Single[] frames; // 0x20

	public override Int32 PropertyId { get; }
	public Int32 BoneIndex { get; set; }
	public Single[] Frames { get; set; }

	// RVA: 0x61c4ff8 VA: 0x75987dcff8
	public Void .ctor(Int32 frameCount) { }
	// RVA: 0x61c5068 VA: 0x75987dd068
	public override Int32 get_PropertyId() { }
	// RVA: 0x61c5070 VA: 0x75987dd070
	public Void set_BoneIndex(Int32 value) { }
	// RVA: 0x61c50d0 VA: 0x75987dd0d0
	public Int32 get_BoneIndex() { }
	// RVA: 0x61c50d8 VA: 0x75987dd0d8
	public Single[] get_Frames() { }
	// RVA: 0x61c50e0 VA: 0x75987dd0e0
	public Void set_Frames(Single[] value) { }
	// RVA: 0x61c50e8 VA: 0x75987dd0e8
	public Void SetFrame(Int32 frameIndex, Single time, Single degrees) { }
	// RVA: 0x61c5134 VA: 0x75987dd134
	public override Void Apply(Skeleton skeleton, Single lastTime, Single time, ExposedList`1 firedEvents, Single alpha, MixBlend blend, MixDirection direction) { }
}
```