# FilterCharacterSubPrefession

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterCharacterSubPrefession : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String[] _keys; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f610fc VA: 0x75945790fc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f61164 VA: 0x7594579164
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f61338 VA: 0x7594579338
	public Void .ctor() { }
}
```