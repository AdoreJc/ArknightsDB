# RegionAttachment

**Namespace:** `Spine`


## Fields

- `String <Path>k__BackingField`

- `Object <RendererObject>k__BackingField`


## Properties

- `Single X`

- `Single Y`

- `Single Rotation`

- `Single ScaleX`

- `Single ScaleY`

- `Single Width`

- `Single Height`

- `Single R`

- `Single G`

- `Single B`

- `Single A`

- `String Path`

- `Object RendererObject`

- `Single RegionOffsetX`

- `Single RegionOffsetY`

- `Single RegionWidth`

- `Single RegionHeight`

- `Single RegionOriginalWidth`

- `Single RegionOriginalHeight`


## Methods

- `Single get_X()`

- `Void set_X(Single)`

- `Single get_Y()`

- `Void set_Y(Single)`

- `Single get_Rotation()`

- `Void set_Rotation(Single)`

- `Single get_ScaleX()`

- `Void set_ScaleX(Single)`

- `Single get_ScaleY()`

- `Void set_ScaleY(Single)`

- `Single get_Width()`

- `Void set_Width(Single)`

- `Single get_Height()`

- `Void set_Height(Single)`

- `Single get_R()`

- `Void set_R(Single)`

- `Single get_G()`

- `Void set_G(Single)`

- `Single get_B()`

- `Void set_B(Single)`

- `Single get_A()`

- `Void set_A(Single)`

- `String get_Path()`

- `Void set_Path(String)`

- `Object get_RendererObject()`

- `Void set_RendererObject(Object)`

- `Single get_RegionOffsetX()`

- `Void set_RegionOffsetX(Single)`

- `Single get_RegionOffsetY()`

- `Void set_RegionOffsetY(Single)`

- `Single get_RegionWidth()`

- `Void set_RegionWidth(Single)`

- `Single get_RegionHeight()`

- `Void set_RegionHeight(Single)`

- `Single get_RegionOriginalWidth()`

- `Void set_RegionOriginalWidth(Single)`

- `Single get_RegionOriginalHeight()`

- `Void set_RegionOriginalHeight(Single)`

- `Void UpdateOffset()`

- `Void SetUVs(Single, Single, Single, Single, Boolean)`

- `Void ComputeWorldVertices(Bone, Single[], Int32, Int32)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class RegionAttachment : Attachment, IHasRendererObject
{
	public const Int32 BLX; // 0x0
	public const Int32 BLY; // 0x0
	public const Int32 ULX; // 0x0
	public const Int32 ULY; // 0x0
	public const Int32 URX; // 0x0
	public const Int32 URY; // 0x0
	public const Int32 BRX; // 0x0
	public const Int32 BRY; // 0x0
	internal Single x; // 0x18
	internal Single y; // 0x1c
	internal Single rotation; // 0x20
	internal Single scaleX; // 0x24
	internal Single scaleY; // 0x28
	internal Single width; // 0x2c
	internal Single height; // 0x30
	internal Single regionOffsetX; // 0x34
	internal Single regionOffsetY; // 0x38
	internal Single regionWidth; // 0x3c
	internal Single regionHeight; // 0x40
	internal Single regionOriginalWidth; // 0x44
	internal Single regionOriginalHeight; // 0x48
	internal Single[] offset; // 0x50
	internal Single[] uvs; // 0x58
	internal Single r; // 0x60
	internal Single g; // 0x64
	internal Single b; // 0x68
	internal Single a; // 0x6c
	private String <Path>k__BackingField; // 0x70
	private Object <RendererObject>k__BackingField; // 0x78

	public Single X { get; set; }
	public Single Y { get; set; }
	public Single Rotation { get; set; }
	public Single ScaleX { get; set; }
	public Single ScaleY { get; set; }
	public Single Width { get; set; }
	public Single Height { get; set; }
	public Single R { get; set; }
	public Single G { get; set; }
	public Single B { get; set; }
	public Single A { get; set; }
	public String Path { get; set; }
	public Object RendererObject { get; set; }
	public Single RegionOffsetX { get; set; }
	public Single RegionOffsetY { get; set; }
	public Single RegionWidth { get; set; }
	public Single RegionHeight { get; set; }
	public Single RegionOriginalWidth { get; set; }
	public Single RegionOriginalHeight { get; set; }
	public Single[] Offset { get; }
	public Single[] UVs { get; }

	// RVA: 0x61d2684 VA: 0x75987ea684
	public Single get_X() { }
	// RVA: 0x61d268c VA: 0x75987ea68c
	public Void set_X(Single value) { }
	// RVA: 0x61d2694 VA: 0x75987ea694
	public Single get_Y() { }
	// RVA: 0x61d269c VA: 0x75987ea69c
	public Void set_Y(Single value) { }
	// RVA: 0x61d26a4 VA: 0x75987ea6a4
	public Single get_Rotation() { }
	// RVA: 0x61d26ac VA: 0x75987ea6ac
	public Void set_Rotation(Single value) { }
	// RVA: 0x61d26b4 VA: 0x75987ea6b4
	public Single get_ScaleX() { }
	// RVA: 0x61d26bc VA: 0x75987ea6bc
	public Void set_ScaleX(Single value) { }
	// RVA: 0x61d26c4 VA: 0x75987ea6c4
	public Single get_ScaleY() { }
	// RVA: 0x61d26cc VA: 0x75987ea6cc
	public Void set_ScaleY(Single value) { }
	// RVA: 0x61d26d4 VA: 0x75987ea6d4
	public Single get_Width() { }
	// RVA: 0x61d26dc VA: 0x75987ea6dc
	public Void set_Width(Single value) { }
	// RVA: 0x61d26e4 VA: 0x75987ea6e4
	public Single get_Height() { }
	// RVA: 0x61d26ec VA: 0x75987ea6ec
	public Void set_Height(Single value) { }
	// RVA: 0x61d26f4 VA: 0x75987ea6f4
	public Single get_R() { }
	// RVA: 0x61d26fc VA: 0x75987ea6fc
	public Void set_R(Single value) { }
	// RVA: 0x61d2704 VA: 0x75987ea704
	public Single get_G() { }
	// RVA: 0x61d270c VA: 0x75987ea70c
	public Void set_G(Single value) { }
	// RVA: 0x61d2714 VA: 0x75987ea714
	public Single get_B() { }
	// RVA: 0x61d271c VA: 0x75987ea71c
	public Void set_B(Single value) { }
	// RVA: 0x61d2724 VA: 0x75987ea724
	public Single get_A() { }
	// RVA: 0x61d272c VA: 0x75987ea72c
	public Void set_A(Single value) { }
	// RVA: 0x61d2734 VA: 0x75987ea734
	public String get_Path() { }
	// RVA: 0x61d273c VA: 0x75987ea73c
	public Void set_Path(String value) { }
	// RVA: 0x61d2744 VA: 0x75987ea744
	public Object get_RendererObject() { }
	// RVA: 0x61d274c VA: 0x75987ea74c
	public Void set_RendererObject(Object value) { }
	// RVA: 0x61d2754 VA: 0x75987ea754
	public Single get_RegionOffsetX() { }
	// RVA: 0x61d275c VA: 0x75987ea75c
	public Void set_RegionOffsetX(Single value) { }
	// RVA: 0x61d2764 VA: 0x75987ea764
	public Single get_RegionOffsetY() { }
	// RVA: 0x61d276c VA: 0x75987ea76c
	public Void set_RegionOffsetY(Single value) { }
	// RVA: 0x61d2774 VA: 0x75987ea774
	public Single get_RegionWidth() { }
	// RVA: 0x61d277c VA: 0x75987ea77c
	public Void set_RegionWidth(Single value) { }
	// RVA: 0x61d2784 VA: 0x75987ea784
	public Single get_RegionHeight() { }
	// RVA: 0x61d278c VA: 0x75987ea78c
	public Void set_RegionHeight(Single value) { }
	// RVA: 0x61d2794 VA: 0x75987ea794
	public Single get_RegionOriginalWidth() { }
	// RVA: 0x61d279c VA: 0x75987ea79c
	public Void set_RegionOriginalWidth(Single value) { }
	// RVA: 0x61d27a4 VA: 0x75987ea7a4
	public Single get_RegionOriginalHeight() { }
	// RVA: 0x61d27ac VA: 0x75987ea7ac
	public Void set_RegionOriginalHeight(Single value) { }
	// RVA: 0x61d27b4 VA: 0x75987ea7b4
	public Single[] get_Offset() { }
	// RVA: 0x61d27bc VA: 0x75987ea7bc
	public Single[] get_UVs() { }
	// RVA: 0x61d27c4 VA: 0x75987ea7c4
	public Void .ctor(String name) { }
	// RVA: 0x61d2864 VA: 0x75987ea864
	public Void UpdateOffset() { }
	// RVA: 0x61d2a50 VA: 0x75987eaa50
	public Void SetUVs(Single u, Single v, Single u2, Single v2, Boolean rotate) { }
	// RVA: 0x61d2b08 VA: 0x75987eab08
	public Void ComputeWorldVertices(Bone bone, Single[] worldVertices, Int32 offset, Int32 stride) { }
	// RVA: 0x61d2c7c VA: 0x75987eac7c
	public override Attachment Copy() { }
}
```