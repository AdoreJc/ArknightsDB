# RecordDamageModifier

**Namespace:** ` `


## Fields

- `Boolean _filterModifierCancelled`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RecordDamageModifier : ActionNode
{
	private Boolean _filterModifierCancelled; // 0x10
	private static StringBuilder m_keyBuilder; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f73fe8 VA: 0x759458bfe8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f74050 VA: 0x759458c050
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7431c VA: 0x759458c31c
	public Void .ctor() { }
}
```