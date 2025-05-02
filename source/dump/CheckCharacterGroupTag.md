# CheckCharacterGroupTag

**Namespace:** ` `


## Fields

- `ActionTargetType _targetType`

- `String _groupTag`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckCharacterGroupTag : ActionNode
{
	private ActionTargetType _targetType; // 0x10
	private String _groupTag; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1af14 VA: 0x7594532f14
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f1af7c VA: 0x7594532f7c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f1b150 VA: 0x7594533150
	public Void .ctor() { }
}
```