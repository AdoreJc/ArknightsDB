# BattleLogMeta

**Namespace:** `Torappu.UI`


## Fields

- `PredefinedAssistData predefinedAssistData`

- `BattleCharmsData battleCharmsData`

- `BattleTemplateTrapData battleTemplateTrapData`

- `BattleTechData battleTechesData`

- `BattleCartData battleCartData`

- `BattleTrapToolData battleTrapToolData`

- `BattlePerformanceData battlePerformanceData`

- `BattleFireworkData battleFireworkData`


## Methods

- `Boolean IsEmpty()`

- `Boolean IsPredefinedAssistEmpty()`

- `Boolean _IsPredefinedAssistEmpty()`

- `Boolean _IsBattleCharmListEmpty()`

- `Boolean _IsBattleTechListEmpty()`

- `Boolean _IsTemplateTrapListEmpty()`

- `Boolean _IsBattleCartDictEmpty()`

- `Boolean _IsBattleTrapToolListEmpty()`

- `Boolean _IsBattlePerformanceEmpty()`

- `Boolean _IsBattleFireworkEmpty()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class BattleLogMeta : IHotfixable
{
	public PredefinedAssistData predefinedAssistData; // 0x10
	public BattleCharmsData battleCharmsData; // 0x18
	public BattleTemplateTrapData battleTemplateTrapData; // 0x20
	public BattleTechData battleTechesData; // 0x28
	public BattleCartData battleCartData; // 0x30
	public BattleTrapToolData battleTrapToolData; // 0x38
	public BattlePerformanceData battlePerformanceData; // 0x40
	public BattleFireworkData battleFireworkData; // 0x48
	private static DelegateBridge __Hotfix0_IsEmpty; // 0x0
	private static DelegateBridge __Hotfix0_IsPredefinedAssistEmpty; // 0x8
	private static DelegateBridge __Hotfix0__IsPredefinedAssistEmpty; // 0x10
	private static DelegateBridge __Hotfix0__IsBattleCharmListEmpty; // 0x18
	private static DelegateBridge __Hotfix0__IsBattleTechListEmpty; // 0x20
	private static DelegateBridge __Hotfix0__IsTemplateTrapListEmpty; // 0x28
	private static DelegateBridge __Hotfix0__IsBattleCartDictEmpty; // 0x30
	private static DelegateBridge __Hotfix0__IsBattleTrapToolListEmpty; // 0x38
	private static DelegateBridge __Hotfix0__IsBattlePerformanceEmpty; // 0x40
	private static DelegateBridge __Hotfix0__IsBattleFireworkEmpty; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2171948 VA: 0x7594789948
	public Boolean IsEmpty() { }
	// RVA: 0x2171fe4 VA: 0x7594789fe4
	public Boolean IsPredefinedAssistEmpty() { }
	// RVA: 0x2171b24 VA: 0x7594789b24
	private Boolean _IsPredefinedAssistEmpty() { }
	// RVA: 0x2171bd0 VA: 0x7594789bd0
	private Boolean _IsBattleCharmListEmpty() { }
	// RVA: 0x2171c68 VA: 0x7594789c68
	private Boolean _IsBattleTechListEmpty() { }
	// RVA: 0x2171ec8 VA: 0x7594789ec8
	private Boolean _IsTemplateTrapListEmpty() { }
	// RVA: 0x2171d00 VA: 0x7594789d00
	private Boolean _IsBattleCartDictEmpty() { }
	// RVA: 0x2171d98 VA: 0x7594789d98
	private Boolean _IsBattleTrapToolListEmpty() { }
	// RVA: 0x2171e30 VA: 0x7594789e30
	private Boolean _IsBattlePerformanceEmpty() { }
	// RVA: 0x2171f60 VA: 0x7594789f60
	private Boolean _IsBattleFireworkEmpty() { }
	// RVA: 0x217204c VA: 0x759478a04c
	public Void .ctor() { }
}
```