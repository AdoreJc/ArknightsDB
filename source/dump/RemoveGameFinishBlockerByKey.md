# RemoveGameFinishBlockerByKey

**Namespace:** ` `


## Fields

- `String _blockerKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RemoveGameFinishBlockerByKey : ActionNode
{
	private String _blockerKey; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd531c VA: 0x75945ed31c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd5384 VA: 0x75945ed384
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd5450 VA: 0x75945ed450
	public Void .ctor() { }
}
```