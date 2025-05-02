# CheckCharacterData

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _filterPredefine`

- `Boolean _filterAlias`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckCharacterData : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _filterPredefine; // 0x14
	private Boolean _filterAlias; // 0x15
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f3292c VA: 0x759454a92c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f32994 VA: 0x759454a994
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f32b90 VA: 0x759454ab90
	public Void .ctor() { }
}
```