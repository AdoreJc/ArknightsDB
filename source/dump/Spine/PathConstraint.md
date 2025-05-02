# PathConstraint

**Namespace:** `Spine`


## Properties

- `Single Position`

- `Single Spacing`

- `Single RotateMix`

- `Single TranslateMix`

- `Slot Target`

- `Boolean Active`

- `PathConstraintData Data`


## Methods

- `Void Apply()`

- `Void Update()`

- `Single get_Position()`

- `Void set_Position(Single)`

- `Single get_Spacing()`

- `Void set_Spacing(Single)`

- `Single get_RotateMix()`

- `Void set_RotateMix(Single)`

- `Single get_TranslateMix()`

- `Void set_TranslateMix(Single)`

- `Slot get_Target()`

- `Void set_Target(Slot)`

- `Boolean get_Active()`

- `PathConstraintData get_Data()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class PathConstraint : IUpdatable
{
	private const Int32 NONE; // 0x0
	private const Int32 BEFORE; // 0x0
	private const Int32 AFTER; // 0x0
	private const Single Epsilon; // 0x0
	internal PathConstraintData data; // 0x10
	internal ExposedList`1 bones; // 0x18
	internal Slot target; // 0x20
	internal Single position; // 0x28
	internal Single spacing; // 0x2c
	internal Single rotateMix; // 0x30
	internal Single translateMix; // 0x34
	internal Boolean active; // 0x38
	internal ExposedList`1 spaces; // 0x40
	internal ExposedList`1 positions; // 0x48
	internal ExposedList`1 world; // 0x50
	internal ExposedList`1 curves; // 0x58
	internal ExposedList`1 lengths; // 0x60
	internal Single[] segments; // 0x68

	public Single Position { get; set; }
	public Single Spacing { get; set; }
	public Single RotateMix { get; set; }
	public Single TranslateMix { get; set; }
	public ExposedList`1 Bones { get; }
	public Slot Target { get; set; }
	public Boolean Active { get; }
	public PathConstraintData Data { get; }

	// RVA: 0x61d6de8 VA: 0x75987eede8
	public Void .ctor(PathConstraintData data, Skeleton skeleton) { }
	// RVA: 0x61d72e8 VA: 0x75987ef2e8
	public Void .ctor(PathConstraint constraint, Skeleton skeleton) { }
	// RVA: 0x61d7734 VA: 0x75987ef734
	public Void Apply() { }
	// RVA: 0x61d7738 VA: 0x75987ef738
	public Void Update() { }
	// RVA: 0x61d7ee0 VA: 0x75987efee0
	private Single[] ComputeWorldPositions(PathAttachment path, Int32 spacesCount, Boolean tangents, Boolean percentPosition, Boolean percentSpacing) { }
	// RVA: 0x61d8c64 VA: 0x75987f0c64
	private static Void AddBeforePosition(Single p, Single[] temp, Int32 i, Single[] output, Int32 o) { }
	// RVA: 0x61d8db4 VA: 0x75987f0db4
	private static Void AddAfterPosition(Single p, Single[] temp, Int32 i, Single[] output, Int32 o) { }
	// RVA: 0x61d8f04 VA: 0x75987f0f04
	private static Void AddCurvePosition(Single p, Single x1, Single y1, Single cx1, Single cy1, Single cx2, Single cy2, Single x2, Single y2, Single[] output, Int32 o, Boolean tangents) { }
	// RVA: 0x61d9190 VA: 0x75987f1190
	public Single get_Position() { }
	// RVA: 0x61d9198 VA: 0x75987f1198
	public Void set_Position(Single value) { }
	// RVA: 0x61d91a0 VA: 0x75987f11a0
	public Single get_Spacing() { }
	// RVA: 0x61d91a8 VA: 0x75987f11a8
	public Void set_Spacing(Single value) { }
	// RVA: 0x61d91b0 VA: 0x75987f11b0
	public Single get_RotateMix() { }
	// RVA: 0x61d91b8 VA: 0x75987f11b8
	public Void set_RotateMix(Single value) { }
	// RVA: 0x61d91c0 VA: 0x75987f11c0
	public Single get_TranslateMix() { }
	// RVA: 0x61d91c8 VA: 0x75987f11c8
	public Void set_TranslateMix(Single value) { }
	// RVA: 0x61d91d0 VA: 0x75987f11d0
	public ExposedList`1 get_Bones() { }
	// RVA: 0x61d91d8 VA: 0x75987f11d8
	public Slot get_Target() { }
	// RVA: 0x61d91e0 VA: 0x75987f11e0
	public Void set_Target(Slot value) { }
	// RVA: 0x61d91e8 VA: 0x75987f11e8
	public Boolean get_Active() { }
	// RVA: 0x61d91f0 VA: 0x75987f11f0
	public PathConstraintData get_Data() { }
}
```