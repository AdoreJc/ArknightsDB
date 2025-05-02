# AutochessAddBuffToCharactersWithSameId

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `BuffData _buff`

- `Boolean _isDerivedBuff`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutochessAddBuffToCharactersWithSameId : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private BuffData _buff; // 0x18
	private Boolean _isDerivedBuff; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee47ac VA: 0x75944fc7ac
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee4814 VA: 0x75944fc814
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee4b60 VA: 0x75944fcb60
	public Void .ctor() { }
}
```