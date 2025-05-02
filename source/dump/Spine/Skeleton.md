# Skeleton

**Namespace:** `Spine`


## Fields

- `Single scaleX`

- `Single scaleY`


## Properties

- `SkeletonData Data`

- `Skin Skin`

- `Single R`

- `Single G`

- `Single B`

- `Single A`

- `Single Time`

- `Single X`

- `Single Y`

- `Single ScaleX`

- `Single ScaleY`

- `Boolean FlipX`

- `Boolean FlipY`

- `Bone RootBone`


## Methods

- `SkeletonData get_Data()`

- `Skin get_Skin()`

- `Void set_Skin(Skin)`

- `Single get_R()`

- `Void set_R(Single)`

- `Single get_G()`

- `Void set_G(Single)`

- `Single get_B()`

- `Void set_B(Single)`

- `Single get_A()`

- `Void set_A(Single)`

- `Single get_Time()`

- `Void set_Time(Single)`

- `Single get_X()`

- `Void set_X(Single)`

- `Single get_Y()`

- `Void set_Y(Single)`

- `Single get_ScaleX()`

- `Void set_ScaleX(Single)`

- `Single get_ScaleY()`

- `Void set_ScaleY(Single)`

- `Boolean get_FlipX()`

- `Void set_FlipX(Boolean)`

- `Boolean get_FlipY()`

- `Void set_FlipY(Boolean)`

- `Bone get_RootBone()`

- `Void UpdateCache()`

- `Void SortIkConstraint(IkConstraint)`

- `Void SortPathConstraint(PathConstraint)`

- `Void SortTransformConstraint(TransformConstraint)`

- `Void SortPathConstraintAttachment(Skin, Int32, Bone)`

- `Void SortPathConstraintAttachment(Attachment, Bone)`

- `Void SortBone(Bone)`

- `Void UpdateWorldTransform()`

- `Void UpdateWorldTransform(Bone)`

- `Void SetToSetupPose()`

- `Void SetBonesToSetupPose()`

- `Void SetSlotsToSetupPose()`

- `Bone FindBone(String)`

- `Int32 FindBoneIndex(String)`

- `Slot FindSlot(String)`

- `Int32 FindSlotIndex(String)`

- `Void SetSkin(String)`

- `Void SetSkin(Skin)`

- `Attachment GetAttachment(String, String)`

- `Attachment GetAttachment(Int32, String)`

- `Void SetAttachment(String, String)`

- `IkConstraint FindIkConstraint(String)`

- `TransformConstraint FindTransformConstraint(String)`

- `PathConstraint FindPathConstraint(String)`

- `Void Update(Single)`

- `Void GetBounds(out, out, out, out, ref)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class Skeleton
{
	internal SkeletonData data; // 0x10
	internal ExposedList`1 bones; // 0x18
	internal ExposedList`1 slots; // 0x20
	internal ExposedList`1 drawOrder; // 0x28
	internal ExposedList`1 ikConstraints; // 0x30
	internal ExposedList`1 transformConstraints; // 0x38
	internal ExposedList`1 pathConstraints; // 0x40
	internal ExposedList`1 updateCache; // 0x48
	internal ExposedList`1 updateCacheReset; // 0x50
	internal Skin skin; // 0x58
	internal Single r; // 0x60
	internal Single g; // 0x64
	internal Single b; // 0x68
	internal Single a; // 0x6c
	internal Single time; // 0x70
	private Single scaleX; // 0x74
	private Single scaleY; // 0x78
	internal Single x; // 0x7c
	internal Single y; // 0x80

	public SkeletonData Data { get; }
	public ExposedList`1 Bones { get; }
	public ExposedList`1 UpdateCacheList { get; }
	public ExposedList`1 Slots { get; }
	public ExposedList`1 DrawOrder { get; }
	public ExposedList`1 IkConstraints { get; }
	public ExposedList`1 PathConstraints { get; }
	public ExposedList`1 TransformConstraints { get; }
	public Skin Skin { get; set; }
	public Single R { get; set; }
	public Single G { get; set; }
	public Single B { get; set; }
	public Single A { get; set; }
	public Single Time { get; set; }
	public Single X { get; set; }
	public Single Y { get; set; }
	public Single ScaleX { get; set; }
	public Single ScaleY { get; set; }
	public Boolean FlipX { get; set; }
	public Boolean FlipY { get; set; }
	public Bone RootBone { get; }

	// RVA: 0x61d9324 VA: 0x75987f1324
	public SkeletonData get_Data() { }
	// RVA: 0x61d932c VA: 0x75987f132c
	public ExposedList`1 get_Bones() { }
	// RVA: 0x61d9334 VA: 0x75987f1334
	public ExposedList`1 get_UpdateCacheList() { }
	// RVA: 0x61d933c VA: 0x75987f133c
	public ExposedList`1 get_Slots() { }
	// RVA: 0x61d9344 VA: 0x75987f1344
	public ExposedList`1 get_DrawOrder() { }
	// RVA: 0x61d934c VA: 0x75987f134c
	public ExposedList`1 get_IkConstraints() { }
	// RVA: 0x61d9354 VA: 0x75987f1354
	public ExposedList`1 get_PathConstraints() { }
	// RVA: 0x61d935c VA: 0x75987f135c
	public ExposedList`1 get_TransformConstraints() { }
	// RVA: 0x61d9364 VA: 0x75987f1364
	public Skin get_Skin() { }
	// RVA: 0x61d936c VA: 0x75987f136c
	public Void set_Skin(Skin value) { }
	// RVA: 0x61d9470 VA: 0x75987f1470
	public Single get_R() { }
	// RVA: 0x61d9478 VA: 0x75987f1478
	public Void set_R(Single value) { }
	// RVA: 0x61d9480 VA: 0x75987f1480
	public Single get_G() { }
	// RVA: 0x61d9488 VA: 0x75987f1488
	public Void set_G(Single value) { }
	// RVA: 0x61d9490 VA: 0x75987f1490
	public Single get_B() { }
	// RVA: 0x61d9498 VA: 0x75987f1498
	public Void set_B(Single value) { }
	// RVA: 0x61d94a0 VA: 0x75987f14a0
	public Single get_A() { }
	// RVA: 0x61d94a8 VA: 0x75987f14a8
	public Void set_A(Single value) { }
	// RVA: 0x61d94b0 VA: 0x75987f14b0
	public Single get_Time() { }
	// RVA: 0x61d94b8 VA: 0x75987f14b8
	public Void set_Time(Single value) { }
	// RVA: 0x61d94c0 VA: 0x75987f14c0
	public Single get_X() { }
	// RVA: 0x61d94c8 VA: 0x75987f14c8
	public Void set_X(Single value) { }
	// RVA: 0x61d94d0 VA: 0x75987f14d0
	public Single get_Y() { }
	// RVA: 0x61d94d8 VA: 0x75987f14d8
	public Void set_Y(Single value) { }
	// RVA: 0x61d94e0 VA: 0x75987f14e0
	public Single get_ScaleX() { }
	// RVA: 0x61d94e8 VA: 0x75987f14e8
	public Void set_ScaleX(Single value) { }
	// RVA: 0x61d3f88 VA: 0x75987ebf88
	public Single get_ScaleY() { }
	// RVA: 0x61d94f0 VA: 0x75987f14f0
	public Void set_ScaleY(Single value) { }
	// RVA: 0x61d94f8 VA: 0x75987f14f8
	public Boolean get_FlipX() { }
	// RVA: 0x61d9508 VA: 0x75987f1508
	public Void set_FlipX(Boolean value) { }
	// RVA: 0x61d9530 VA: 0x75987f1530
	public Boolean get_FlipY() { }
	// RVA: 0x61d9540 VA: 0x75987f1540
	public Void set_FlipY(Boolean value) { }
	// RVA: 0x61d9568 VA: 0x75987f1568
	public Bone get_RootBone() { }
	// RVA: 0x61d95a8 VA: 0x75987f15a8
	public Void .ctor(SkeletonData data) { }
	// RVA: 0x61da22c VA: 0x75987f222c
	public Void UpdateCache() { }
	// RVA: 0x61da6b4 VA: 0x75987f26b4
	private Void SortIkConstraint(IkConstraint constraint) { }
	// RVA: 0x61daae0 VA: 0x75987f2ae0
	private Void SortPathConstraint(PathConstraint constraint) { }
	// RVA: 0x61da87c VA: 0x75987f287c
	private Void SortTransformConstraint(TransformConstraint constraint) { }
	// RVA: 0x61dae40 VA: 0x75987f2e40
	private Void SortPathConstraintAttachment(Skin skin, Int32 slotIndex, Bone slotBone) { }
	// RVA: 0x61db118 VA: 0x75987f3118
	private Void SortPathConstraintAttachment(Attachment attachment, Bone slotBone) { }
	// RVA: 0x61dad38 VA: 0x75987f2d38
	private Void SortBone(Bone bone) { }
	// RVA: 0x61dadc0 VA: 0x75987f2dc0
	private static Void SortReset(ExposedList`1 bones) { }
	// RVA: 0x61da564 VA: 0x75987f2564
	public Void UpdateWorldTransform() { }
	// RVA: 0x61db274 VA: 0x75987f3274
	public Void UpdateWorldTransform(Bone parent) { }
	// RVA: 0x61db518 VA: 0x75987f3518
	public Void SetToSetupPose() { }
	// RVA: 0x61db530 VA: 0x75987f3530
	public Void SetBonesToSetupPose() { }
	// RVA: 0x61db6b4 VA: 0x75987f36b4
	public Void SetSlotsToSetupPose() { }
	// RVA: 0x61d4f88 VA: 0x75987ecf88
	public Bone FindBone(String boneName) { }
	// RVA: 0x61db7c0 VA: 0x75987f37c0
	public Int32 FindBoneIndex(String boneName) { }
	// RVA: 0x61d71f4 VA: 0x75987ef1f4
	public Slot FindSlot(String slotName) { }
	// RVA: 0x61db8b4 VA: 0x75987f38b4
	public Int32 FindSlotIndex(String slotName) { }
	// RVA: 0x61db9ac VA: 0x75987f39ac
	public Void SetSkin(String skinName) { }
	// RVA: 0x61d9370 VA: 0x75987f1370
	public Void SetSkin(Skin newSkin) { }
	// RVA: 0x61dba54 VA: 0x75987f3a54
	public Attachment GetAttachment(String slotName, String attachmentName) { }
	// RVA: 0x61dba90 VA: 0x75987f3a90
	public Attachment GetAttachment(Int32 slotIndex, String attachmentName) { }
	// RVA: 0x61dbb5c VA: 0x75987f3b5c
	public Void SetAttachment(String slotName, String attachmentName) { }
	// RVA: 0x61dbd14 VA: 0x75987f3d14
	public IkConstraint FindIkConstraint(String constraintName) { }
	// RVA: 0x61dbe08 VA: 0x75987f3e08
	public TransformConstraint FindTransformConstraint(String constraintName) { }
	// RVA: 0x61dbefc VA: 0x75987f3efc
	public PathConstraint FindPathConstraint(String constraintName) { }
	// RVA: 0x61dbff4 VA: 0x75987f3ff4
	public Void Update(Single delta) { }
	// RVA: 0x61dc004 VA: 0x75987f4004
	public Void GetBounds(out Single x, out Single y, out Single width, out Single height, ref Single[] vertexBuffer) { }
}
```