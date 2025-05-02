# RemoveTileBindingGlobalBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _abilitySource`

- `ActionTargetType _selectorTarget`

- `String _abilityName`

- `String _globalBuffPrefabKey`

- `String _globalBuffKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RemoveTileBindingGlobalBuff : ActionNode
{
	private ActionTargetType _abilitySource; // 0x10
	private ActionTargetType _selectorTarget; // 0x14
	private String _abilityName; // 0x18
	private String _globalBuffPrefabKey; // 0x20
	private String _globalBuffKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7dce8 VA: 0x7594595ce8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7dd50 VA: 0x7594595d50
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7e160 VA: 0x7594596160
	public Void .ctor() { }
}
```