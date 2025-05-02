# IkConstraintData

**Namespace:** `Spine`


## Properties

- `BoneData Target`

- `Single Mix`

- `Single Softness`

- `Int32 BendDirection`

- `Boolean Compress`

- `Boolean Stretch`

- `Boolean Uniform`


## Methods

- `BoneData get_Target()`

- `Void set_Target(BoneData)`

- `Single get_Mix()`

- `Void set_Mix(Single)`

- `Single get_Softness()`

- `Void set_Softness(Single)`

- `Int32 get_BendDirection()`

- `Void set_BendDirection(Int32)`

- `Boolean get_Compress()`

- `Void set_Compress(Boolean)`

- `Boolean get_Stretch()`

- `Void set_Stretch(Boolean)`

- `Boolean get_Uniform()`

- `Void set_Uniform(Boolean)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class IkConstraintData : ConstraintData
{
	internal ExposedList`1 bones; // 0x20
	internal BoneData target; // 0x28
	internal Int32 bendDirection; // 0x30
	internal Boolean compress; // 0x34
	internal Boolean stretch; // 0x35
	internal Boolean uniform; // 0x36
	internal Single mix; // 0x38
	internal Single softness; // 0x3c

	public ExposedList`1 Bones { get; }
	public BoneData Target { get; set; }
	public Single Mix { get; set; }
	public Single Softness { get; set; }
	public Int32 BendDirection { get; set; }
	public Boolean Compress { get; set; }
	public Boolean Stretch { get; set; }
	public Boolean Uniform { get; set; }

	// RVA: 0x61d61f0 VA: 0x75987ee1f0
	public Void .ctor(String name) { }
	// RVA: 0x61d6294 VA: 0x75987ee294
	public ExposedList`1 get_Bones() { }
	// RVA: 0x61d629c VA: 0x75987ee29c
	public BoneData get_Target() { }
	// RVA: 0x61d62a4 VA: 0x75987ee2a4
	public Void set_Target(BoneData value) { }
	// RVA: 0x61d62ac VA: 0x75987ee2ac
	public Single get_Mix() { }
	// RVA: 0x61d62b4 VA: 0x75987ee2b4
	public Void set_Mix(Single value) { }
	// RVA: 0x61d62bc VA: 0x75987ee2bc
	public Single get_Softness() { }
	// RVA: 0x61d62c4 VA: 0x75987ee2c4
	public Void set_Softness(Single value) { }
	// RVA: 0x61d62cc VA: 0x75987ee2cc
	public Int32 get_BendDirection() { }
	// RVA: 0x61d62d4 VA: 0x75987ee2d4
	public Void set_BendDirection(Int32 value) { }
	// RVA: 0x61d62dc VA: 0x75987ee2dc
	public Boolean get_Compress() { }
	// RVA: 0x61d62e4 VA: 0x75987ee2e4
	public Void set_Compress(Boolean value) { }
	// RVA: 0x61d62f0 VA: 0x75987ee2f0
	public Boolean get_Stretch() { }
	// RVA: 0x61d62f8 VA: 0x75987ee2f8
	public Void set_Stretch(Boolean value) { }
	// RVA: 0x61d6304 VA: 0x75987ee304
	public Boolean get_Uniform() { }
	// RVA: 0x61d630c VA: 0x75987ee30c
	public Void set_Uniform(Boolean value) { }
}
```