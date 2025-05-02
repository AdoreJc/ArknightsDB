# LegionModeOnlyCheckLastCardDrawProfession

**Namespace:** ` `


## Fields

- `ProfessionCategory _professionCategory`


## Properties

- `LegionGameMode legionMode`


## Methods

- `LegionGameMode get_legionMode()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyCheckLastCardDrawProfession : ActionNode
{
	private ProfessionCategory _professionCategory; // 0x10
	private static DelegateBridge __Hotfix0_get_legionMode; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private LegionGameMode legionMode { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f6cb24 VA: 0x7594584b24
	private LegionGameMode get_legionMode() { }
	// RVA: 0x1f6cc00 VA: 0x7594584c00
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6cc68 VA: 0x7594584c68
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6cd5c VA: 0x7594584d5c
	public Void .ctor() { }
}
```