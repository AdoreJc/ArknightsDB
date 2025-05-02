# Act35SideSummonLinkGem

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act35SideSummonLinkGem : ActionNode
{
	private String _envSystemKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee09dc VA: 0x75944f89dc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee0a44 VA: 0x75944f8a44
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee0c6c VA: 0x75944f8c6c
	public Void .ctor() { }
}
```