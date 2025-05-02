# LegionModeOnlyCheckCardInHandViaId

**Namespace:** ` `


## Fields

- `String cardId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyCheckCardInHandViaId : ActionNode
{
	private String cardId; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f68d9c VA: 0x7594580d9c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f68e04 VA: 0x7594580e04
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f68f78 VA: 0x7594580f78
	public Void .ctor() { }
}
```