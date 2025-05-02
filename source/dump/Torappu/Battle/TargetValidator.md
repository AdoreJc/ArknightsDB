# TargetValidator

**Namespace:** `Torappu.Battle`


## Fields

- `TargetOptions _targetOptions`

- `Boolean m_ignoreTargetSide`

- `Boolean m_inited`


## Properties

- `Entity owner`


## Methods

- `Entity get_owner()`

- `Int32 GetLayerMask()`

- `Boolean VerifyOnlyMotionAndCategory(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TargetValidator : MonoBehaviour
{
	private TargetOptions _targetOptions; // 0x18
	private ObjectPtr`1 m_owner; // 0x78
	private Boolean m_ignoreTargetSide; // 0x88
	private Boolean m_inited; // 0x89

	protected Entity owner { get; }

	// RVA: 0x1bda654 VA: 0x75941f2654
	protected Entity get_owner() { }
	// RVA: 0x1bda880 VA: 0x75941f2880
	public virtual Void SetData(Entity owner, Blackboard blackboard, Boolean ignoreTargetSide) { }
	// RVA: 0x1bda2c8 VA: 0x75941f22c8
	public virtual Boolean Validate(Entity target) { }
	// RVA: 0x1bdc0fc VA: 0x75941f40fc
	public Int32 GetLayerMask() { }
	// RVA: 0x1bdc108 VA: 0x75941f4108
	public Boolean VerifyOnlyMotionAndCategory(Entity target) { }
	// RVA: 0x1bdc120 VA: 0x75941f4120
	public virtual Void OnTick(FP deltaTime) { }
	// RVA: 0x1bda434 VA: 0x75941f2434
	public Void .ctor() { }
}
```