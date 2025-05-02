# AssignTokenCntToBB

**Namespace:** ` `


## Fields

- `ActionTargetType _actionTargetType`

- `String _blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AssignTokenCntToBB : ActionNode
{
	private ActionTargetType _actionTargetType; // 0x10
	private String _blackboardKey; // 0x18
	private List`1 m_tokens; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd9964 VA: 0x75945f1964
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd99cc VA: 0x75945f19cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd9bc0 VA: 0x75945f1bc0
	public Void .ctor() { }
}
```