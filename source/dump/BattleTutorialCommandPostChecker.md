# BattleTutorialCommandPostChecker

**Namespace:** ` `


## Fields

- `AVGTutorialPanel <panel>k__BackingField`

- `ITileBuildableChecker m_tileBuildableCheckerForPutDown`


## Properties

- `AVGTutorialPanel panel`

- `String cmdName`


## Methods

- `AVGTutorialPanel get_panel()`

- `Void set_panel(AVGTutorialPanel)`

- `Void _PostCharacterInfo(Command)`

- `Void _PostPutDown(Command)`

- `Void _PostPutDownPosCheck(Command)`

- `Void _PostPutDownCharIdCheck(Command)`

- `Void AppendTileBuildableChecker(ITileBuildableChecker)`

- `Void RemoveTileBuildableChecker()`

- `Void _PostUseSkill(Command)`

- `Void _PostExitCharacterMenu(Command)`

- `Void OnPostCheckDelayFallback()`

- `String get_cmdName()`

- `Void PostCheck(Boolean, Command)`

- `Void OnCommandFinished(Boolean, Command)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BattleTutorialCommandPostChecker : ICommandPostChecker, IHotfixable
{
	private Dictionary`2 m_postSignalCheckers; // 0x10
	private AVGTutorialPanel <panel>k__BackingField; // 0x18
	private ITileBuildableChecker m_tileBuildableCheckerForPutDown; // 0x20
	private const Single DEFAULT_DELAY; // 0x0
	private static DelegateBridge __Hotfix0_GenPostCheckers; // 0x0
	private static DelegateBridge __Hotfix0_get_panel; // 0x8
	private static DelegateBridge __Hotfix0_set_panel; // 0x10
	private static DelegateBridge __Hotfix0__PostCharacterInfo; // 0x18
	private static DelegateBridge __Hotfix0__PostPutDown; // 0x20
	private static DelegateBridge __Hotfix0__PostPutDownPosCheck; // 0x28
	private static DelegateBridge __Hotfix0__PostPutDownCharIdCheck; // 0x30
	private static DelegateBridge __Hotfix0_AppendTileBuildableChecker; // 0x38
	private static DelegateBridge __Hotfix0_RemoveTileBuildableChecker; // 0x40
	private static DelegateBridge __Hotfix0__PostUseSkill; // 0x48
	private static DelegateBridge __Hotfix0__PostExitCharacterMenu; // 0x50
	private static DelegateBridge __Hotfix0_OnPostCheckDelayFallback; // 0x58
	private static DelegateBridge __Hotfix0_get_cmdName; // 0x60
	private static DelegateBridge __Hotfix0_PostCheck; // 0x68
	private static DelegateBridge __Hotfix0_OnCommandFinished; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public AVGTutorialPanel panel { get; set; }
	public String cmdName { get; }

	// RVA: 0x3fd4ef8 VA: 0x75965ecef8
	private Dictionary`2 GenPostCheckers() { }
	// RVA: 0x3fd5154 VA: 0x75965ed154
	public AVGTutorialPanel get_panel() { }
	// RVA: 0x3fd4c10 VA: 0x75965ecc10
	public Void set_panel(AVGTutorialPanel value) { }
	// RVA: 0x3fd51bc VA: 0x75965ed1bc
	private Void _PostCharacterInfo(Command command) { }
	// RVA: 0x3fd547c VA: 0x75965ed47c
	private Void _PostPutDown(Command command) { }
	// RVA: 0x3fd578c VA: 0x75965ed78c
	private Void _PostPutDownPosCheck(Command command) { }
	// RVA: 0x3fd5560 VA: 0x75965ed560
	private Void _PostPutDownCharIdCheck(Command command) { }
	// RVA: 0x3fd58e4 VA: 0x75965ed8e4
	private Void AppendTileBuildableChecker(ITileBuildableChecker buildableChecker) { }
	// RVA: 0x3fd59ec VA: 0x75965ed9ec
	private Void RemoveTileBuildableChecker() { }
	// RVA: 0x3fd5ae8 VA: 0x75965edae8
	private Void _PostUseSkill(Command command) { }
	// RVA: 0x3fd5d18 VA: 0x75965edd18
	private Void _PostExitCharacterMenu(Command command) { }
	// RVA: 0x3fd5e70 VA: 0x75965ede70
	private Void OnPostCheckDelayFallback() { }
	// RVA: 0x3fd5f6c VA: 0x75965edf6c
	public String get_cmdName() { }
	// RVA: 0x3fd5fe8 VA: 0x75965edfe8
	public Void PostCheck(Boolean isTutorial, Command command) { }
	// RVA: 0x3fd6114 VA: 0x75965ee114
	public Void OnCommandFinished(Boolean isTutorial, Command command) { }
	// RVA: 0x3fd4ba0 VA: 0x75965ecba0
	public Void .ctor() { }
}
```