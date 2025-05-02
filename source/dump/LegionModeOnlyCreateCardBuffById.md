# LegionModeOnlyCreateCardBuffById

**Namespace:** ` `


## Fields

- `String _id`

- `LegionCardLibraryType _cardLibraryType`


## Methods

- `SourceType <>xLuaBaseProxy_get_allowedSource()`

- `Boolean <>xLuaBaseProxy_Execute(Blackboard, SourceType, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyCreateCardBuffById : BaseCreateCardBuff
{
	private String _id; // 0x20
	private LegionCardLibraryType _cardLibraryType; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f6aa90 VA: 0x7594582a90
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f6aaf8 VA: 0x7594582af8
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f6aee0 VA: 0x7594582ee0
	public Void .ctor() { }
	// RVA: 0x1f6af50 VA: 0x7594582f50
	private SourceType <>xLuaBaseProxy_get_allowedSource() { }
	// RVA: 0x1f6af58 VA: 0x7594582f58
	private Boolean <>xLuaBaseProxy_Execute(Blackboard P0, SourceType P1, ref Snapshot P2) { }
}
```