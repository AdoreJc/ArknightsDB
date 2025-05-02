# DynamicBuffWoodrdTile

**Namespace:** `Torappu.Battle`


## Methods

- `Void doExtraBattleLog(String)`

- `Void CheckEnemiesFallDown()`

- `Void <>xLuaBaseProxy_Init(TileData, GridPosition)`

- `Boolean <>xLuaBaseProxy_get_triggerable()`

- `Void <>xLuaBaseProxy_OnTrigger()`

- `Boolean <>xLuaBaseProxy_SwitchMode(Int32)`

- `Void <>xLuaBaseProxy_OnEnemyEnter(Enemy)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DynamicBuffWoodrdTile : DynamicBuffTile
{
	private const String SPECIAL_UNIT_MARK_BUFF_KEY; // 0x0
	private const String LOGTYPE; // 0x0
	private const String LOGTARGET; // 0x0
	private const String LOGBORN; // 0x0
	private const String LOGKILL; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_doExtraBattleLog; // 0x8
	private static DelegateBridge __Hotfix0_get_triggerable; // 0x10
	private static DelegateBridge __Hotfix0_OnTrigger; // 0x18
	private static DelegateBridge __Hotfix0_SwitchMode; // 0x20
	private static DelegateBridge __Hotfix0_CheckEnemiesFallDown; // 0x28
	private static DelegateBridge __Hotfix0_OnEnemyEnter; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override Boolean triggerable { get; }

	// RVA: 0x408e754 VA: 0x75966a6754
	public override Void Init(TileData tileData, GridPosition pos) { }
	// RVA: 0x408e904 VA: 0x75966a6904
	private Void doExtraBattleLog(String key) { }
	// RVA: 0x408ea6c VA: 0x75966a6a6c
	public override Boolean get_triggerable() { }
	// RVA: 0x408eaec VA: 0x75966a6aec
	protected override Void OnTrigger() { }
	// RVA: 0x408ef00 VA: 0x75966a6f00
	public override Boolean SwitchMode(Int32 modeIndex) { }
	// RVA: 0x408eb5c VA: 0x75966a6b5c
	private Void CheckEnemiesFallDown() { }
	// RVA: 0x408f02c VA: 0x75966a702c
	protected override Void OnEnemyEnter(Enemy enemy) { }
	// RVA: 0x408f168 VA: 0x75966a7168
	public Void .ctor() { }
	// RVA: 0x408f1d4 VA: 0x75966a71d4
	private Void <>xLuaBaseProxy_Init(TileData P0, GridPosition P1) { }
	// RVA: 0x408f1d8 VA: 0x75966a71d8
	private Boolean <>xLuaBaseProxy_get_triggerable() { }
	// RVA: 0x408f280 VA: 0x75966a7280
	private Void <>xLuaBaseProxy_OnTrigger() { }
	// RVA: 0x408f284 VA: 0x75966a7284
	private Boolean <>xLuaBaseProxy_SwitchMode(Int32 P0) { }
	// RVA: 0x408f288 VA: 0x75966a7288
	private Void <>xLuaBaseProxy_OnEnemyEnter(Enemy P0) { }
}
```