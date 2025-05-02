# LegionFindLibraryCardTrigger

**Namespace:** `Torappu.Battle`


## Fields

- `String _cardKey`

- `LegionCardLibraryType _findType`

- `LegionGameMode m_gameMode`


## Properties

- `LegionGameMode gameMode`


## Methods

- `LegionGameMode get_gameMode()`

- `Boolean <>xLuaBaseProxy_get_isReadyToTrig()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class LegionFindLibraryCardTrigger : TargetTrigger
{
	private String _cardKey; // 0x20
	private LegionCardLibraryType _findType; // 0x28
	private LegionGameMode m_gameMode; // 0x30
	private List`1 m_allCards; // 0x38
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_get_isReadyToTrig; // 0x8
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x10
	private static DelegateBridge __Hotfix0_Search; // 0x18
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Entity target { get; }
	public override Boolean isReadyToTrig { get; }
	private LegionGameMode gameMode { get; }

	// RVA: 0x1bd85b8 VA: 0x75941f05b8
	public override Entity get_target() { }
	// RVA: 0x1bd861c VA: 0x75941f061c
	public override Boolean get_isReadyToTrig() { }
	// RVA: 0x1bd8684 VA: 0x75941f0684
	private LegionGameMode get_gameMode() { }
	// RVA: 0x1bd87b0 VA: 0x75941f07b0
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd895c VA: 0x75941f095c
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bd89d8 VA: 0x75941f09d8
	public Void .ctor() { }
	// RVA: 0x1bd8ad0 VA: 0x75941f0ad0
	private Boolean <>xLuaBaseProxy_get_isReadyToTrig() { }
}
```