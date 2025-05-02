# SkeletonBinary

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

- `SkeletonData ReadSkeletonData(Stream)`

- `Skin ReadSkin(SkeletonInput, SkeletonData, Boolean, Boolean)`

- `Attachment ReadAttachment(SkeletonInput, SkeletonData, Skin, Int32, String, Boolean)`

- `Vertices ReadVertices(SkeletonInput, Int32)`

- `Animation ReadAnimation(Animation, Byte[], SkeletonData, ExposedList`1)`

- `Animation ReadAnimation(String, SkeletonInput, SkeletonData)`

- `Void ReadCurve(SkeletonInput, Int32, CurveTimeline)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class SkeletonBinary
{
	public const Int32 BONE_ROTATE; // 0x0
	public const Int32 BONE_TRANSLATE; // 0x0
	public const Int32 BONE_SCALE; // 0x0
	public const Int32 BONE_SHEAR; // 0x0
	public const Int32 SLOT_ATTACHMENT; // 0x0
	public const Int32 SLOT_COLOR; // 0x0
	public const Int32 SLOT_TWO_COLOR; // 0x0
	public const Int32 PATH_POSITION; // 0x0
	public const Int32 PATH_SPACING; // 0x0
	public const Int32 PATH_MIX; // 0x0
	public const Int32 CURVE_LINEAR; // 0x0
	public const Int32 CURVE_STEPPED; // 0x0
	public const Int32 CURVE_BEZIER; // 0x0
	private Single <Scale>k__BackingField; // 0x10
	private AttachmentLoader attachmentLoader; // 0x18
	private List`1 linkedMeshes; // 0x20
	public static readonly TransformMode[] TransformModeValues; // 0x0
	public static Boolean useLazyLoad; // 0x8

	public Single Scale { get; set; }

	// RVA: 0x61dc350 VA: 0x75987f4350
	public Single get_Scale() { }
	// RVA: 0x61dc358 VA: 0x75987f4358
	public Void set_Scale(Single value) { }
	// RVA: 0x61dc360 VA: 0x75987f4360
	public Void .ctor(Atlas[] atlasArray) { }
	// RVA: 0x61dc3d4 VA: 0x75987f43d4
	public Void .ctor(AttachmentLoader attachmentLoader) { }
	// RVA: 0x61dc4d4 VA: 0x75987f44d4
	public SkeletonData ReadSkeletonData(String path) { }
	// RVA: 0x61de144 VA: 0x75987f6144
	public static String GetVersionString(Stream file) { }
	// RVA: 0x61dc6cc VA: 0x75987f46cc
	public SkeletonData ReadSkeletonData(Stream file) { }
	// RVA: 0x61de1fc VA: 0x75987f61fc
	private Skin ReadSkin(SkeletonInput input, SkeletonData skeletonData, Boolean defaultSkin, Boolean nonessential) { }
	// RVA: 0x61dfe30 VA: 0x75987f7e30
	private Attachment ReadAttachment(SkeletonInput input, SkeletonData skeletonData, Skin skin, Int32 slotIndex, String attachmentName, Boolean nonessential) { }
	// RVA: 0x61e0988 VA: 0x75987f8988
	private Vertices ReadVertices(SkeletonInput input, Int32 vertexCount) { }
	// RVA: 0x61e0c24 VA: 0x75987f8c24
	private Single[] ReadFloatArray(SkeletonInput input, Int32 n, Single scale) { }
	// RVA: 0x61e0d34 VA: 0x75987f8d34
	private Int32[] ReadShortArray(SkeletonInput input) { }
	// RVA: 0x61e0e18 VA: 0x75987f8e18
	public Animation ReadAnimation(Animation anim, Byte[] buffer, SkeletonData skeletonData, ExposedList`1 strings) { }
	// RVA: 0x61de638 VA: 0x75987f6638
	private Animation ReadAnimation(String name, SkeletonInput input, SkeletonData skeletonData) { }
	// RVA: 0x61e0ef0 VA: 0x75987f8ef0
	private Void ReadCurve(SkeletonInput input, Int32 frameIndex, CurveTimeline timeline) { }
	// RVA: 0x61e0fdc VA: 0x75987f8fdc
	private static Void .cctor() { }
}
```