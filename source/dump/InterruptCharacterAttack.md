# InterruptCharacterAttack

**Namespace:** ` `


## Fields

- `ActionTargetType _charFrom`

- `Boolean _resetCD`

- `Boolean _resetAndClearCD`

- `Boolean _forceUseCharacterAttack`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class InterruptCharacterAttack : ActionNode
{
	private ActionTargetType _charFrom; // 0x10
	private Boolean _resetCD; // 0x14
	private Boolean _resetAndClearCD; // 0x15
	private Boolean _forceUseCharacterAttack; // 0x16
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0e214 VA: 0x7594526214
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0e27c VA: 0x759452627c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0e4a0 VA: 0x75945264a0
	public Void .ctor() { }
}
```