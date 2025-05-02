# CheckTileCntInAttackRange

**Namespace:** ` `


## Fields

- `CompareType _condType`

- `Boolean _ignoreContainsCharacter`

- `ActionTargetType m_sourceType`


## Methods

- `Boolean _ContainsKey(Tile, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckTileCntInAttackRange : ActionNode
{
	private CompareType _condType; // 0x10
	private Boolean _ignoreContainsCharacter; // 0x14
	private ActionTargetType m_sourceType; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__ContainsKey; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f26480 VA: 0x759453e480
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f264e8 VA: 0x759453e4e8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f26860 VA: 0x759453e860
	private Boolean _ContainsKey(Tile tile, String key) { }
	// RVA: 0x1f26940 VA: 0x759453e940
	public Void .ctor() { }
}
```