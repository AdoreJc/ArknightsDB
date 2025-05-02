# SlotData

**Namespace:** `Spine`


## Properties

- `Int32 Index`

- `String Name`

- `BoneData BoneData`

- `Single R`

- `Single G`

- `Single B`

- `Single A`

- `Single R2`

- `Single G2`

- `Single B2`

- `Boolean HasSecondColor`

- `String AttachmentName`

- `BlendMode BlendMode`


## Methods

- `Int32 get_Index()`

- `String get_Name()`

- `BoneData get_BoneData()`

- `Single get_R()`

- `Void set_R(Single)`

- `Single get_G()`

- `Void set_G(Single)`

- `Single get_B()`

- `Void set_B(Single)`

- `Single get_A()`

- `Void set_A(Single)`

- `Single get_R2()`

- `Void set_R2(Single)`

- `Single get_G2()`

- `Void set_G2(Single)`

- `Single get_B2()`

- `Void set_B2(Single)`

- `Boolean get_HasSecondColor()`

- `Void set_HasSecondColor(Boolean)`

- `String get_AttachmentName()`

- `Void set_AttachmentName(String)`

- `BlendMode get_BlendMode()`

- `Void set_BlendMode(BlendMode)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class SlotData
{
	internal Int32 index; // 0x10
	internal String name; // 0x18
	internal BoneData boneData; // 0x20
	internal Single r; // 0x28
	internal Single g; // 0x2c
	internal Single b; // 0x30
	internal Single a; // 0x34
	internal Single r2; // 0x38
	internal Single g2; // 0x3c
	internal Single b2; // 0x40
	internal Boolean hasSecondColor; // 0x44
	internal String attachmentName; // 0x48
	internal BlendMode blendMode; // 0x50

	public Int32 Index { get; }
	public String Name { get; }
	public BoneData BoneData { get; }
	public Single R { get; set; }
	public Single G { get; set; }
	public Single B { get; set; }
	public Single A { get; set; }
	public Single R2 { get; set; }
	public Single G2 { get; set; }
	public Single B2 { get; set; }
	public Boolean HasSecondColor { get; set; }
	public String AttachmentName { get; set; }
	public BlendMode BlendMode { get; set; }

	// RVA: 0x61f4158 VA: 0x759880c158
	public Int32 get_Index() { }
	// RVA: 0x61f4160 VA: 0x759880c160
	public String get_Name() { }
	// RVA: 0x61f4168 VA: 0x759880c168
	public BoneData get_BoneData() { }
	// RVA: 0x61f4170 VA: 0x759880c170
	public Single get_R() { }
	// RVA: 0x61f4178 VA: 0x759880c178
	public Void set_R(Single value) { }
	// RVA: 0x61f4180 VA: 0x759880c180
	public Single get_G() { }
	// RVA: 0x61f4188 VA: 0x759880c188
	public Void set_G(Single value) { }
	// RVA: 0x61f4190 VA: 0x759880c190
	public Single get_B() { }
	// RVA: 0x61f4198 VA: 0x759880c198
	public Void set_B(Single value) { }
	// RVA: 0x61f41a0 VA: 0x759880c1a0
	public Single get_A() { }
	// RVA: 0x61f41a8 VA: 0x759880c1a8
	public Void set_A(Single value) { }
	// RVA: 0x61f41b0 VA: 0x759880c1b0
	public Single get_R2() { }
	// RVA: 0x61f41b8 VA: 0x759880c1b8
	public Void set_R2(Single value) { }
	// RVA: 0x61f41c0 VA: 0x759880c1c0
	public Single get_G2() { }
	// RVA: 0x61f41c8 VA: 0x759880c1c8
	public Void set_G2(Single value) { }
	// RVA: 0x61f41d0 VA: 0x759880c1d0
	public Single get_B2() { }
	// RVA: 0x61f41d8 VA: 0x759880c1d8
	public Void set_B2(Single value) { }
	// RVA: 0x61f41e0 VA: 0x759880c1e0
	public Boolean get_HasSecondColor() { }
	// RVA: 0x61f41e8 VA: 0x759880c1e8
	public Void set_HasSecondColor(Boolean value) { }
	// RVA: 0x61f41f4 VA: 0x759880c1f4
	public String get_AttachmentName() { }
	// RVA: 0x61f41fc VA: 0x759880c1fc
	public Void set_AttachmentName(String value) { }
	// RVA: 0x61f4204 VA: 0x759880c204
	public BlendMode get_BlendMode() { }
	// RVA: 0x61f420c VA: 0x759880c20c
	public Void set_BlendMode(BlendMode value) { }
	// RVA: 0x61eb7a0 VA: 0x75988037a0
	public Void .ctor(Int32 index, String name, BoneData boneData) { }
	// RVA: 0x61f4214 VA: 0x759880c214
	public override String ToString() { }
}
```