# AutoChessCheckCharacterKeyHappendOnlyOnce

**Namespace:** ` `


## Fields

- `String _key`

- `ActionTargetType _ownerType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessCheckCharacterKeyHappendOnlyOnce : ActionNode
{
	private String _key; // 0x10
	private ActionTargetType _ownerType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee5230 VA: 0x75944fd230
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee5298 VA: 0x75944fd298
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee5454 VA: 0x75944fd454
	public Void .ctor() { }
}
```