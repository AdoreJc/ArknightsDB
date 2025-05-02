# CheckHostContainsBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean isAND`

- `Boolean m_result`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckHostContainsBuff : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String[] _buffKeys; // 0x18
	private Boolean isAND; // 0x20
	private Boolean m_result; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1d7bc VA: 0x75945357bc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1d824 VA: 0x7594535824
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1daec VA: 0x7594535aec
	public Void .ctor() { }
}
```