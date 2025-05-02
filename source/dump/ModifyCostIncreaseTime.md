# ModifyCostIncreaseTime

**Namespace:** ` `


## Fields

- `Boolean _isMulOtherwiseDiv`

- `ActionTargetType _sourceType`

- `String _blackboardKey`

- `Single _deltaCostIncreaseTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyCostIncreaseTime : ActionNode
{
	private Boolean _isMulOtherwiseDiv; // 0x10
	private ActionTargetType _sourceType; // 0x14
	private String _blackboardKey; // 0x18
	private Single _deltaCostIncreaseTime; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0bb78 VA: 0x7594523b78
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0bbe0 VA: 0x7594523be0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0bd7c VA: 0x7594523d7c
	public Void .ctor() { }
}
```