# BoneData

**Namespace:** `Spine`


## Properties

- `Int32 Index`

- `String Name`

- `BoneData Parent`

- `Single Length`

- `Single X`

- `Single Y`

- `Single Rotation`

- `Single ScaleX`

- `Single ScaleY`

- `Single ShearX`

- `Single ShearY`

- `TransformMode TransformMode`

- `Boolean SkinRequired`


## Methods

- `Int32 get_Index()`

- `String get_Name()`

- `BoneData get_Parent()`

- `Single get_Length()`

- `Void set_Length(Single)`

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

- `Single get_ShearX()`

- `Void set_ShearX(Single)`

- `Single get_ShearY()`

- `Void set_ShearY(Single)`

- `TransformMode get_TransformMode()`

- `Void set_TransformMode(TransformMode)`

- `Boolean get_SkinRequired()`

- `Void set_SkinRequired(Boolean)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class BoneData
{
	internal Int32 index; // 0x10
	internal String name; // 0x18
	internal BoneData parent; // 0x20
	internal Single length; // 0x28
	internal Single x; // 0x2c
	internal Single y; // 0x30
	internal Single rotation; // 0x34
	internal Single scaleX; // 0x38
	internal Single scaleY; // 0x3c
	internal Single shearX; // 0x40
	internal Single shearY; // 0x44
	internal TransformMode transformMode; // 0x48
	internal Boolean skinRequired; // 0x4c

	public Int32 Index { get; }
	public String Name { get; }
	public BoneData Parent { get; }
	public Single Length { get; set; }
	public Single X { get; set; }
	public Single Y { get; set; }
	public Single Rotation { get; set; }
	public Single ScaleX { get; set; }
	public Single ScaleY { get; set; }
	public Single ShearX { get; set; }
	public Single ShearY { get; set; }
	public TransformMode TransformMode { get; set; }
	public Boolean SkinRequired { get; set; }

	// RVA: 0x61d477c VA: 0x75987ec77c
	public Int32 get_Index() { }
	// RVA: 0x61d4784 VA: 0x75987ec784
	public String get_Name() { }
	// RVA: 0x61d478c VA: 0x75987ec78c
	public BoneData get_Parent() { }
	// RVA: 0x61d4794 VA: 0x75987ec794
	public Single get_Length() { }
	// RVA: 0x61d479c VA: 0x75987ec79c
	public Void set_Length(Single value) { }
	// RVA: 0x61d47a4 VA: 0x75987ec7a4
	public Single get_X() { }
	// RVA: 0x61d47ac VA: 0x75987ec7ac
	public Void set_X(Single value) { }
	// RVA: 0x61d47b4 VA: 0x75987ec7b4
	public Single get_Y() { }
	// RVA: 0x61d47bc VA: 0x75987ec7bc
	public Void set_Y(Single value) { }
	// RVA: 0x61d47c4 VA: 0x75987ec7c4
	public Single get_Rotation() { }
	// RVA: 0x61d47cc VA: 0x75987ec7cc
	public Void set_Rotation(Single value) { }
	// RVA: 0x61d47d4 VA: 0x75987ec7d4
	public Single get_ScaleX() { }
	// RVA: 0x61d47dc VA: 0x75987ec7dc
	public Void set_ScaleX(Single value) { }
	// RVA: 0x61d47e4 VA: 0x75987ec7e4
	public Single get_ScaleY() { }
	// RVA: 0x61d47ec VA: 0x75987ec7ec
	public Void set_ScaleY(Single value) { }
	// RVA: 0x61d47f4 VA: 0x75987ec7f4
	public Single get_ShearX() { }
	// RVA: 0x61d47fc VA: 0x75987ec7fc
	public Void set_ShearX(Single value) { }
	// RVA: 0x61d4804 VA: 0x75987ec804
	public Single get_ShearY() { }
	// RVA: 0x61d480c VA: 0x75987ec80c
	public Void set_ShearY(Single value) { }
	// RVA: 0x61d4814 VA: 0x75987ec814
	public TransformMode get_TransformMode() { }
	// RVA: 0x61d481c VA: 0x75987ec81c
	public Void set_TransformMode(TransformMode value) { }
	// RVA: 0x61d4824 VA: 0x75987ec824
	public Boolean get_SkinRequired() { }
	// RVA: 0x61d482c VA: 0x75987ec82c
	public Void set_SkinRequired(Boolean value) { }
	// RVA: 0x61d4838 VA: 0x75987ec838
	public Void .ctor(Int32 index, String name, BoneData parent) { }
	// RVA: 0x61d4948 VA: 0x75987ec948
	public override String ToString() { }
}
```