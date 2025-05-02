# DrawOrderTimeline

**Namespace:** `Spine`


## Properties

- `Int32 PropertyId`

- `Int32 FrameCount`


## Methods

- `Int32 get_PropertyId()`

- `Int32 get_FrameCount()`

- `Void set_Frames(Single[])`

- `Void set_DrawOrders(Int32[][])`

- `Void SetFrame(Int32, Single, Int32[])`

- `Void Apply(Skeleton, Single, Single, ExposedList`1, Single, MixBlend, MixDirection)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class DrawOrderTimeline : Timeline
{
	internal Single[] frames; // 0x10
	private Int32[][] drawOrders; // 0x18

	public Int32 PropertyId { get; }
	public Int32 FrameCount { get; }
	public Single[] Frames { get; set; }
	public Int32[][] DrawOrders { get; set; }

	// RVA: 0x61c80c0 VA: 0x75987e00c0
	public Void .ctor(Int32 frameCount) { }
	// RVA: 0x61c8160 VA: 0x75987e0160
	public Int32 get_PropertyId() { }
	// RVA: 0x61c8168 VA: 0x75987e0168
	public Int32 get_FrameCount() { }
	// RVA: 0x61c8184 VA: 0x75987e0184
	public Single[] get_Frames() { }
	// RVA: 0x61c818c VA: 0x75987e018c
	public Void set_Frames(Single[] value) { }
	// RVA: 0x61c8194 VA: 0x75987e0194
	public Int32[][] get_DrawOrders() { }
	// RVA: 0x61c819c VA: 0x75987e019c
	public Void set_DrawOrders(Int32[][] value) { }
	// RVA: 0x61c81a4 VA: 0x75987e01a4
	public Void SetFrame(Int32 frameIndex, Single time, Int32[] drawOrder) { }
	// RVA: 0x61c8234 VA: 0x75987e0234
	public Void Apply(Skeleton skeleton, Single lastTime, Single time, ExposedList`1 firedEvents, Single alpha, MixBlend blend, MixDirection direction) { }
}
```