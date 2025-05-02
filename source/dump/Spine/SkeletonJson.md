# SkeletonJson

**Namespace:** `Spine`


## Fields

- `Single <Scale>k__BackingField`

- `AttachmentLoader attachmentLoader`


## Properties

- `Single Scale`


## Methods

- `Single get_Scale()`

- `Void set_Scale(Single)`

- `SkeletonData ReadSkeletonData(String)`

- `SkeletonData ReadSkeletonData(TextReader)`

- `Attachment ReadAttachment(Dictionary`2, Skin, Int32, String, SkeletonData)`

- `Void ReadVertices(Dictionary`2, VertexAttachment, Int32)`

- `Void ReadAnimation(Dictionary`2, String, SkeletonData)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class SkeletonJson
{
	private Single <Scale>k__BackingField; // 0x10
	private AttachmentLoader attachmentLoader; // 0x18
	private List`1 linkedMeshes; // 0x20

	public Single Scale { get; set; }

	// RVA: 0x61e6d04 VA: 0x75987fed04
	public Single get_Scale() { }
	// RVA: 0x61e6d0c VA: 0x75987fed0c
	public Void set_Scale(Single value) { }
	// RVA: 0x61e6d14 VA: 0x75987fed14
	public Void .ctor(Atlas[] atlasArray) { }
	// RVA: 0x61e6d88 VA: 0x75987fed88
	public Void .ctor(AttachmentLoader attachmentLoader) { }
	// RVA: 0x61e6e9c VA: 0x75987fee9c
	public SkeletonData ReadSkeletonData(String path) { }
	// RVA: 0x61e70c4 VA: 0x75987ff0c4
	public SkeletonData ReadSkeletonData(TextReader reader) { }
	// RVA: 0x61ebd90 VA: 0x7598803d90
	private Attachment ReadAttachment(Dictionary`2 map, Skin skin, Int32 slotIndex, String name, SkeletonData skeletonData) { }
	// RVA: 0x61f1988 VA: 0x7598809988
	private Void ReadVertices(Dictionary`2 map, VertexAttachment attachment, Int32 verticesLength) { }
	// RVA: 0x61ecbf8 VA: 0x7598804bf8
	private Void ReadAnimation(Dictionary`2 map, String name, SkeletonData skeletonData) { }
	// RVA: 0x61f2104 VA: 0x759880a104
	private static Void ReadCurve(Dictionary`2 valueMap, CurveTimeline timeline, Int32 frameIndex) { }
	// RVA: 0x61f1d50 VA: 0x7598809d50
	private static Single[] GetFloatArray(Dictionary`2 map, String name, Single scale) { }
	// RVA: 0x61f1f5c VA: 0x7598809f5c
	private static Int32[] GetIntArray(Dictionary`2 map, String name) { }
	// RVA: 0x61eb530 VA: 0x7598803530
	private static Single GetFloat(Dictionary`2 map, String name, Single defaultValue) { }
	// RVA: 0x61eba34 VA: 0x7598803a34
	private static Int32 GetInt(Dictionary`2 map, String name, Int32 defaultValue) { }
	// RVA: 0x61eb6c8 VA: 0x75988036c8
	private static Boolean GetBoolean(Dictionary`2 map, String name, Boolean defaultValue) { }
	// RVA: 0x61eb600 VA: 0x7598803600
	private static String GetString(Dictionary`2 map, String name, String defaultValue) { }
	// RVA: 0x61eb8e8 VA: 0x75988038e8
	private static Single ToColor(String hexString, Int32 colorIndex, Int32 expectedLength) { }
}
```