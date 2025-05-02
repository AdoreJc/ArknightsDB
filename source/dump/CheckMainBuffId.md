# CheckMainBuffId

**Namespace:** ` `


## Fields

- `String _idToFilter`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckMainBuffId : ActionNode
{
	private String _idToFilter; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1ce38 VA: 0x7594534e38
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1cea0 VA: 0x7594534ea0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1cf60 VA: 0x7594534f60
	public Void .ctor() { }
}
```