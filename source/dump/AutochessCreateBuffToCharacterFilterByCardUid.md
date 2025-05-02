# AutochessCreateBuffToCharacterFilterByCardUid

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `BuffData _buff`

- `Boolean _isDerivedBuff`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutochessCreateBuffToCharacterFilterByCardUid : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private BuffData _buff; // 0x18
	private Boolean _isDerivedBuff; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee616c VA: 0x75944fe16c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee61d4 VA: 0x75944fe1d4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee6474 VA: 0x75944fe474
	public Void .ctor() { }
}
```