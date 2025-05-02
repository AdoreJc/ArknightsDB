# Act35SideSummonGemsInFourDirections

**Namespace:** ` `


## Fields

- `String _envSystemKey`

- `ActionTargetType _targetType`

- `GemsType _gemsType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act35SideSummonGemsInFourDirections : ActionNode
{
	private String _envSystemKey; // 0x10
	private ActionTargetType _targetType; // 0x18
	private GemsType _gemsType; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edf438 VA: 0x75944f7438
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edf4a0 VA: 0x75944f74a0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edf6a0 VA: 0x75944f76a0
	public Void .ctor() { }
}
```