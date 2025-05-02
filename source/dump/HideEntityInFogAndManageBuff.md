# HideEntityInFogAndManageBuff

**Namespace:** ` `


## Fields

- `BuffData _buff`

- `BuffData _buffToTrap`

- `BuffData _buffToNPC`

- `String _filterTag`

- `String _hideTrapFilterTag`

- `String _npcFilterTag`

- `String _enemyNotShowBuff`


## Methods

- `Boolean HideUnit(Character, Boolean, ref, Blackboard)`

- `Boolean HideUnit(Enemy, Boolean, ref, Blackboard)`

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HideEntityInFogAndManageBuff : ActionNode, IBuffSource, ICreateBuffNode
{
	private BuffData _buff; // 0x10
	private BuffData _buffToTrap; // 0x18
	private BuffData _buffToNPC; // 0x20
	private String _filterTag; // 0x28
	private String _hideTrapFilterTag; // 0x30
	private String _npcFilterTag; // 0x38
	private String _enemyNotShowBuff; // 0x40
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_HideUnit; // 0x10
	private static DelegateBridge __Hotfix1_HideUnit; // 0x18
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override SourceType allowedSource { get; }

	// RVA: 0x1f82710 VA: 0x759459a710
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f82778 VA: 0x759459a778
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f82ba4 VA: 0x759459aba4
	private Boolean HideUnit(Character unit, Boolean hide, ref Snapshot snapshot, Blackboard blackboard) { }
	// RVA: 0x1f82f38 VA: 0x759459af38
	private Boolean HideUnit(Enemy unit, Boolean hide, ref Snapshot snapshot, Blackboard blackboard) { }
	// RVA: 0x1f83108 VA: 0x759459b108
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f83258 VA: 0x759459b258
	public Void .ctor() { }
}
```