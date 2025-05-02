# HideCharacterOrTokenNotInAbilityBlackboard

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `String _abilityName`

- `InfoType _infoType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HideCharacterOrTokenNotInAbilityBlackboard : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private String _abilityName; // 0x18
	private InfoType _infoType; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd6140 VA: 0x75945ee140
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd61a8 VA: 0x75945ee1a8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd66ec VA: 0x75945ee6ec
	public Void .ctor() { }
}
```