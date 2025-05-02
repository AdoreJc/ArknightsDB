# DeformTimeline

**Namespace:** `Spine`


## Properties

- `Int32 SlotIndex`

- `VertexAttachment Attachment`


## Methods

- `Void set_SlotIndex(Int32)`

- `Int32 get_SlotIndex()`

- `VertexAttachment get_Attachment()`

- `Void set_Attachment(VertexAttachment)`

- `Void set_Frames(Single[])`

- `Void set_Vertices(Single[][])`

- `Void SetFrame(Int32, Single, Single[])`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class DeformTimeline : CurveTimeline, ISlotTimeline
{
	internal Int32 slotIndex; // 0x18
	internal VertexAttachment attachment; // 0x20
	internal Single[] frames; // 0x28
	internal Single[][] frameVertices; // 0x30

	public override Int32 PropertyId { get; }
	public Int32 SlotIndex { get; set; }
	public VertexAttachment Attachment { get; set; }
	public Single[] Frames { get; set; }
	public Single[][] Vertices { get; set; }

	// RVA: 0x61c7070 VA: 0x75987df070
	public Void .ctor(Int32 frameCount) { }
	// RVA: 0x61c7110 VA: 0x75987df110
	public override Int32 get_PropertyId() { }
	// RVA: 0x61c713c VA: 0x75987df13c
	public Void set_SlotIndex(Int32 value) { }
	// RVA: 0x61c719c VA: 0x75987df19c
	public Int32 get_SlotIndex() { }
	// RVA: 0x61c71a4 VA: 0x75987df1a4
	public VertexAttachment get_Attachment() { }
	// RVA: 0x61c71ac VA: 0x75987df1ac
	public Void set_Attachment(VertexAttachment value) { }
	// RVA: 0x61c71b4 VA: 0x75987df1b4
	public Single[] get_Frames() { }
	// RVA: 0x61c71bc VA: 0x75987df1bc
	public Void set_Frames(Single[] value) { }
	// RVA: 0x61c71c4 VA: 0x75987df1c4
	public Single[][] get_Vertices() { }
	// RVA: 0x61c71cc VA: 0x75987df1cc
	public Void set_Vertices(Single[][] value) { }
	// RVA: 0x61c71d4 VA: 0x75987df1d4
	public Void SetFrame(Int32 frameIndex, Single time, Single[] vertices) { }
	// RVA: 0x61c7264 VA: 0x75987df264
	public override Void Apply(Skeleton skeleton, Single lastTime, Single time, ExposedList`1 firedEvents, Single alpha, MixBlend blend, MixDirection direction) { }
}
```