# FinishBuffsOfEveryCharacterById

**Namespace:** ` `


## Fields

- `String _buffKey`

- `Boolean _loadFromBlackboard`

- `Boolean _decCntIfStack`

- `Boolean _updateOverrideMap`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishBuffsOfEveryCharacterById : ActionNode
{
	private String _buffKey; // 0x10
	private Boolean _loadFromBlackboard; // 0x18
	private Boolean _decCntIfStack; // 0x19
	private Boolean _updateOverrideMap; // 0x1a
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f9b6b8 VA: 0x75945b36b8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f9b720 VA: 0x75945b3720
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f9ba88 VA: 0x75945b3a88
	public Void .ctor() { }
}
```