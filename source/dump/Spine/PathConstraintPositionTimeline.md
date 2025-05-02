# PathConstraintPositionTimeline

**Namespace:** `Spine`


## Properties

- `Int32 PathConstraintIndex`


## Methods

- `Void set_PathConstraintIndex(Int32)`

- `Int32 get_PathConstraintIndex()`

- `Void set_Frames(Single[])`

- `Void SetFrame(Int32, Single, Single)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class PathConstraintPositionTimeline : CurveTimeline
{
	public const Int32 ENTRIES; // 0x0
	protected const Int32 PREV_TIME; // 0x0
	protected const Int32 PREV_VALUE; // 0x0
	protected const Int32 VALUE; // 0x0
	internal Int32 pathConstraintIndex; // 0x18
	internal Single[] frames; // 0x20

	public override Int32 PropertyId { get; }
	public Int32 PathConstraintIndex { get; set; }
	public Single[] Frames { get; set; }

	// RVA: 0x61c8ed4 VA: 0x75987e0ed4
	public Void .ctor(Int32 frameCount) { }
	// RVA: 0x61c8f44 VA: 0x75987e0f44
	public override Int32 get_PropertyId() { }
	// RVA: 0x61c8f54 VA: 0x75987e0f54
	public Void set_PathConstraintIndex(Int32 value) { }
	// RVA: 0x61c8fb4 VA: 0x75987e0fb4
	public Int32 get_PathConstraintIndex() { }
	// RVA: 0x61c8fbc VA: 0x75987e0fbc
	public Single[] get_Frames() { }
	// RVA: 0x61c8fc4 VA: 0x75987e0fc4
	public Void set_Frames(Single[] value) { }
	// RVA: 0x61c8fcc VA: 0x75987e0fcc
	public Void SetFrame(Int32 frameIndex, Single time, Single position) { }
	// RVA: 0x61c9018 VA: 0x75987e1018
	public override Void Apply(Skeleton skeleton, Single lastTime, Single time, ExposedList`1 firedEvents, Single alpha, MixBlend blend, MixDirection direction) { }
}
```