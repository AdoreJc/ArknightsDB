# LegionModeOnlyGainGoldViaCardNum

**Namespace:** ` `


## Fields

- `LegionCardLibraryType _cardType`

- `Int32 _goldPerCount`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyGainGoldViaCardNum : ActionNode
{
	private LegionCardLibraryType _cardType; // 0x10
	private Int32 _goldPerCount; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f62c38 VA: 0x759457ac38
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f62ca0 VA: 0x759457aca0
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f62e24 VA: 0x759457ae24
	public Void .ctor() { }
}
```