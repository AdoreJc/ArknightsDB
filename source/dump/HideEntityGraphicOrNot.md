# HideEntityGraphicOrNot

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `Boolean _hide`


## Methods

- `Void _HideCharacter(Character, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HideEntityGraphicOrNot : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private Boolean _hide; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__HideCharacter; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd5aa4 VA: 0x75945edaa4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd5b0c VA: 0x75945edb0c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd5ca4 VA: 0x75945edca4
	private Void _HideCharacter(Character unit, Boolean hide) { }
	// RVA: 0x1fd5e6c VA: 0x75945ede6c
	public Void .ctor() { }
}
```