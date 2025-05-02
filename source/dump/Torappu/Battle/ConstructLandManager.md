# ConstructLandManager

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean m_gameStarted`

- `SyncHelper m_syncHelper`


## Properties

- `SandboxV2Data dataTable`

- `PlayerSandboxV2 playerSandboxV2`


## Methods

- `SandboxV2Data get_dataTable()`

- `PlayerSandboxV2 get_playerSandboxV2()`

- `Void _OnGameStart(Object)`

- `Void _OnGameReady(Object)`

- `Void _OnDeckCreated(Object)`

- `Void _BindDefaultDeckEvent(Deck)`

- `Void _OnCardSpawn(GridPosition, Direction, Card)`

- `Void _OnPageResume(Object)`

- `Void _OnDoResetMap(Object)`

- `Void _DoSaveMap(Object)`

- `Void DoOperation(IConstructOp)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ConstructLandManager : EnvManager
{
	private Boolean m_gameStarted; // 0x28
	private List`1 m_opQueue; // 0x30
	private ListDict`2 m_cards; // 0x38
	private SyncHelper m_syncHelper; // 0x40
	private static DelegateBridge __Hotfix0_get_dataTable; // 0x0
	private static DelegateBridge __Hotfix0_get_playerSandboxV2; // 0x8
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0__OnGameStart; // 0x20
	private static DelegateBridge __Hotfix0__OnGameReady; // 0x28
	private static DelegateBridge __Hotfix0__OnDeckCreated; // 0x30
	private static DelegateBridge __Hotfix0__BindDefaultDeckEvent; // 0x38
	private static DelegateBridge __Hotfix0__OnCardSpawn; // 0x40
	private static DelegateBridge __Hotfix0__OnPageResume; // 0x48
	private static DelegateBridge __Hotfix0__OnDoResetMap; // 0x50
	private static DelegateBridge __Hotfix0__DoSaveMap; // 0x58
	private static DelegateBridge __Hotfix0_DoOperation; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	private SandboxV2Data dataTable { get; }
	private PlayerSandboxV2 playerSandboxV2 { get; }
	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x404491c VA: 0x759665c91c
	private SandboxV2Data get_dataTable() { }
	// RVA: 0x40449b4 VA: 0x759665c9b4
	private PlayerSandboxV2 get_playerSandboxV2() { }
	// RVA: 0x4044a84 VA: 0x759665ca84
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x4044c8c VA: 0x759665cc8c
	public override Void Init(GlobalEnvSystem system) { }
	// RVA: 0x4044e88 VA: 0x759665ce88
	private Void _OnGameStart(Object arg) { }
	// RVA: 0x4045110 VA: 0x759665d110
	private Void _OnGameReady(Object arg) { }
	// RVA: 0x4045724 VA: 0x759665d724
	private Void _OnDeckCreated(Object arg) { }
	// RVA: 0x404556c VA: 0x759665d56c
	private Void _BindDefaultDeckEvent(Deck deck) { }
	// RVA: 0x40458fc VA: 0x759665d8fc
	private Void _OnCardSpawn(GridPosition pos, Direction dir, Card card) { }
	// RVA: 0x4045cd0 VA: 0x759665dcd0
	private Void _OnPageResume(Object arg) { }
	// RVA: 0x4045d5c VA: 0x759665dd5c
	private Void _OnDoResetMap(Object arg) { }
	// RVA: 0x4045f9c VA: 0x759665df9c
	private Void _DoSaveMap(Object arg) { }
	// RVA: 0x4045a58 VA: 0x759665da58
	public Void DoOperation(IConstructOp op) { }
	// RVA: 0x4046060 VA: 0x759665e060
	public Void .ctor() { }
	// RVA: 0x4046174 VA: 0x759665e174
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x404617c VA: 0x759665e17c
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
}
```