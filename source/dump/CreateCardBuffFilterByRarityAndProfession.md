# CreateCardBuffFilterByRarityAndProfession

**Namespace:** ` `


## Fields

- `RarityRankMask _rarity`


## Properties

- `ProfessionCategory professionGroup`


## Methods

- `ProfessionCategory get_professionGroup()`

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateCardBuffFilterByRarityAndProfession : BaseCreateCardBuff
{
	private RarityRankMask _rarity; // 0x20
	private ProfessionCategory[] _profession; // 0x28
	private static DelegateBridge __Hotfix0_get_professionGroup; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private ProfessionCategory professionGroup { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f06ef8 VA: 0x759451eef8
	private ProfessionCategory get_professionGroup() { }
	// RVA: 0x1f06fb0 VA: 0x759451efb0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f07018 VA: 0x759451f018
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0725c VA: 0x759451f25c
	public Void .ctor() { }
	// RVA: 0x1f072c8 VA: 0x759451f2c8
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f072cc VA: 0x759451f2cc
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```