# RecalculateDamage

**Namespace:** ` `


## Properties

- `ActionPurposeMask purposeMask`


## Methods

- `ActionPurposeMask get_purposeMask()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RecalculateDamage : ActionNode
{
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_get_purposeMask; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }
	public ActionPurposeMask purposeMask { get; }

	// RVA: 0x1f4cb9c VA: 0x7594564b9c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f4cc04 VA: 0x7594564c04
	public ActionPurposeMask get_purposeMask() { }
	// RVA: 0x1f4cc6c VA: 0x7594564c6c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f4cfc4 VA: 0x7594564fc4
	public Void .ctor() { }
}
```