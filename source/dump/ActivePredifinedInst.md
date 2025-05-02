# ActivePredifinedInst

**Namespace:** ` `


## Fields

- `String _instAlias`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ActivePredifinedInst : ActionNode
{
	private String _instAlias; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd4c80 VA: 0x75945ecc80
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd4ce8 VA: 0x75945ecce8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd4e2c VA: 0x75945ece2c
	public Void .ctor() { }
}
```