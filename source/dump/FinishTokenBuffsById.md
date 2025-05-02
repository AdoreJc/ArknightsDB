# FinishTokenBuffsById

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _buffKey`

- `Boolean _loadFromBlackboard`

- `Boolean _decCntIfStack`

- `Boolean _updateOverrideMap`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishTokenBuffsById : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _buffKey; // 0x18
	private Boolean _loadFromBlackboard; // 0x20
	private Boolean _decCntIfStack; // 0x21
	private Boolean _updateOverrideMap; // 0x22
	private List`1 m_tokens; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f03650 VA: 0x759451b650
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f036b8 VA: 0x759451b6b8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f03988 VA: 0x759451b988
	public Void .ctor() { }
}
```