# SwitchSide

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `SideType _sideType`

- `Boolean _alwaysShowEnemyHp`

- `Boolean _markEnemyKilled`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchSide : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private SideType _sideType; // 0x14
	private Boolean _alwaysShowEnemyHp; // 0x18
	private Boolean _markEnemyKilled; // 0x19
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc9788 VA: 0x75945e1788
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc97f0 VA: 0x75945e17f0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc9a28 VA: 0x75945e1a28
	public Void .ctor() { }
}
```