# AssignAttributeDefaultValueToBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Single _maxHpValue`

- `Single _atkValue`

- `Single _defValue`

- `Single _attackSpeedValue`

- `Single _magicResistanceValue`

- `Int32 _blockCnt`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignAttributeDefaultValueToBlackboard : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Single _maxHpValue; // 0x14
	private Single _atkValue; // 0x18
	private Single _defValue; // 0x1c
	private Single _attackSpeedValue; // 0x20
	private Single _magicResistanceValue; // 0x24
	private Int32 _blockCnt; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd9c84 VA: 0x75945f1c84
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd9cec VA: 0x75945f1cec
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd9fd4 VA: 0x75945f1fd4
	public Void .ctor() { }
}
```