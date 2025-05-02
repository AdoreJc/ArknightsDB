# CreateBuffToToken

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Boolean _excludeTarget`

- `ActionTargetType _targetType`

- `BuffData _buffData`

- `Boolean _isDerivedBuff`

- `Boolean _onlyToFirstTarget`

- `Boolean _excludeByBuffKey`

- `String _excludeBuffKey`

- `Boolean _finishDerivedBuffIfParentFinish`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffToToken : ActionNode, IBuffSource
{
	private ActionTargetType _sourceType; // 0x10
	private Boolean _excludeTarget; // 0x14
	private ActionTargetType _targetType; // 0x18
	private BuffData _buffData; // 0x20
	private Boolean _isDerivedBuff; // 0x28
	private Boolean _onlyToFirstTarget; // 0x29
	private Boolean _excludeByBuffKey; // 0x2a
	private String _excludeBuffKey; // 0x30
	private Boolean _finishDerivedBuffIfParentFinish; // 0x38
	private List`1 m_tokens; // 0x40
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1efc994 VA: 0x7594514994
	public override SourceType get_allowedSource() { }
	// RVA: 0x1efc9fc VA: 0x75945149fc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1efcdf0 VA: 0x7594514df0
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1efcef8 VA: 0x7594514ef8
	public Void .ctor() { }
}
```