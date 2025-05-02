# TransformConstraintTimeline

**Namespace:** `Spine`


## Properties

- `Int32 TransformConstraintIndex`


## Methods

- `Void set_TransformConstraintIndex(Int32)`

- `Int32 get_TransformConstraintIndex()`

- `Void set_Frames(Single[])`

- `Void SetFrame(Int32, Single, Single, Single, Single, Single)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class TransformConstraintTimeline : CurveTimeline
{
	public const Int32 ENTRIES; // 0x0
	private const Int32 PREV_TIME; // 0x0
	private const Int32 PREV_ROTATE; // 0x0
	private const Int32 PREV_TRANSLATE; // 0x0
	private const Int32 PREV_SCALE; // 0x0
	private const Int32 PREV_SHEAR; // 0x0
	private const Int32 ROTATE; // 0x0
	private const Int32 TRANSLATE; // 0x0
	private const Int32 SCALE; // 0x0
	private const Int32 SHEAR; // 0x0
	internal Int32 transformConstraintIndex; // 0x18
	internal Single[] frames; // 0x20

	public override Int32 PropertyId { get; }
	public Int32 TransformConstraintIndex { get; set; }
	public Single[] Frames { get; set; }

	// RVA: 0x61c8a04 VA: 0x75987e0a04
	public Void .ctor(Int32 frameCount) { }
	// RVA: 0x61c8a74 VA: 0x75987e0a74
	public override Int32 get_PropertyId() { }
	// RVA: 0x61c8a84 VA: 0x75987e0a84
	public Void set_TransformConstraintIndex(Int32 value) { }
	// RVA: 0x61c8ae4 VA: 0x75987e0ae4
	public Int32 get_TransformConstraintIndex() { }
	// RVA: 0x61c8aec VA: 0x75987e0aec
	public Single[] get_Frames() { }
	// RVA: 0x61c8af4 VA: 0x75987e0af4
	public Void set_Frames(Single[] value) { }
	// RVA: 0x61c8afc VA: 0x75987e0afc
	public Void SetFrame(Int32 frameIndex, Single time, Single rotateMix, Single translateMix, Single scaleMix, Single shearMix) { }
	// RVA: 0x61c8b80 VA: 0x75987e0b80
	public override Void Apply(Skeleton skeleton, Single lastTime, Single time, ExposedList`1 firedEvents, Single alpha, MixBlend blend, MixDirection direction) { }
}
```