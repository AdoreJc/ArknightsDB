# TransformConstraintData

**Namespace:** `Spine`


## Properties

- `BoneData Target`

- `Single RotateMix`

- `Single TranslateMix`

- `Single ScaleMix`

- `Single ShearMix`

- `Single OffsetRotation`

- `Single OffsetX`

- `Single OffsetY`

- `Single OffsetScaleX`

- `Single OffsetScaleY`

- `Single OffsetShearY`

- `Boolean Relative`

- `Boolean Local`


## Methods

- `BoneData get_Target()`

- `Void set_Target(BoneData)`

- `Single get_RotateMix()`

- `Void set_RotateMix(Single)`

- `Single get_TranslateMix()`

- `Void set_TranslateMix(Single)`

- `Single get_ScaleMix()`

- `Void set_ScaleMix(Single)`

- `Single get_ShearMix()`

- `Void set_ShearMix(Single)`

- `Single get_OffsetRotation()`

- `Void set_OffsetRotation(Single)`

- `Single get_OffsetX()`

- `Void set_OffsetX(Single)`

- `Single get_OffsetY()`

- `Void set_OffsetY(Single)`

- `Single get_OffsetScaleX()`

- `Void set_OffsetScaleX(Single)`

- `Single get_OffsetScaleY()`

- `Void set_OffsetScaleY(Single)`

- `Single get_OffsetShearY()`

- `Void set_OffsetShearY(Single)`

- `Boolean get_Relative()`

- `Void set_Relative(Boolean)`

- `Boolean get_Local()`

- `Void set_Local(Boolean)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class TransformConstraintData : ConstraintData
{
	internal ExposedList`1 bones; // 0x20
	internal BoneData target; // 0x28
	internal Single rotateMix; // 0x30
	internal Single translateMix; // 0x34
	internal Single scaleMix; // 0x38
	internal Single shearMix; // 0x3c
	internal Single offsetRotation; // 0x40
	internal Single offsetX; // 0x44
	internal Single offsetY; // 0x48
	internal Single offsetScaleX; // 0x4c
	internal Single offsetScaleY; // 0x50
	internal Single offsetShearY; // 0x54
	internal Boolean relative; // 0x58
	internal Boolean local; // 0x59

	public ExposedList`1 Bones { get; }
	public BoneData Target { get; set; }
	public Single RotateMix { get; set; }
	public Single TranslateMix { get; set; }
	public Single ScaleMix { get; set; }
	public Single ShearMix { get; set; }
	public Single OffsetRotation { get; set; }
	public Single OffsetX { get; set; }
	public Single OffsetY { get; set; }
	public Single OffsetScaleX { get; set; }
	public Single OffsetScaleY { get; set; }
	public Single OffsetShearY { get; set; }
	public Boolean Relative { get; set; }
	public Boolean Local { get; set; }

	// RVA: 0x61f5640 VA: 0x759880d640
	public ExposedList`1 get_Bones() { }
	// RVA: 0x61f5648 VA: 0x759880d648
	public BoneData get_Target() { }
	// RVA: 0x61f5650 VA: 0x759880d650
	public Void set_Target(BoneData value) { }
	// RVA: 0x61f5658 VA: 0x759880d658
	public Single get_RotateMix() { }
	// RVA: 0x61f5660 VA: 0x759880d660
	public Void set_RotateMix(Single value) { }
	// RVA: 0x61f5668 VA: 0x759880d668
	public Single get_TranslateMix() { }
	// RVA: 0x61f5670 VA: 0x759880d670
	public Void set_TranslateMix(Single value) { }
	// RVA: 0x61f5678 VA: 0x759880d678
	public Single get_ScaleMix() { }
	// RVA: 0x61f5680 VA: 0x759880d680
	public Void set_ScaleMix(Single value) { }
	// RVA: 0x61f5688 VA: 0x759880d688
	public Single get_ShearMix() { }
	// RVA: 0x61f5690 VA: 0x759880d690
	public Void set_ShearMix(Single value) { }
	// RVA: 0x61f5698 VA: 0x759880d698
	public Single get_OffsetRotation() { }
	// RVA: 0x61f56a0 VA: 0x759880d6a0
	public Void set_OffsetRotation(Single value) { }
	// RVA: 0x61f56a8 VA: 0x759880d6a8
	public Single get_OffsetX() { }
	// RVA: 0x61f56b0 VA: 0x759880d6b0
	public Void set_OffsetX(Single value) { }
	// RVA: 0x61f56b8 VA: 0x759880d6b8
	public Single get_OffsetY() { }
	// RVA: 0x61f56c0 VA: 0x759880d6c0
	public Void set_OffsetY(Single value) { }
	// RVA: 0x61f56c8 VA: 0x759880d6c8
	public Single get_OffsetScaleX() { }
	// RVA: 0x61f56d0 VA: 0x759880d6d0
	public Void set_OffsetScaleX(Single value) { }
	// RVA: 0x61f56d8 VA: 0x759880d6d8
	public Single get_OffsetScaleY() { }
	// RVA: 0x61f56e0 VA: 0x759880d6e0
	public Void set_OffsetScaleY(Single value) { }
	// RVA: 0x61f56e8 VA: 0x759880d6e8
	public Single get_OffsetShearY() { }
	// RVA: 0x61f56f0 VA: 0x759880d6f0
	public Void set_OffsetShearY(Single value) { }
	// RVA: 0x61f56f8 VA: 0x759880d6f8
	public Boolean get_Relative() { }
	// RVA: 0x61f5700 VA: 0x759880d700
	public Void set_Relative(Boolean value) { }
	// RVA: 0x61f570c VA: 0x759880d70c
	public Boolean get_Local() { }
	// RVA: 0x61f5714 VA: 0x759880d714
	public Void set_Local(Boolean value) { }
	// RVA: 0x61ebb1c VA: 0x7598803b1c
	public Void .ctor(String name) { }
}
```