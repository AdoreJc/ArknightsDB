# ClearOverlappedCharacterIfExist

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ClearOverlappedCharacterIfExist : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd0d3c VA: 0x75945e8d3c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd0da4 VA: 0x75945e8da4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd0fb0 VA: 0x75945e8fb0
	public Void .ctor() { }
}
```