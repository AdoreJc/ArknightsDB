# AutochessCreateBuffToCharacterFilterByAttribute

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `BuffData _buff`

- `Boolean _isDerivedBuff`

- `AttributeType _attributeType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutochessCreateBuffToCharacterFilterByAttribute : ActionNode, ICreateBuffNode
{
	private ActionTargetType _ownerType; // 0x10
	private BuffData _buff; // 0x18
	private Boolean _isDerivedBuff; // 0x20
	private AttributeType _attributeType; // 0x24
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee54cc VA: 0x75944fd4cc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee5534 VA: 0x75944fd534
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee5a10 VA: 0x75944fda10
	public Void .ctor() { }
}
```