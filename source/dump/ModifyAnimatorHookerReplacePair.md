# ModifyAnimatorHookerReplacePair

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _isOverwrite`

- `Boolean _modifyCurrentMode`

- `Int32 _modeIndex`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyAnimatorHookerReplacePair : ActionNode
{
	private ActionTargetType _target; // 0x10
	private ReplacePair[] _replaceAnimPairs; // 0x18
	private Boolean _isOverwrite; // 0x20
	private Boolean _modifyCurrentMode; // 0x21
	private Int32 _modeIndex; // 0x24
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f9a190 VA: 0x75945b2190
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f9a1f8 VA: 0x75945b21f8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f9a47c VA: 0x75945b247c
	public Void .ctor() { }
}
```