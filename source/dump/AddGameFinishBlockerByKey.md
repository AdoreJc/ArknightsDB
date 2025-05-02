# AddGameFinishBlockerByKey

**Namespace:** ` `


## Fields

- `String _blockerKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddGameFinishBlockerByKey : ActionNode
{
	private String _blockerKey; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd4e9c VA: 0x75945ece9c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd4f04 VA: 0x75945ecf04
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd4fd0 VA: 0x75945ecfd0
	public Void .ctor() { }
}
```