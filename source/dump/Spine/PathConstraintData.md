# PathConstraintData

**Namespace:** `Spine`


## Properties

- `SlotData Target`

- `PositionMode PositionMode`

- `SpacingMode SpacingMode`

- `RotateMode RotateMode`

- `Single OffsetRotation`

- `Single Position`

- `Single Spacing`

- `Single RotateMix`

- `Single TranslateMix`


## Methods

- `SlotData get_Target()`

- `Void set_Target(SlotData)`

- `PositionMode get_PositionMode()`

- `Void set_PositionMode(PositionMode)`

- `SpacingMode get_SpacingMode()`

- `Void set_SpacingMode(SpacingMode)`

- `RotateMode get_RotateMode()`

- `Void set_RotateMode(RotateMode)`

- `Single get_OffsetRotation()`

- `Void set_OffsetRotation(Single)`

- `Single get_Position()`

- `Void set_Position(Single)`

- `Single get_Spacing()`

- `Void set_Spacing(Single)`

- `Single get_RotateMix()`

- `Void set_RotateMix(Single)`

- `Single get_TranslateMix()`

- `Void set_TranslateMix(Single)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class PathConstraintData : ConstraintData
{
	internal ExposedList`1 bones; // 0x20
	internal SlotData target; // 0x28
	internal PositionMode positionMode; // 0x30
	internal SpacingMode spacingMode; // 0x34
	internal RotateMode rotateMode; // 0x38
	internal Single offsetRotation; // 0x3c
	internal Single position; // 0x40
	internal Single spacing; // 0x44
	internal Single rotateMix; // 0x48
	internal Single translateMix; // 0x4c

	public ExposedList`1 Bones { get; }
	public SlotData Target { get; set; }
	public PositionMode PositionMode { get; set; }
	public SpacingMode SpacingMode { get; set; }
	public RotateMode RotateMode { get; set; }
	public Single OffsetRotation { get; set; }
	public Single Position { get; set; }
	public Single Spacing { get; set; }
	public Single RotateMix { get; set; }
	public Single TranslateMix { get; set; }

	// RVA: 0x61d91f8 VA: 0x75987f11f8
	public Void .ctor(String name) { }
	// RVA: 0x61d928c VA: 0x75987f128c
	public ExposedList`1 get_Bones() { }
	// RVA: 0x61d9294 VA: 0x75987f1294
	public SlotData get_Target() { }
	// RVA: 0x61d929c VA: 0x75987f129c
	public Void set_Target(SlotData value) { }
	// RVA: 0x61d92a4 VA: 0x75987f12a4
	public PositionMode get_PositionMode() { }
	// RVA: 0x61d92ac VA: 0x75987f12ac
	public Void set_PositionMode(PositionMode value) { }
	// RVA: 0x61d92b4 VA: 0x75987f12b4
	public SpacingMode get_SpacingMode() { }
	// RVA: 0x61d92bc VA: 0x75987f12bc
	public Void set_SpacingMode(SpacingMode value) { }
	// RVA: 0x61d92c4 VA: 0x75987f12c4
	public RotateMode get_RotateMode() { }
	// RVA: 0x61d92cc VA: 0x75987f12cc
	public Void set_RotateMode(RotateMode value) { }
	// RVA: 0x61d92d4 VA: 0x75987f12d4
	public Single get_OffsetRotation() { }
	// RVA: 0x61d92dc VA: 0x75987f12dc
	public Void set_OffsetRotation(Single value) { }
	// RVA: 0x61d92e4 VA: 0x75987f12e4
	public Single get_Position() { }
	// RVA: 0x61d92ec VA: 0x75987f12ec
	public Void set_Position(Single value) { }
	// RVA: 0x61d92f4 VA: 0x75987f12f4
	public Single get_Spacing() { }
	// RVA: 0x61d92fc VA: 0x75987f12fc
	public Void set_Spacing(Single value) { }
	// RVA: 0x61d9304 VA: 0x75987f1304
	public Single get_RotateMix() { }
	// RVA: 0x61d930c VA: 0x75987f130c
	public Void set_RotateMix(Single value) { }
	// RVA: 0x61d9314 VA: 0x75987f1314
	public Single get_TranslateMix() { }
	// RVA: 0x61d931c VA: 0x75987f131c
	public Void set_TranslateMix(Single value) { }
}
```