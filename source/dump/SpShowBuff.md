# SpShowBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _spShowBuffKey`

- `Boolean _isSelf`

- `Boolean _isSkillCountDown`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SpShowBuff : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _spShowBuffKey; // 0x18
	private Boolean _isSelf; // 0x20
	private Boolean _isSkillCountDown; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f01b1c VA: 0x7594519b1c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f01b84 VA: 0x7594519b84
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f01d54 VA: 0x7594519d54
	public Void .ctor() { }
}
```