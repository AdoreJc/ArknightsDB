# MeshAttachment

**Namespace:** `Spine`


## Fields

- `MeshAttachment parentMesh`

- `String <Path>k__BackingField`

- `Object <RendererObject>k__BackingField`

- `Single <RegionU>k__BackingField`

- `Single <RegionV>k__BackingField`

- `Single <RegionU2>k__BackingField`

- `Single <RegionV2>k__BackingField`

- `Boolean <RegionRotate>k__BackingField`

- `Int32 <RegionDegrees>k__BackingField`

- `Single <Width>k__BackingField`

- `Single <Height>k__BackingField`


## Properties

- `Int32 HullLength`

- `Single R`

- `Single G`

- `Single B`

- `Single A`

- `String Path`

- `Object RendererObject`

- `Single RegionU`

- `Single RegionV`

- `Single RegionU2`

- `Single RegionV2`

- `Boolean RegionRotate`

- `Int32 RegionDegrees`

- `Single RegionOffsetX`

- `Single RegionOffsetY`

- `Single RegionWidth`

- `Single RegionHeight`

- `Single RegionOriginalWidth`

- `Single RegionOriginalHeight`

- `MeshAttachment ParentMesh`

- `Single Width`

- `Single Height`


## Methods

- `Int32 get_HullLength()`

- `Void set_HullLength(Int32)`

- `Void set_RegionUVs(Single[])`

- `Void set_UVs(Single[])`

- `Void set_Triangles(Int32[])`

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

- `Single get_RegionU()`

- `Void set_RegionU(Single)`

- `Single get_RegionV()`

- `Void set_RegionV(Single)`

- `Single get_RegionU2()`

- `Void set_RegionU2(Single)`

- `Single get_RegionV2()`

- `Void set_RegionV2(Single)`

- `Boolean get_RegionRotate()`

- `Void set_RegionRotate(Boolean)`

- `Int32 get_RegionDegrees()`

- `Void set_RegionDegrees(Int32)`

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

- `MeshAttachment get_ParentMesh()`

- `Void set_ParentMesh(MeshAttachment)`

- `Void set_Edges(Int32[])`

- `Single get_Width()`

- `Void set_Width(Single)`

- `Single get_Height()`

- `Void set_Height(Single)`

- `Void UpdateUVs()`

- `MeshAttachment NewLinkedMesh()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class MeshAttachment : VertexAttachment, IHasRendererObject
{
	internal Single regionOffsetX; // 0x40
	internal Single regionOffsetY; // 0x44
	internal Single regionWidth; // 0x48
	internal Single regionHeight; // 0x4c
	internal Single regionOriginalWidth; // 0x50
	internal Single regionOriginalHeight; // 0x54
	private MeshAttachment parentMesh; // 0x58
	internal Single[] uvs; // 0x60
	internal Single[] regionUVs; // 0x68
	internal Int32[] triangles; // 0x70
	internal Single r; // 0x78
	internal Single g; // 0x7c
	internal Single b; // 0x80
	internal Single a; // 0x84
	internal Int32 hulllength; // 0x88
	private String <Path>k__BackingField; // 0x90
	private Object <RendererObject>k__BackingField; // 0x98
	private Single <RegionU>k__BackingField; // 0xa0
	private Single <RegionV>k__BackingField; // 0xa4
	private Single <RegionU2>k__BackingField; // 0xa8
	private Single <RegionV2>k__BackingField; // 0xac
	private Boolean <RegionRotate>k__BackingField; // 0xb0
	private Int32 <RegionDegrees>k__BackingField; // 0xb4
	private Int32[] <Edges>k__BackingField; // 0xb8
	private Single <Width>k__BackingField; // 0xc0
	private Single <Height>k__BackingField; // 0xc4

	public Int32 HullLength { get; set; }
	public Single[] RegionUVs { get; set; }
	public Single[] UVs { get; set; }
	public Int32[] Triangles { get; set; }
	public Single R { get; set; }
	public Single G { get; set; }
	public Single B { get; set; }
	public Single A { get; set; }
	public String Path { get; set; }
	public Object RendererObject { get; set; }
	public Single RegionU { get; set; }
	public Single RegionV { get; set; }
	public Single RegionU2 { get; set; }
	public Single RegionV2 { get; set; }
	public Boolean RegionRotate { get; set; }
	public Int32 RegionDegrees { get; set; }
	public Single RegionOffsetX { get; set; }
	public Single RegionOffsetY { get; set; }
	public Single RegionWidth { get; set; }
	public Single RegionHeight { get; set; }
	public Single RegionOriginalWidth { get; set; }
	public Single RegionOriginalHeight { get; set; }
	public MeshAttachment ParentMesh { get; set; }
	public Int32[] Edges { get; set; }
	public Single Width { get; set; }
	public Single Height { get; set; }

	// RVA: 0x61d1628 VA: 0x75987e9628
	public Int32 get_HullLength() { }
	// RVA: 0x61d1630 VA: 0x75987e9630
	public Void set_HullLength(Int32 value) { }
	// RVA: 0x61d1638 VA: 0x75987e9638
	public Single[] get_RegionUVs() { }
	// RVA: 0x61d1640 VA: 0x75987e9640
	public Void set_RegionUVs(Single[] value) { }
	// RVA: 0x61d1648 VA: 0x75987e9648
	public Single[] get_UVs() { }
	// RVA: 0x61d1650 VA: 0x75987e9650
	public Void set_UVs(Single[] value) { }
	// RVA: 0x61d1658 VA: 0x75987e9658
	public Int32[] get_Triangles() { }
	// RVA: 0x61d1660 VA: 0x75987e9660
	public Void set_Triangles(Int32[] value) { }
	// RVA: 0x61d1668 VA: 0x75987e9668
	public Single get_R() { }
	// RVA: 0x61d1670 VA: 0x75987e9670
	public Void set_R(Single value) { }
	// RVA: 0x61d1678 VA: 0x75987e9678
	public Single get_G() { }
	// RVA: 0x61d1680 VA: 0x75987e9680
	public Void set_G(Single value) { }
	// RVA: 0x61d1688 VA: 0x75987e9688
	public Single get_B() { }
	// RVA: 0x61d1690 VA: 0x75987e9690
	public Void set_B(Single value) { }
	// RVA: 0x61d1698 VA: 0x75987e9698
	public Single get_A() { }
	// RVA: 0x61d16a0 VA: 0x75987e96a0
	public Void set_A(Single value) { }
	// RVA: 0x61d16a8 VA: 0x75987e96a8
	public String get_Path() { }
	// RVA: 0x61d16b0 VA: 0x75987e96b0
	public Void set_Path(String value) { }
	// RVA: 0x61d16b8 VA: 0x75987e96b8
	public Object get_RendererObject() { }
	// RVA: 0x61d16c0 VA: 0x75987e96c0
	public Void set_RendererObject(Object value) { }
	// RVA: 0x61d16c8 VA: 0x75987e96c8
	public Single get_RegionU() { }
	// RVA: 0x61d16d0 VA: 0x75987e96d0
	public Void set_RegionU(Single value) { }
	// RVA: 0x61d16d8 VA: 0x75987e96d8
	public Single get_RegionV() { }
	// RVA: 0x61d16e0 VA: 0x75987e96e0
	public Void set_RegionV(Single value) { }
	// RVA: 0x61d16e8 VA: 0x75987e96e8
	public Single get_RegionU2() { }
	// RVA: 0x61d16f0 VA: 0x75987e96f0
	public Void set_RegionU2(Single value) { }
	// RVA: 0x61d16f8 VA: 0x75987e96f8
	public Single get_RegionV2() { }
	// RVA: 0x61d1700 VA: 0x75987e9700
	public Void set_RegionV2(Single value) { }
	// RVA: 0x61d1708 VA: 0x75987e9708
	public Boolean get_RegionRotate() { }
	// RVA: 0x61d1710 VA: 0x75987e9710
	public Void set_RegionRotate(Boolean value) { }
	// RVA: 0x61d171c VA: 0x75987e971c
	public Int32 get_RegionDegrees() { }
	// RVA: 0x61d1724 VA: 0x75987e9724
	public Void set_RegionDegrees(Int32 value) { }
	// RVA: 0x61d172c VA: 0x75987e972c
	public Single get_RegionOffsetX() { }
	// RVA: 0x61d1734 VA: 0x75987e9734
	public Void set_RegionOffsetX(Single value) { }
	// RVA: 0x61d173c VA: 0x75987e973c
	public Single get_RegionOffsetY() { }
	// RVA: 0x61d1744 VA: 0x75987e9744
	public Void set_RegionOffsetY(Single value) { }
	// RVA: 0x61d174c VA: 0x75987e974c
	public Single get_RegionWidth() { }
	// RVA: 0x61d1754 VA: 0x75987e9754
	public Void set_RegionWidth(Single value) { }
	// RVA: 0x61d175c VA: 0x75987e975c
	public Single get_RegionHeight() { }
	// RVA: 0x61d1764 VA: 0x75987e9764
	public Void set_RegionHeight(Single value) { }
	// RVA: 0x61d176c VA: 0x75987e976c
	public Single get_RegionOriginalWidth() { }
	// RVA: 0x61d1774 VA: 0x75987e9774
	public Void set_RegionOriginalWidth(Single value) { }
	// RVA: 0x61d177c VA: 0x75987e977c
	public Single get_RegionOriginalHeight() { }
	// RVA: 0x61d1784 VA: 0x75987e9784
	public Void set_RegionOriginalHeight(Single value) { }
	// RVA: 0x61d178c VA: 0x75987e978c
	public MeshAttachment get_ParentMesh() { }
	// RVA: 0x61d1794 VA: 0x75987e9794
	public Void set_ParentMesh(MeshAttachment value) { }
	// RVA: 0x61d1824 VA: 0x75987e9824
	public Int32[] get_Edges() { }
	// RVA: 0x61d182c VA: 0x75987e982c
	public Void set_Edges(Int32[] value) { }
	// RVA: 0x61d1834 VA: 0x75987e9834
	public Single get_Width() { }
	// RVA: 0x61d183c VA: 0x75987e983c
	public Void set_Width(Single value) { }
	// RVA: 0x61d1844 VA: 0x75987e9844
	public Single get_Height() { }
	// RVA: 0x61d184c VA: 0x75987e984c
	public Void set_Height(Single value) { }
	// RVA: 0x61d11ac VA: 0x75987e91ac
	public Void .ctor(String name) { }
	// RVA: 0x61d1854 VA: 0x75987e9854
	public Void UpdateUVs() { }
	// RVA: 0x61d1c1c VA: 0x75987e9c1c
	public override Attachment Copy() { }
	// RVA: 0x61d1e68 VA: 0x75987e9e68
	public MeshAttachment NewLinkedMesh() { }
}
```