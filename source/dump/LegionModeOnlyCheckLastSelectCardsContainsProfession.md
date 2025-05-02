# LegionModeOnlyCheckLastSelectCardsContainsProfession

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `ProfessionCategory _professionCategory`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyCheckLastSelectCardsContainsProfession : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private ProfessionCategory _professionCategory; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f64968 VA: 0x759457c968
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f649d0 VA: 0x759457c9d0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f64bcc VA: 0x759457cbcc
	public Void .ctor() { }
}
```