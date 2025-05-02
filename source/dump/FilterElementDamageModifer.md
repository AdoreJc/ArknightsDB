# FilterElementDamageModifer

**Namespace:** ` `


## Fields

- `Boolean _filterEPType`

- `ElementType _epType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterElementDamageModifer : ActionNode
{
	private Boolean _filterEPType; // 0x10
	private ElementType _epType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f31968 VA: 0x7594549968
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f319d0 VA: 0x75945499d0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f31adc VA: 0x7594549adc
	public Void .ctor() { }
}
```