# ModifyAbilityBlackboardAndCast

**Namespace:** ` `


## Fields

- `Boolean _scaledByBuffGroupStackCount`

- `String _blackboardKeys`

- `String _ability`

- `Boolean _logStackCountToDynamicVar`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyAbilityBlackboardAndCast : ActionNode
{
	private Boolean _scaledByBuffGroupStackCount; // 0x10
	private String _blackboardKeys; // 0x18
	private String _ability; // 0x20
	private Boolean _logStackCountToDynamicVar; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f97844 VA: 0x75945af844
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f978ac VA: 0x75945af8ac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f97bcc VA: 0x75945afbcc
	public Void .ctor() { }
}
```