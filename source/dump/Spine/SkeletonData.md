# SkeletonData

**Namespace:** `Spine`


## Properties

- `String Name`

- `Skin DefaultSkin`

- `Single X`

- `Single Y`

- `Single Width`

- `Single Height`

- `String Version`

- `String Hash`

- `String ImagesPath`

- `String AudioPath`

- `Single Fps`


## Methods

- `String get_Name()`

- `Void set_Name(String)`

- `Void set_Skins(ExposedList`1)`

- `Skin get_DefaultSkin()`

- `Void set_DefaultSkin(Skin)`

- `Void set_Events(ExposedList`1)`

- `Void set_Animations(ExposedList`1)`

- `Void set_IkConstraints(ExposedList`1)`

- `Void set_TransformConstraints(ExposedList`1)`

- `Void set_PathConstraints(ExposedList`1)`

- `Single get_X()`

- `Void set_X(Single)`

- `Single get_Y()`

- `Void set_Y(Single)`

- `Single get_Width()`

- `Void set_Width(Single)`

- `Single get_Height()`

- `Void set_Height(Single)`

- `String get_Version()`

- `Void set_Version(String)`

- `String get_Hash()`

- `Void set_Hash(String)`

- `String get_ImagesPath()`

- `Void set_ImagesPath(String)`

- `String get_AudioPath()`

- `Void set_AudioPath(String)`

- `Single get_Fps()`

- `Void set_Fps(Single)`

- `BoneData FindBone(String)`

- `Int32 FindBoneIndex(String)`

- `SlotData FindSlot(String)`

- `Int32 FindSlotIndex(String)`

- `Skin FindSkin(String)`

- `EventData FindEvent(String)`

- `Animation FindAnimation(String)`

- `IkConstraintData FindIkConstraint(String)`

- `TransformConstraintData FindTransformConstraint(String)`

- `PathConstraintData FindPathConstraint(String)`

- `Int32 FindPathConstraintIndex(String)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class SkeletonData
{
	internal String name; // 0x10
	internal ExposedList`1 bones; // 0x18
	internal ExposedList`1 slots; // 0x20
	internal ExposedList`1 skins; // 0x28
	internal Skin defaultSkin; // 0x30
	internal ExposedList`1 events; // 0x38
	internal ExposedList`1 animations; // 0x40
	internal ExposedList`1 ikConstraints; // 0x48
	internal ExposedList`1 transformConstraints; // 0x50
	internal ExposedList`1 pathConstraints; // 0x58
	internal Single x; // 0x60
	internal Single y; // 0x64
	internal Single width; // 0x68
	internal Single height; // 0x6c
	internal String version; // 0x70
	internal String hash; // 0x78
	internal Single fps; // 0x80
	internal String imagesPath; // 0x88
	internal String audioPath; // 0x90

	public String Name { get; set; }
	public ExposedList`1 Bones { get; }
	public ExposedList`1 Slots { get; }
	public ExposedList`1 Skins { get; set; }
	public Skin DefaultSkin { get; set; }
	public ExposedList`1 Events { get; set; }
	public ExposedList`1 Animations { get; set; }
	public ExposedList`1 IkConstraints { get; set; }
	public ExposedList`1 TransformConstraints { get; set; }
	public ExposedList`1 PathConstraints { get; set; }
	public Single X { get; set; }
	public Single Y { get; set; }
	public Single Width { get; set; }
	public Single Height { get; set; }
	public String Version { get; set; }
	public String Hash { get; set; }
	public String ImagesPath { get; set; }
	public String AudioPath { get; set; }
	public Single Fps { get; set; }

	// RVA: 0x61e5cf0 VA: 0x75987fdcf0
	public String get_Name() { }
	// RVA: 0x61e5cf8 VA: 0x75987fdcf8
	public Void set_Name(String value) { }
	// RVA: 0x61e5d00 VA: 0x75987fdd00
	public ExposedList`1 get_Bones() { }
	// RVA: 0x61e5d08 VA: 0x75987fdd08
	public ExposedList`1 get_Slots() { }
	// RVA: 0x61e5d10 VA: 0x75987fdd10
	public ExposedList`1 get_Skins() { }
	// RVA: 0x61e5d18 VA: 0x75987fdd18
	public Void set_Skins(ExposedList`1 value) { }
	// RVA: 0x61e5d20 VA: 0x75987fdd20
	public Skin get_DefaultSkin() { }
	// RVA: 0x61e5d28 VA: 0x75987fdd28
	public Void set_DefaultSkin(Skin value) { }
	// RVA: 0x61e5d30 VA: 0x75987fdd30
	public ExposedList`1 get_Events() { }
	// RVA: 0x61e5d38 VA: 0x75987fdd38
	public Void set_Events(ExposedList`1 value) { }
	// RVA: 0x61e5d40 VA: 0x75987fdd40
	public ExposedList`1 get_Animations() { }
	// RVA: 0x61e5d48 VA: 0x75987fdd48
	public Void set_Animations(ExposedList`1 value) { }
	// RVA: 0x61e5d50 VA: 0x75987fdd50
	public ExposedList`1 get_IkConstraints() { }
	// RVA: 0x61e5d58 VA: 0x75987fdd58
	public Void set_IkConstraints(ExposedList`1 value) { }
	// RVA: 0x61e5d60 VA: 0x75987fdd60
	public ExposedList`1 get_TransformConstraints() { }
	// RVA: 0x61e5d68 VA: 0x75987fdd68
	public Void set_TransformConstraints(ExposedList`1 value) { }
	// RVA: 0x61e5d70 VA: 0x75987fdd70
	public ExposedList`1 get_PathConstraints() { }
	// RVA: 0x61e5d78 VA: 0x75987fdd78
	public Void set_PathConstraints(ExposedList`1 value) { }
	// RVA: 0x61e5d80 VA: 0x75987fdd80
	public Single get_X() { }
	// RVA: 0x61e5d88 VA: 0x75987fdd88
	public Void set_X(Single value) { }
	// RVA: 0x61e5d90 VA: 0x75987fdd90
	public Single get_Y() { }
	// RVA: 0x61e5d98 VA: 0x75987fdd98
	public Void set_Y(Single value) { }
	// RVA: 0x61e5da0 VA: 0x75987fdda0
	public Single get_Width() { }
	// RVA: 0x61e5da8 VA: 0x75987fdda8
	public Void set_Width(Single value) { }
	// RVA: 0x61e5db0 VA: 0x75987fddb0
	public Single get_Height() { }
	// RVA: 0x61e5db8 VA: 0x75987fddb8
	public Void set_Height(Single value) { }
	// RVA: 0x61e5dc0 VA: 0x75987fddc0
	public String get_Version() { }
	// RVA: 0x61e5dc8 VA: 0x75987fddc8
	public Void set_Version(String value) { }
	// RVA: 0x61e5dd0 VA: 0x75987fddd0
	public String get_Hash() { }
	// RVA: 0x61e5dd8 VA: 0x75987fddd8
	public Void set_Hash(String value) { }
	// RVA: 0x61e5de0 VA: 0x75987fdde0
	public String get_ImagesPath() { }
	// RVA: 0x61e5de8 VA: 0x75987fdde8
	public Void set_ImagesPath(String value) { }
	// RVA: 0x61e5df0 VA: 0x75987fddf0
	public String get_AudioPath() { }
	// RVA: 0x61e5df8 VA: 0x75987fddf8
	public Void set_AudioPath(String value) { }
	// RVA: 0x61e5e00 VA: 0x75987fde00
	public Single get_Fps() { }
	// RVA: 0x61e5e08 VA: 0x75987fde08
	public Void set_Fps(Single value) { }
	// RVA: 0x61e5e10 VA: 0x75987fde10
	public BoneData FindBone(String boneName) { }
	// RVA: 0x61e5efc VA: 0x75987fdefc
	public Int32 FindBoneIndex(String boneName) { }
	// RVA: 0x61e5fe8 VA: 0x75987fdfe8
	public SlotData FindSlot(String slotName) { }
	// RVA: 0x61e60d4 VA: 0x75987fe0d4
	public Int32 FindSlotIndex(String slotName) { }
	// RVA: 0x61e61c0 VA: 0x75987fe1c0
	public Skin FindSkin(String skinName) { }
	// RVA: 0x61e63a8 VA: 0x75987fe3a8
	public EventData FindEvent(String eventDataName) { }
	// RVA: 0x61e6590 VA: 0x75987fe590
	public Animation FindAnimation(String animationName) { }
	// RVA: 0x61e667c VA: 0x75987fe67c
	public IkConstraintData FindIkConstraint(String constraintName) { }
	// RVA: 0x61e6768 VA: 0x75987fe768
	public TransformConstraintData FindTransformConstraint(String constraintName) { }
	// RVA: 0x61e6854 VA: 0x75987fe854
	public PathConstraintData FindPathConstraint(String constraintName) { }
	// RVA: 0x61e6944 VA: 0x75987fe944
	public Int32 FindPathConstraintIndex(String pathConstraintName) { }
	// RVA: 0x61e6a34 VA: 0x75987fea34
	public override String ToString() { }
	// RVA: 0x61e6a4c VA: 0x75987fea4c
	public Void .ctor() { }
}
```