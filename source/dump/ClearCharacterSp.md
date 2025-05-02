# ClearCharacterSp

**Namespace:** ` `


## Fields

- `Boolean _forceFlag`

- `ActionTargetType _charFrom`


## Methods

- `Boolean _ReduceSpToZero(Character)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ClearCharacterSp : ActionNode
{
	private Boolean _forceFlag; // 0x10
	private ActionTargetType _charFrom; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__ReduceSpToZero; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1fc3c50 VA: 0x75945dbc50
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fc3cb8 VA: 0x75945dbcb8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fc3e40 VA: 0x75945dbe40
	private Boolean _ReduceSpToZero(Character character) { }
	// RVA: 0x1fc3f84 VA: 0x75945dbf84
	public Void .ctor() { }
}
```