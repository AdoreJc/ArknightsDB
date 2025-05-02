# ModifyCharacterSpineColor

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `SpineColor _color`

- `Boolean _lockColor`


## Methods

- `Boolean _SetColor(Character, SpineColor, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ModifyCharacterSpineColor : ActionNode
{
	private ActionTargetType _target; // 0x10
	private SpineColor _color; // 0x14
	private Boolean _lockColor; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0__SetColor; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f12aec VA: 0x759452aaec
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f12b54 VA: 0x759452ab54
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f12c78 VA: 0x759452ac78
	private Boolean _SetColor(Character character, SpineColor color, Boolean lockAnimatorColor) { }
	// RVA: 0x1f12e9c VA: 0x759452ae9c
	public Void .ctor() { }
}
```