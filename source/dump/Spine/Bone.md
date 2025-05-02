# Bone

**Namespace:** `Spine`


## Properties

- `BoneData Data`

- `Skeleton Skeleton`

- `Bone Parent`

- `Boolean Active`

- `Single X`

- `Single Y`

- `Single Rotation`

- `Single ScaleX`

- `Single ScaleY`

- `Single ShearX`

- `Single ShearY`

- `Single AppliedRotation`

- `Single AX`

- `Single AY`

- `Single AScaleX`

- `Single AScaleY`

- `Single AShearX`

- `Single AShearY`

- `Single A`

- `Single B`

- `Single C`

- `Single D`

- `Single WorldX`

- `Single WorldY`

- `Single WorldRotationX`

- `Single WorldRotationY`

- `Single WorldScaleX`

- `Single WorldScaleY`

- `Single WorldToLocalRotationX`

- `Single WorldToLocalRotationY`


## Methods

- `BoneData get_Data()`

- `Skeleton get_Skeleton()`

- `Bone get_Parent()`

- `Boolean get_Active()`

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

- `Single get_AppliedRotation()`

- `Void set_AppliedRotation(Single)`

- `Single get_AX()`

- `Void set_AX(Single)`

- `Single get_AY()`

- `Void set_AY(Single)`

- `Single get_AScaleX()`

- `Void set_AScaleX(Single)`

- `Single get_AScaleY()`

- `Void set_AScaleY(Single)`

- `Single get_AShearX()`

- `Void set_AShearX(Single)`

- `Single get_AShearY()`

- `Void set_AShearY(Single)`

- `Single get_A()`

- `Single get_B()`

- `Single get_C()`

- `Single get_D()`

- `Single get_WorldX()`

- `Single get_WorldY()`

- `Single get_WorldRotationX()`

- `Single get_WorldRotationY()`

- `Single get_WorldScaleX()`

- `Single get_WorldScaleY()`

- `Void Update()`

- `Void UpdateWorldTransform()`

- `Void UpdateWorldTransform(Single, Single, Single, Single, Single, Single, Single)`

- `Void SetToSetupPose()`

- `Void WorldToLocal(Single, Single, out, out)`

- `Void LocalToWorld(Single, Single, out, out)`

- `Single get_WorldToLocalRotationX()`

- `Single get_WorldToLocalRotationY()`

- `Single WorldToLocalRotation(Single)`

- `Single LocalToWorldRotation(Single)`

- `Void RotateWorld(Single)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class Bone : IUpdatable
{
	public static Boolean yDown; // 0x0
	internal BoneData data; // 0x10
	internal Skeleton skeleton; // 0x18
	internal Bone parent; // 0x20
	internal ExposedList`1 children; // 0x28
	internal Single x; // 0x30
	internal Single y; // 0x34
	internal Single rotation; // 0x38
	internal Single scaleX; // 0x3c
	internal Single scaleY; // 0x40
	internal Single shearX; // 0x44
	internal Single shearY; // 0x48
	internal Single ax; // 0x4c
	internal Single ay; // 0x50
	internal Single arotation; // 0x54
	internal Single ascaleX; // 0x58
	internal Single ascaleY; // 0x5c
	internal Single ashearX; // 0x60
	internal Single ashearY; // 0x64
	internal Boolean appliedValid; // 0x68
	internal Single a; // 0x6c
	internal Single b; // 0x70
	internal Single worldX; // 0x74
	internal Single c; // 0x78
	internal Single d; // 0x7c
	internal Single worldY; // 0x80
	internal Boolean sorted; // 0x84
	internal Boolean active; // 0x85

	public BoneData Data { get; }
	public Skeleton Skeleton { get; }
	public Bone Parent { get; }
	public ExposedList`1 Children { get; }
	public Boolean Active { get; }
	public Single X { get; set; }
	public Single Y { get; set; }
	public Single Rotation { get; set; }
	public Single ScaleX { get; set; }
	public Single ScaleY { get; set; }
	public Single ShearX { get; set; }
	public Single ShearY { get; set; }
	public Single AppliedRotation { get; set; }
	public Single AX { get; set; }
	public Single AY { get; set; }
	public Single AScaleX { get; set; }
	public Single AScaleY { get; set; }
	public Single AShearX { get; set; }
	public Single AShearY { get; set; }
	public Single A { get; }
	public Single B { get; }
	public Single C { get; }
	public Single D { get; }
	public Single WorldX { get; }
	public Single WorldY { get; }
	public Single WorldRotationX { get; }
	public Single WorldRotationY { get; }
	public Single WorldScaleX { get; }
	public Single WorldScaleY { get; }
	public Single WorldToLocalRotationX { get; }
	public Single WorldToLocalRotationY { get; }

	// RVA: 0x61d32a0 VA: 0x75987eb2a0
	public BoneData get_Data() { }
	// RVA: 0x61d32a8 VA: 0x75987eb2a8
	public Skeleton get_Skeleton() { }
	// RVA: 0x61d32b0 VA: 0x75987eb2b0
	public Bone get_Parent() { }
	// RVA: 0x61d32b8 VA: 0x75987eb2b8
	public ExposedList`1 get_Children() { }
	// RVA: 0x61d32c0 VA: 0x75987eb2c0
	public Boolean get_Active() { }
	// RVA: 0x61d32c8 VA: 0x75987eb2c8
	public Single get_X() { }
	// RVA: 0x61d32d0 VA: 0x75987eb2d0
	public Void set_X(Single value) { }
	// RVA: 0x61d32d8 VA: 0x75987eb2d8
	public Single get_Y() { }
	// RVA: 0x61d32e0 VA: 0x75987eb2e0
	public Void set_Y(Single value) { }
	// RVA: 0x61d32e8 VA: 0x75987eb2e8
	public Single get_Rotation() { }
	// RVA: 0x61d32f0 VA: 0x75987eb2f0
	public Void set_Rotation(Single value) { }
	// RVA: 0x61d32f8 VA: 0x75987eb2f8
	public Single get_ScaleX() { }
	// RVA: 0x61d3300 VA: 0x75987eb300
	public Void set_ScaleX(Single value) { }
	// RVA: 0x61d3308 VA: 0x75987eb308
	public Single get_ScaleY() { }
	// RVA: 0x61d3310 VA: 0x75987eb310
	public Void set_ScaleY(Single value) { }
	// RVA: 0x61d3318 VA: 0x75987eb318
	public Single get_ShearX() { }
	// RVA: 0x61d3320 VA: 0x75987eb320
	public Void set_ShearX(Single value) { }
	// RVA: 0x61d3328 VA: 0x75987eb328
	public Single get_ShearY() { }
	// RVA: 0x61d3330 VA: 0x75987eb330
	public Void set_ShearY(Single value) { }
	// RVA: 0x61d3338 VA: 0x75987eb338
	public Single get_AppliedRotation() { }
	// RVA: 0x61d3340 VA: 0x75987eb340
	public Void set_AppliedRotation(Single value) { }
	// RVA: 0x61d3348 VA: 0x75987eb348
	public Single get_AX() { }
	// RVA: 0x61d3350 VA: 0x75987eb350
	public Void set_AX(Single value) { }
	// RVA: 0x61d3358 VA: 0x75987eb358
	public Single get_AY() { }
	// RVA: 0x61d3360 VA: 0x75987eb360
	public Void set_AY(Single value) { }
	// RVA: 0x61d3368 VA: 0x75987eb368
	public Single get_AScaleX() { }
	// RVA: 0x61d3370 VA: 0x75987eb370
	public Void set_AScaleX(Single value) { }
	// RVA: 0x61d3378 VA: 0x75987eb378
	public Single get_AScaleY() { }
	// RVA: 0x61d3380 VA: 0x75987eb380
	public Void set_AScaleY(Single value) { }
	// RVA: 0x61d3388 VA: 0x75987eb388
	public Single get_AShearX() { }
	// RVA: 0x61d3390 VA: 0x75987eb390
	public Void set_AShearX(Single value) { }
	// RVA: 0x61d3398 VA: 0x75987eb398
	public Single get_AShearY() { }
	// RVA: 0x61d33a0 VA: 0x75987eb3a0
	public Void set_AShearY(Single value) { }
	// RVA: 0x61d33a8 VA: 0x75987eb3a8
	public Single get_A() { }
	// RVA: 0x61d33b0 VA: 0x75987eb3b0
	public Single get_B() { }
	// RVA: 0x61d33b8 VA: 0x75987eb3b8
	public Single get_C() { }
	// RVA: 0x61d33c0 VA: 0x75987eb3c0
	public Single get_D() { }
	// RVA: 0x61d33c8 VA: 0x75987eb3c8
	public Single get_WorldX() { }
	// RVA: 0x61d33d0 VA: 0x75987eb3d0
	public Single get_WorldY() { }
	// RVA: 0x61d33d8 VA: 0x75987eb3d8
	public Single get_WorldRotationX() { }
	// RVA: 0x61d3450 VA: 0x75987eb450
	public Single get_WorldRotationY() { }
	// RVA: 0x61d34c8 VA: 0x75987eb4c8
	public Single get_WorldScaleX() { }
	// RVA: 0x61d3538 VA: 0x75987eb538
	public Single get_WorldScaleY() { }
	// RVA: 0x61d35a8 VA: 0x75987eb5a8
	public Void .ctor(BoneData data, Skeleton skeleton, Bone parent) { }
	// RVA: 0x61d3758 VA: 0x75987eb758
	public Void Update() { }
	// RVA: 0x61d3f74 VA: 0x75987ebf74
	public Void UpdateWorldTransform() { }
	// RVA: 0x61d376c VA: 0x75987eb76c
	public Void UpdateWorldTransform(Single x, Single y, Single rotation, Single scaleX, Single scaleY, Single shearX, Single shearY) { }
	// RVA: 0x61d3720 VA: 0x75987eb720
	public Void SetToSetupPose() { }
	// RVA: 0x61d40b4 VA: 0x75987ec0b4
	internal Void UpdateAppliedTransform() { }
	// RVA: 0x61d4394 VA: 0x75987ec394
	public Void WorldToLocal(Single worldX, Single worldY, out Single localX, out Single localY) { }
	// RVA: 0x61d23cc VA: 0x75987ea3cc
	public Void LocalToWorld(Single localX, Single localY, out Single worldX, out Single worldY) { }
	// RVA: 0x61d43f0 VA: 0x75987ec3f0
	public Single get_WorldToLocalRotationX() { }
	// RVA: 0x61d44a0 VA: 0x75987ec4a0
	public Single get_WorldToLocalRotationY() { }
	// RVA: 0x61d4550 VA: 0x75987ec550
	public Single WorldToLocalRotation(Single worldRotation) { }
	// RVA: 0x61d4600 VA: 0x75987ec600
	public Single LocalToWorldRotation(Single localRotation) { }
	// RVA: 0x61d46b0 VA: 0x75987ec6b0
	public Void RotateWorld(Single degrees) { }
	// RVA: 0x61d4760 VA: 0x75987ec760
	public override String ToString() { }
}
```