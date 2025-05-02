# Act35SideSummonGems

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `ActionTargetType _targetType`

- `GemsType _gemsType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act35SideSummonGems : ActionNode
{
	private String _envSystemKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private GemsType _gemsType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee011c VA: 0x75944f811c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee0184 VA: 0x75944f8184
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee0350 VA: 0x75944f8350
	public Void .ctor() { }
}
```