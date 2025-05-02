# RistarRecordDirection

**Namespace:** ` `


## Fields

- `ActionTargetType _source`

- `Boolean _isAura`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RistarRecordDirection : ActionNode
{
	private ActionTargetType _source; // 0x10
	private Boolean _isAura; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f597d4 VA: 0x75945717d4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f5983c VA: 0x759457183c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f59c3c VA: 0x7594571c3c
	public Void .ctor() { }
}
```