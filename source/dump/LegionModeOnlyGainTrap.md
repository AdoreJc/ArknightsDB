# LegionModeOnlyGainTrap

**Namespace:** ` `


## Fields

- `LegionCardLibraryType _gainToCardType`

- `Boolean _onlyUseOnce`

- `String _tokenKey`

- `Boolean _releaseDiscardBeforeFind`

- `Boolean _extraCheckOnlyUseOnceList`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LegionModeOnlyGainTrap : ActionNode
{
	private LegionCardLibraryType _gainToCardType; // 0x10
	private Boolean _onlyUseOnce; // 0x14
	private String _tokenKey; // 0x18
	private Boolean _releaseDiscardBeforeFind; // 0x20
	private Boolean _extraCheckOnlyUseOnceList; // 0x21
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f63a08 VA: 0x759457ba08
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f63a70 VA: 0x759457ba70
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f63da8 VA: 0x759457bda8
	public Void .ctor() { }
}
```