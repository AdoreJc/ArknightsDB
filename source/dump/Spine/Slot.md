# Slot

**Namespace:** `Spine`


## Properties

- `SlotData Data`

- `Bone Bone`

- `Skeleton Skeleton`

- `Single R`

- `Single G`

- `Single B`

- `Single A`

- `Single R2`

- `Single G2`

- `Single B2`

- `Boolean HasSecondColor`

- `Attachment Attachment`

- `Single AttachmentTime`


## Methods

- `SlotData get_Data()`

- `Bone get_Bone()`

- `Skeleton get_Skeleton()`

- `Single get_R()`

- `Void set_R(Single)`

- `Single get_G()`

- `Void set_G(Single)`

- `Single get_B()`

- `Void set_B(Single)`

- `Single get_A()`

- `Void set_A(Single)`

- `Void ClampColor()`

- `Single get_R2()`

- `Void set_R2(Single)`

- `Single get_G2()`

- `Void set_G2(Single)`

- `Single get_B2()`

- `Void set_B2(Single)`

- `Boolean get_HasSecondColor()`

- `Void set_HasSecondColor(Boolean)`

- `Void ClampSecondColor()`

- `Attachment get_Attachment()`

- `Void set_Attachment(Attachment)`

- `Single get_AttachmentTime()`

- `Void set_AttachmentTime(Single)`

- `Void set_Deform(ExposedList`1)`

- `Void SetToSetupPose()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class Slot
{
	internal SlotData data; // 0x10
	internal Bone bone; // 0x18
	internal Single r; // 0x20
	internal Single g; // 0x24
	internal Single b; // 0x28
	internal Single a; // 0x2c
	internal Single r2; // 0x30
	internal Single g2; // 0x34
	internal Single b2; // 0x38
	internal Boolean hasSecondColor; // 0x3c
	internal Attachment attachment; // 0x40
	internal Single attachmentTime; // 0x48
	internal ExposedList`1 deform; // 0x50
	internal Int32 attachmentState; // 0x58

	public SlotData Data { get; }
	public Bone Bone { get; }
	public Skeleton Skeleton { get; }
	public Single R { get; set; }
	public Single G { get; set; }
	public Single B { get; set; }
	public Single A { get; set; }
	public Single R2 { get; set; }
	public Single G2 { get; set; }
	public Single B2 { get; set; }
	public Boolean HasSecondColor { get; set; }
	public Attachment Attachment { get; set; }
	public Single AttachmentTime { get; set; }
	public ExposedList`1 Deform { get; set; }

	// RVA: 0x61f3a34 VA: 0x759880ba34
	public Void .ctor(SlotData data, Bone bone) { }
	// RVA: 0x61f3c38 VA: 0x759880bc38
	public Void .ctor(Slot slot, Bone bone) { }
	// RVA: 0x61f3e00 VA: 0x759880be00
	public SlotData get_Data() { }
	// RVA: 0x61f3e08 VA: 0x759880be08
	public Bone get_Bone() { }
	// RVA: 0x61f3e10 VA: 0x759880be10
	public Skeleton get_Skeleton() { }
	// RVA: 0x61f3e2c VA: 0x759880be2c
	public Single get_R() { }
	// RVA: 0x61f3e34 VA: 0x759880be34
	public Void set_R(Single value) { }
	// RVA: 0x61f3e3c VA: 0x759880be3c
	public Single get_G() { }
	// RVA: 0x61f3e44 VA: 0x759880be44
	public Void set_G(Single value) { }
	// RVA: 0x61f3e4c VA: 0x759880be4c
	public Single get_B() { }
	// RVA: 0x61f3e54 VA: 0x759880be54
	public Void set_B(Single value) { }
	// RVA: 0x61f3e5c VA: 0x759880be5c
	public Single get_A() { }
	// RVA: 0x61f3e64 VA: 0x759880be64
	public Void set_A(Single value) { }
	// RVA: 0x61f3e6c VA: 0x759880be6c
	public Void ClampColor() { }
	// RVA: 0x61f3f38 VA: 0x759880bf38
	public Single get_R2() { }
	// RVA: 0x61f3f40 VA: 0x759880bf40
	public Void set_R2(Single value) { }
	// RVA: 0x61f3f48 VA: 0x759880bf48
	public Single get_G2() { }
	// RVA: 0x61f3f50 VA: 0x759880bf50
	public Void set_G2(Single value) { }
	// RVA: 0x61f3f58 VA: 0x759880bf58
	public Single get_B2() { }
	// RVA: 0x61f3f60 VA: 0x759880bf60
	public Void set_B2(Single value) { }
	// RVA: 0x61f3f68 VA: 0x759880bf68
	public Boolean get_HasSecondColor() { }
	// RVA: 0x61f3f84 VA: 0x759880bf84
	public Void set_HasSecondColor(Boolean value) { }
	// RVA: 0x61f3fa4 VA: 0x759880bfa4
	public Void ClampSecondColor() { }
	// RVA: 0x61f4054 VA: 0x759880c054
	public Attachment get_Attachment() { }
	// RVA: 0x61f38ac VA: 0x759880b8ac
	public Void set_Attachment(Attachment value) { }
	// RVA: 0x61f405c VA: 0x759880c05c
	public Single get_AttachmentTime() { }
	// RVA: 0x61f4088 VA: 0x759880c088
	public Void set_AttachmentTime(Single value) { }
	// RVA: 0x61f40b4 VA: 0x759880c0b4
	public ExposedList`1 get_Deform() { }
	// RVA: 0x61f40bc VA: 0x759880c0bc
	public Void set_Deform(ExposedList`1 value) { }
	// RVA: 0x61f3ba0 VA: 0x759880bba0
	public Void SetToSetupPose() { }
	// RVA: 0x61f413c VA: 0x759880c13c
	public override String ToString() { }
}
```