# PathConstraintMixTimeline

**Namespace:** `Spine`


## Properties

- `Int32 PathConstraintIndex`


## Methods

- `Void set_PathConstraintIndex(Int32)`

- `Int32 get_PathConstraintIndex()`

- `Void set_Frames(Single[])`

- `Void SetFrame(Int32, Single, Single, Single)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class PathConstraintMixTimeline : CurveTimeline
{
	public const Int32 ENTRIES; // 0x0
	private const Int32 PREV_TIME; // 0x0
	private const Int32 PREV_ROTATE; // 0x0
	private const Int32 PREV_TRANSLATE; // 0x0
	private const Int32 ROTATE; // 0x0
	private const Int32 TRANSLATE; // 0x0
	internal Int32 pathConstraintIndex; // 0x18
	internal Single[] frames; // 0x20

	public override Int32 PropertyId { get; }
	public Int32 PathConstraintIndex { get; set; }
	public Single[] Frames { get; set; }

	// RVA: 0x61c93dc VA: 0x75987e13dc
	public Void .ctor(Int32 frameCount) { }
	// RVA: 0x61c944c VA: 0x75987e144c
	public override Int32 get_PropertyId() { }
	// RVA: 0x61c945c VA: 0x75987e145c
	public Void set_PathConstraintIndex(Int32 value) { }
	// RVA: 0x61c94bc VA: 0x75987e14bc
	public Int32 get_PathConstraintIndex() { }
	// RVA: 0x61c94c4 VA: 0x75987e14c4
	public Single[] get_Frames() { }
	// RVA: 0x61c94cc VA: 0x75987e14cc
	public Void set_Frames(Single[] value) { }
	// RVA: 0x61c94d4 VA: 0x75987e14d4
	public Void SetFrame(Int32 frameIndex, Single time, Single rotateMix, Single translateMix) { }
	// RVA: 0x61c9530 VA: 0x75987e1530
	public override Void Apply(Skeleton skeleton, Single lastTime, Single time, ExposedList`1 firedEvents, Single alpha, MixBlend blend, MixDirection direction) { }
}
```