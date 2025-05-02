# IkConstraintTimeline

**Namespace:** `Spine`


## Properties

- `Int32 IkConstraintIndex`


## Methods

- `Void set_IkConstraintIndex(Int32)`

- `Int32 get_IkConstraintIndex()`

- `Void set_Frames(Single[])`

- `Void SetFrame(Int32, Single, Single, Single, Int32, Boolean, Boolean)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class IkConstraintTimeline : CurveTimeline
{
	public const Int32 ENTRIES; // 0x0
	private const Int32 PREV_TIME; // 0x0
	private const Int32 PREV_MIX; // 0x0
	private const Int32 PREV_SOFTNESS; // 0x0
	private const Int32 PREV_BEND_DIRECTION; // 0x0
	private const Int32 PREV_COMPRESS; // 0x0
	private const Int32 PREV_STRETCH; // 0x0
	private const Int32 MIX; // 0x0
	private const Int32 SOFTNESS; // 0x0
	private const Int32 BEND_DIRECTION; // 0x0
	private const Int32 COMPRESS; // 0x0
	private const Int32 STRETCH; // 0x0
	internal Int32 ikConstraintIndex; // 0x18
	internal Single[] frames; // 0x20

	public override Int32 PropertyId { get; }
	public Int32 IkConstraintIndex { get; set; }
	public Single[] Frames { get; set; }

	// RVA: 0x61c83c8 VA: 0x75987e03c8
	public Void .ctor(Int32 frameCount) { }
	// RVA: 0x61c843c VA: 0x75987e043c
	public override Int32 get_PropertyId() { }
	// RVA: 0x61c844c VA: 0x75987e044c
	public Void set_IkConstraintIndex(Int32 value) { }
	// RVA: 0x61c84ac VA: 0x75987e04ac
	public Int32 get_IkConstraintIndex() { }
	// RVA: 0x61c84b4 VA: 0x75987e04b4
	public Single[] get_Frames() { }
	// RVA: 0x61c84bc VA: 0x75987e04bc
	public Void set_Frames(Single[] value) { }
	// RVA: 0x61c84c4 VA: 0x75987e04c4
	public Void SetFrame(Int32 frameIndex, Single time, Single mix, Single softness, Int32 bendDirection, Boolean compress, Boolean stretch) { }
	// RVA: 0x61c8580 VA: 0x75987e0580
	public override Void Apply(Skeleton skeleton, Single lastTime, Single time, ExposedList`1 firedEvents, Single alpha, MixBlend blend, MixDirection direction) { }
}
```