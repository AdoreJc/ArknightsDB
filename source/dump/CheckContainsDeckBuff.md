# CheckContainsDeckBuff

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _key`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckContainsDeckBuff : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _key; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f09104 VA: 0x7594521104
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0916c VA: 0x759452116c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f09338 VA: 0x7594521338
	public Void .ctor() { }
}
```