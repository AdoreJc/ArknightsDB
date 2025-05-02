# FinishSeveralBuffsById

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _decCntIfStack`

- `Boolean _updateOverrideMap`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FinishSeveralBuffsById : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String[] _buffKeys; // 0x18
	private Boolean _decCntIfStack; // 0x20
	private Boolean _updateOverrideMap; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ef7344 VA: 0x759450f344
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ef73ac VA: 0x759450f3ac
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ef753c VA: 0x759450f53c
	public Void .ctor() { }
}
```