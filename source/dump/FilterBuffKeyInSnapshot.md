# FilterBuffKeyInSnapshot

**Namespace:** ` `


## Fields

- `String _key`

- `Boolean _mainBuff`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterBuffKeyInSnapshot : ActionNode
{
	private String _key; // 0x10
	private Boolean _mainBuff; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f61620 VA: 0x7594579620
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f61688 VA: 0x7594579688
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f61764 VA: 0x7594579764
	public Void .ctor() { }
}
```