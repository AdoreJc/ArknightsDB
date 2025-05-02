# SetExternWithdrawGainCostFlag

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _value`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetExternWithdrawGainCostFlag : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _value; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd3b10 VA: 0x75945ebb10
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd3b78 VA: 0x75945ebb78
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd3cec VA: 0x75945ebcec
	public Void .ctor() { }
}
```