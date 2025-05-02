# TransformConstraint

**Namespace:** `Spine`


## Properties

- `Bone Target`

- `Single RotateMix`

- `Single TranslateMix`

- `Single ScaleMix`

- `Single ShearMix`

- `Boolean Active`

- `TransformConstraintData Data`


## Methods

- `Void Apply()`

- `Void Update()`

- `Void ApplyAbsoluteWorld()`

- `Void ApplyRelativeWorld()`

- `Void ApplyAbsoluteLocal()`

- `Void ApplyRelativeLocal()`

- `Bone get_Target()`

- `Void set_Target(Bone)`

- `Single get_RotateMix()`

- `Void set_RotateMix(Single)`

- `Single get_TranslateMix()`

- `Void set_TranslateMix(Single)`

- `Single get_ScaleMix()`

- `Void set_ScaleMix(Single)`

- `Single get_ShearMix()`

- `Void set_ShearMix(Single)`

- `Boolean get_Active()`

- `TransformConstraintData get_Data()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class TransformConstraint : IUpdatable
{
	internal TransformConstraintData data; // 0x10
	internal ExposedList`1 bones; // 0x18
	internal Bone target; // 0x20
	internal Single rotateMix; // 0x28
	internal Single translateMix; // 0x2c
	internal Single scaleMix; // 0x30
	internal Single shearMix; // 0x34
	internal Boolean active; // 0x38

	public ExposedList`1 Bones { get; }
	public Bone Target { get; set; }
	public Single RotateMix { get; set; }
	public Single TranslateMix { get; set; }
	public Single ScaleMix { get; set; }
	public Single ShearMix { get; set; }
	public Boolean Active { get; }
	public TransformConstraintData Data { get; }

	// RVA: 0x61f421c VA: 0x759880c21c
	public Void .ctor(TransformConstraintData data, Skeleton skeleton) { }
	// RVA: 0x61f4504 VA: 0x759880c504
	public Void .ctor(TransformConstraint constraint, Skeleton skeleton) { }
	// RVA: 0x61f4830 VA: 0x759880c830
	public Void Apply() { }
	// RVA: 0x61f4834 VA: 0x759880c834
	public Void Update() { }
	// RVA: 0x61f50c0 VA: 0x759880d0c0
	private Void ApplyAbsoluteWorld() { }
	// RVA: 0x61f4c98 VA: 0x759880cc98
	private Void ApplyRelativeWorld() { }
	// RVA: 0x61f4a2c VA: 0x759880ca2c
	private Void ApplyAbsoluteLocal() { }
	// RVA: 0x61f4878 VA: 0x759880c878
	private Void ApplyRelativeLocal() { }
	// RVA: 0x61f55bc VA: 0x759880d5bc
	public ExposedList`1 get_Bones() { }
	// RVA: 0x61f55c4 VA: 0x759880d5c4
	public Bone get_Target() { }
	// RVA: 0x61f55cc VA: 0x759880d5cc
	public Void set_Target(Bone value) { }
	// RVA: 0x61f55d4 VA: 0x759880d5d4
	public Single get_RotateMix() { }
	// RVA: 0x61f55dc VA: 0x759880d5dc
	public Void set_RotateMix(Single value) { }
	// RVA: 0x61f55e4 VA: 0x759880d5e4
	public Single get_TranslateMix() { }
	// RVA: 0x61f55ec VA: 0x759880d5ec
	public Void set_TranslateMix(Single value) { }
	// RVA: 0x61f55f4 VA: 0x759880d5f4
	public Single get_ScaleMix() { }
	// RVA: 0x61f55fc VA: 0x759880d5fc
	public Void set_ScaleMix(Single value) { }
	// RVA: 0x61f5604 VA: 0x759880d604
	public Single get_ShearMix() { }
	// RVA: 0x61f560c VA: 0x759880d60c
	public Void set_ShearMix(Single value) { }
	// RVA: 0x61f5614 VA: 0x759880d614
	public Boolean get_Active() { }
	// RVA: 0x61f561c VA: 0x759880d61c
	public TransformConstraintData get_Data() { }
	// RVA: 0x61f5624 VA: 0x759880d624
	public override String ToString() { }
}
```