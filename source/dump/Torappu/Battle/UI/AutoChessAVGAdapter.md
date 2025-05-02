# AutoChessAVGAdapter

**Namespace:** `Torappu.Battle.UI`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void _DetachRequestLock()`

- `Void _OnStoryEnd(Object)`

- `Boolean _ExecuteAutoChessOnlyAllow(Command)`

- `Boolean _ExecuteAutoChessOnlyDisable(Command)`

- `Boolean _ExecuteUnlockAutoChessHud(Command)`

- `Boolean _ExecuteLockAutoChessHud(Command)`

- `Boolean _ExecuteLockAutoChessDragOperation(Command)`

- `Boolean _AllowUpgradeStoreOnly(AutoChessServiceMsg, ValueBundle)`

- `Boolean _AllowRefreshStoreOnly(AutoChessServiceMsg, ValueBundle)`

- `Boolean _AllowUseSpMagicOnly(AutoChessServiceMsg, ValueBundle)`

- `Boolean _AllowBuyCharOnly(AutoChessServiceMsg, ValueBundle)`

- `Boolean _AllowRecruitCharOnly(AutoChessServiceMsg, ValueBundle)`

- `Boolean _AllowBuyCharShop2Hand1Only(AutoChessServiceMsg, ValueBundle)`

- `Boolean _AllowBuyCharShop1Hand2Only(AutoChessServiceMsg, ValueBundle)`

- `Boolean _AllowRoundBattleStartOnly(AutoChessServiceMsg, ValueBundle)`

- `Boolean _AllowBuyEquipOrSpellOnly(AutoChessServiceMsg, ValueBundle)`

- `Boolean _AllowEearEquipNotReplaceOnly(AutoChessServiceMsg, ValueBundle)`

- `Boolean _AllowNone(AutoChessServiceMsg, ValueBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class AutoChessAVGAdapter : ExecutorComponent
{
	private const String LOCK_HUD_KEY_IS_TUTORIAL; // 0x0
	private const String LOCK_DRAG_KEY_IS_TUTORIAL; // 0x0
	private List`1 m_bindedLock; // 0x50
	private Dictionary`2 m_checkers; // 0x58
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x8
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__DetachRequestLock; // 0x20
	private static DelegateBridge __Hotfix0__OnStoryEnd; // 0x28
	private static DelegateBridge __Hotfix0__ExecuteAutoChessOnlyAllow; // 0x30
	private static DelegateBridge __Hotfix0__ExecuteAutoChessOnlyDisable; // 0x38
	private static DelegateBridge __Hotfix0__ExecuteUnlockAutoChessHud; // 0x40
	private static DelegateBridge __Hotfix0__ExecuteLockAutoChessHud; // 0x48
	private static DelegateBridge __Hotfix0__ExecuteLockAutoChessDragOperation; // 0x50
	private static DelegateBridge __Hotfix0_GetCheckers; // 0x58
	private static DelegateBridge __Hotfix0__AllowUpgradeStoreOnly; // 0x60
	private static DelegateBridge __Hotfix0__AllowRefreshStoreOnly; // 0x68
	private static DelegateBridge __Hotfix0__AllowUseSpMagicOnly; // 0x70
	private static DelegateBridge __Hotfix0__AllowBuyCharOnly; // 0x78
	private static DelegateBridge __Hotfix0__AllowRecruitCharOnly; // 0x80
	private static DelegateBridge __Hotfix0__AllowBuyCharShop2Hand1Only; // 0x88
	private static DelegateBridge __Hotfix0__AllowBuyCharShop1Hand2Only; // 0x90
	private static DelegateBridge __Hotfix0__AllowRoundBattleStartOnly; // 0x98
	private static DelegateBridge __Hotfix0__AllowBuyEquipOrSpellOnly; // 0xa0
	private static DelegateBridge __Hotfix0__AllowEearEquipNotReplaceOnly; // 0xa8
	private static DelegateBridge __Hotfix0__AllowNone; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8


	// RVA: 0x20270a0 VA: 0x759463f0a0
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x20273bc VA: 0x759463f3bc
	protected override Void ForceCommandEnd() { }
	// RVA: 0x2027420 VA: 0x759463f420
	private Void Start() { }
	// RVA: 0x2027570 VA: 0x759463f570
	private Void OnDestroy() { }
	// RVA: 0x2027740 VA: 0x759463f740
	private Void _DetachRequestLock() { }
	// RVA: 0x202793c VA: 0x759463f93c
	private Void _OnStoryEnd(Object arg) { }
	// RVA: 0x2027a48 VA: 0x759463fa48
	private Boolean _ExecuteAutoChessOnlyAllow(Command command) { }
	// RVA: 0x202826c VA: 0x759464026c
	private Boolean _ExecuteAutoChessOnlyDisable(Command command) { }
	// RVA: 0x20284c8 VA: 0x75946404c8
	private Boolean _ExecuteUnlockAutoChessHud(Command command) { }
	// RVA: 0x2028598 VA: 0x7594640598
	private Boolean _ExecuteLockAutoChessHud(Command command) { }
	// RVA: 0x2028668 VA: 0x7594640668
	private Boolean _ExecuteLockAutoChessDragOperation(Command command) { }
	// RVA: 0x2027d0c VA: 0x759463fd0c
	private Dictionary`2 GetCheckers() { }
	// RVA: 0x2028770 VA: 0x7594640770
	private Boolean _AllowUpgradeStoreOnly(AutoChessServiceMsg msg, ValueBundle requestData) { }
	// RVA: 0x2028804 VA: 0x7594640804
	private Boolean _AllowRefreshStoreOnly(AutoChessServiceMsg msg, ValueBundle requestData) { }
	// RVA: 0x2028898 VA: 0x7594640898
	private Boolean _AllowUseSpMagicOnly(AutoChessServiceMsg msg, ValueBundle requestData) { }
	// RVA: 0x20289c8 VA: 0x75946409c8
	private Boolean _AllowBuyCharOnly(AutoChessServiceMsg msg, ValueBundle requestData) { }
	// RVA: 0x2028abc VA: 0x7594640abc
	private Boolean _AllowRecruitCharOnly(AutoChessServiceMsg msg, ValueBundle requestData) { }
	// RVA: 0x2028bb0 VA: 0x7594640bb0
	private Boolean _AllowBuyCharShop2Hand1Only(AutoChessServiceMsg msg, ValueBundle requestData) { }
	// RVA: 0x2028d08 VA: 0x7594640d08
	private Boolean _AllowBuyCharShop1Hand2Only(AutoChessServiceMsg msg, ValueBundle requestData) { }
	// RVA: 0x2028e60 VA: 0x7594640e60
	private Boolean _AllowRoundBattleStartOnly(AutoChessServiceMsg msg, ValueBundle requestData) { }
	// RVA: 0x2028ef4 VA: 0x7594640ef4
	private Boolean _AllowBuyEquipOrSpellOnly(AutoChessServiceMsg msg, ValueBundle requestData) { }
	// RVA: 0x2028fe8 VA: 0x7594640fe8
	private Boolean _AllowEearEquipNotReplaceOnly(AutoChessServiceMsg msg, ValueBundle requestData) { }
	// RVA: 0x20290dc VA: 0x75946410dc
	private Boolean _AllowNone(AutoChessServiceMsg msg, ValueBundle requestData) { }
	// RVA: 0x2029164 VA: 0x7594641164
	public Void .ctor() { }
}
```