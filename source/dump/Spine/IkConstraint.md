# IkConstraint

**Namespace:** `Spine`


## Properties

- `Bone Target`

- `Single Mix`

- `Single Softness`

- `Int32 BendDirection`

- `Boolean Compress`

- `Boolean Stretch`

- `Boolean Active`

- `IkConstraintData Data`


## Methods

- `Void Apply()`

- `Void Update()`

- `Bone get_Target()`

- `Void set_Target(Bone)`

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

- `Boolean get_Active()`

- `IkConstraintData get_Data()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class IkConstraint : IUpdatable
{
	internal IkConstraintData data; // 0x10
	internal ExposedList`1 bones; // 0x18
	internal Bone target; // 0x20
	internal Int32 bendDirection; // 0x28
	internal Boolean compress; // 0x2c
	internal Boolean stretch; // 0x2d
	internal Single mix; // 0x30
	internal Single softness; // 0x34
	internal Boolean active; // 0x38

	public ExposedList`1 Bones { get; }
	public Bone Target { get; set; }
	public Single Mix { get; set; }
	public Single Softness { get; set; }
	public Int32 BendDirection { get; set; }
	public Boolean Compress { get; set; }
	public Boolean Stretch { get; set; }
	public Boolean Active { get; }
	public IkConstraintData Data { get; }

	// RVA: 0x61d4c3c VA: 0x75987ecc3c
	public Void .ctor(IkConstraintData data, Skeleton skeleton) { }
	// RVA: 0x61d507c VA: 0x75987ed07c
	public Void .ctor(IkConstraint constraint, Skeleton skeleton) { }
	// RVA: 0x61d53f4 VA: 0x75987ed3f4
	public Void Apply() { }
	// RVA: 0x61d53f8 VA: 0x75987ed3f8
	public Void Update() { }
	// RVA: 0x61d6154 VA: 0x75987ee154
	public ExposedList`1 get_Bones() { }
	// RVA: 0x61d615c VA: 0x75987ee15c
	public Bone get_Target() { }
	// RVA: 0x61d6164 VA: 0x75987ee164
	public Void set_Target(Bone value) { }
	// RVA: 0x61d616c VA: 0x75987ee16c
	public Single get_Mix() { }
	// RVA: 0x61d6174 VA: 0x75987ee174
	public Void set_Mix(Single value) { }
	// RVA: 0x61d617c VA: 0x75987ee17c
	public Single get_Softness() { }
	// RVA: 0x61d6184 VA: 0x75987ee184
	public Void set_Softness(Single value) { }
	// RVA: 0x61d618c VA: 0x75987ee18c
	public Int32 get_BendDirection() { }
	// RVA: 0x61d6194 VA: 0x75987ee194
	public Void set_BendDirection(Int32 value) { }
	// RVA: 0x61d619c VA: 0x75987ee19c
	public Boolean get_Compress() { }
	// RVA: 0x61d61a4 VA: 0x75987ee1a4
	public Void set_Compress(Boolean value) { }
	// RVA: 0x61d61b0 VA: 0x75987ee1b0
	public Boolean get_Stretch() { }
	// RVA: 0x61d61b8 VA: 0x75987ee1b8
	public Void set_Stretch(Boolean value) { }
	// RVA: 0x61d61c4 VA: 0x75987ee1c4
	public Boolean get_Active() { }
	// RVA: 0x61d61cc VA: 0x75987ee1cc
	public IkConstraintData get_Data() { }
	// RVA: 0x61d61d4 VA: 0x75987ee1d4
	public override String ToString() { }
	// RVA: 0x61d54b0 VA: 0x75987ed4b0
	public static Void Apply(Bone bone, Single targetX, Single targetY, Boolean compress, Boolean stretch, Boolean uniform, Single alpha) { }
	// RVA: 0x61d5820 VA: 0x75987ed820
	public static Void Apply(Bone parent, Bone child, Single targetX, Single targetY, Int32 bendDir, Boolean stretch, Single softness, Single alpha) { }
}
```