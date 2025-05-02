# AutoChessDragState

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Vector2 _touchOffset`

- `Vector3 _overlapOffset`

- `Color _overlapColor`

- `Single _worldSnapLen`

- `Single _toastTime`

- `UIAutoChessDragEquipPanel _equipStatusPanel`

- `AutoChessGameMode m_gameMode`

- `Boolean m_inited`

- `State m_state`

- `Character m_outlineDummy`

- `Color m_cacheOverlapDefaultColor`

- `Color m_outlineDefaultColor`

- `Direction m_direction`

- `Boolean m_needRevertBattleOverlap`

- `Boolean m_operationFinished`

- `Boolean m_isEquip`

- `Boolean m_isMagic`

- `Int32 m_beginInstId`

- `Int32 m_equipFullCharInstId`

- `Boolean m_waitForEquipAnimation`

- `Boolean m_isDialogOpened`

- `Int32 m_replaceInstId`

- `UIAutoChessDragEquipPanel m_equipStatusPanel`

- `Tile m_currentTile`

- `Coroutine m_dragUpdateCoroutine`

- `TileDragContext m_dragContext`

- `BattleDragOperationHandler m_handler`


## Properties

- `UIDirectionSelector directionSelector`

- `AutoChessGameMode gameMode`

- `BattleGameInfo gameInfo`

- `DummyManager dummyManager`

- `Boolean isGameModeStateValid`


## Methods

- `UIDirectionSelector get_directionSelector()`

- `AutoChessGameMode get_gameMode()`

- `BattleGameInfo get_gameInfo()`

- `DummyManager get_dummyManager()`

- `Boolean get_isGameModeStateValid()`

- `Void OnDestroy()`

- `IEnumerator _Update()`

- `Void _DoOperation()`

- `Void _BindDragInterruptIfNot()`

- `Void _OnBottomMaskBeginDrag(Object)`

- `Void _DoOnButtomMaskBeginDrag(Object)`

- `Void _OnDirectionSelected(Boolean, Direction)`

- `Void _EquipCharacter()`

- `Void _DoEquipCharacter(Output)`

- `Void _WaitForEquip()`

- `Void _UseMagic(Direction)`

- `Boolean _IsBeginTileValid(Tile)`

- `Character _CreateDummy(AutoChessUnitQuery)`

- `Void _CheckSpell()`

- `Void _CreateOutline()`

- `Void _ClearOutline()`

- `Boolean _CheckBuildable(Tile)`

- `Boolean _CheckBuildable(Tile, Tile)`

- `Void _UpdateInternal()`

- `Void _UpdateCharacterInfo(String)`

- `Void _ResetCharacterInfo()`

- `Void _ClearDummy()`

- `Void _TryMoveToNextState()`

- `Void _TutorialTryRaiseBattlePutDownSignal()`

- `Void _DoShowPanel()`

- `Void OnConfirmFinish(Object)`

- `Void OpenReplaceDlgSuccess(Object)`

- `Void _DoBattleOverlap(Character)`

- `Void _RevertBattleOverlap(Character)`

- `Void _SwitchToDefaultState()`

- `Void <_BindDragInterruptIfNot>b__53_0(Object)`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Boolean <>xLuaBaseProxy_get_enableBackpress()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class AutoChessDragState : UIStateNode
{
	private const String LOCK_HUD_KEY_IS_DRAGGING; // 0x0
	private Vector2 _touchOffset; // 0x20
	private Vector3 _overlapOffset; // 0x28
	private Color _overlapColor; // 0x34
	private Single _worldSnapLen; // 0x44
	private Single _toastTime; // 0x48
	private UIAutoChessDragEquipPanel _equipStatusPanel; // 0x50
	private AutoChessGameMode m_gameMode; // 0x58
	private Boolean m_inited; // 0x60
	private State m_state; // 0x64
	private Character m_outlineDummy; // 0x68
	private Color m_cacheOverlapDefaultColor; // 0x70
	private Color m_outlineDefaultColor; // 0x80
	private Direction m_direction; // 0x90
	private Boolean m_needRevertBattleOverlap; // 0x94
	private Boolean m_operationFinished; // 0x95
	private Boolean m_isEquip; // 0x96
	private Boolean m_isMagic; // 0x97
	private Int32 m_beginInstId; // 0x98
	private Int32 m_equipFullCharInstId; // 0x9c
	private Boolean m_waitForEquipAnimation; // 0xa0
	private Boolean m_isDialogOpened; // 0xa1
	private Int32 m_replaceInstId; // 0xa4
	private UIAutoChessDragEquipPanel m_equipStatusPanel; // 0xa8
	private Tile m_currentTile; // 0xb0
	private Coroutine m_dragUpdateCoroutine; // 0xb8
	private TileDragContext m_dragContext; // 0xc0
	private DragHandler`1 m_dragHandler; // 0xc8
	private BattleDragOperationHandler m_handler; // 0xd0
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x8
	private static DelegateBridge __Hotfix0_get_enableBackpress; // 0x10
	private static DelegateBridge __Hotfix0_get_directionSelector; // 0x18
	private static DelegateBridge __Hotfix0_get_gameMode; // 0x20
	private static DelegateBridge __Hotfix0_get_gameInfo; // 0x28
	private static DelegateBridge __Hotfix0_get_dummyManager; // 0x30
	private static DelegateBridge __Hotfix0_get_isGameModeStateValid; // 0x38
	private static DelegateBridge __Hotfix0_OnInit; // 0x40
	private static DelegateBridge __Hotfix0_OnEnter; // 0x48
	private static DelegateBridge __Hotfix0_OnTick; // 0x50
	private static DelegateBridge __Hotfix0_OnExit; // 0x58
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x60
	private static DelegateBridge __Hotfix0__Update; // 0x68
	private static DelegateBridge __Hotfix0__DoOperation; // 0x70
	private static DelegateBridge __Hotfix0__BindDragInterruptIfNot; // 0x78
	private static DelegateBridge __Hotfix0__OnBottomMaskBeginDrag; // 0x80
	private static DelegateBridge __Hotfix0__DoOnButtomMaskBeginDrag; // 0x88
	private static DelegateBridge __Hotfix0__OnDirectionSelected; // 0x90
	private static DelegateBridge __Hotfix0__EquipCharacter; // 0x98
	private static DelegateBridge __Hotfix0__DoEquipCharacter; // 0xa0
	private static DelegateBridge __Hotfix0__WaitForEquip; // 0xa8
	private static DelegateBridge __Hotfix0__UseMagic; // 0xb0
	private static DelegateBridge __Hotfix0__GetMagicCharChessInstIds; // 0xb8
	private static DelegateBridge __Hotfix0__IsBeginTileValid; // 0xc0
	private static DelegateBridge __Hotfix0__CreateDummy; // 0xc8
	private static DelegateBridge __Hotfix0__CheckSpell; // 0xd0
	private static DelegateBridge __Hotfix0__CreateOutline; // 0xd8
	private static DelegateBridge __Hotfix0__ClearOutline; // 0xe0
	private static DelegateBridge __Hotfix0__CheckBuildable; // 0xe8
	private static DelegateBridge __Hotfix1__CheckBuildable; // 0xf0
	private static DelegateBridge __Hotfix0__UpdateInternal; // 0xf8
	private static DelegateBridge __Hotfix0__UpdateCharacterInfo; // 0x100
	private static DelegateBridge __Hotfix0__ResetCharacterInfo; // 0x108
	private static DelegateBridge __Hotfix0__ClearDummy; // 0x110
	private static DelegateBridge __Hotfix0__TryMoveToNextState; // 0x118
	private static DelegateBridge __Hotfix0__TutorialTryRaiseBattlePutDownSignal; // 0x120
	private static DelegateBridge __Hotfix0__DoShowPanel; // 0x128
	private static DelegateBridge __Hotfix0_OnConfirmFinish; // 0x130
	private static DelegateBridge __Hotfix0_OpenReplaceDlgSuccess; // 0x138
	private static DelegateBridge __Hotfix0__DoBattleOverlap; // 0x140
	private static DelegateBridge __Hotfix0__RevertBattleOverlap; // 0x148
	private static DelegateBridge __Hotfix0__SwitchToDefaultState; // 0x150
	private static DelegateBridge _c__Hotfix0_ctor; // 0x158

	public override UIStateEnum uiState { get; }
	public override Boolean enablePerspectiveCanvas { get; }
	public override Boolean enableBackpress { get; }
	private UIDirectionSelector directionSelector { get; }
	private AutoChessGameMode gameMode { get; }
	private BattleGameInfo gameInfo { get; }
	private DummyManager dummyManager { get; }
	private Boolean isGameModeStateValid { get; }

	// RVA: 0x2020744 VA: 0x7594638744
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20207ac VA: 0x75946387ac
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x2020814 VA: 0x7594638814
	public override Boolean get_enableBackpress() { }
	// RVA: 0x2020878 VA: 0x7594638878
	private UIDirectionSelector get_directionSelector() { }
	// RVA: 0x2020904 VA: 0x7594638904
	private AutoChessGameMode get_gameMode() { }
	// RVA: 0x20209b4 VA: 0x75946389b4
	private BattleGameInfo get_gameInfo() { }
	// RVA: 0x2020a40 VA: 0x7594638a40
	private DummyManager get_dummyManager() { }
	// RVA: 0x2020ab8 VA: 0x7594638ab8
	private Boolean get_isGameModeStateValid() { }
	// RVA: 0x2020b60 VA: 0x7594638b60
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x202109c VA: 0x759463909c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x2021c4c VA: 0x7594639c4c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x2021e4c VA: 0x7594639e4c
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x202268c VA: 0x759463a68c
	public Void OnDestroy() { }
	// RVA: 0x2020ff0 VA: 0x7594638ff0
	public IEnumerator _Update() { }
	// RVA: 0x202226c VA: 0x759463a26c
	private Void _DoOperation() { }
	// RVA: 0x2021350 VA: 0x7594639350
	private Void _BindDragInterruptIfNot() { }
	// RVA: 0x2022bcc VA: 0x759463abcc
	private Void _OnBottomMaskBeginDrag(Object arg) { }
	// RVA: 0x2022d50 VA: 0x759463ad50
	private Void _DoOnButtomMaskBeginDrag(Object arg) { }
	// RVA: 0x2023244 VA: 0x759463b244
	private Void _OnDirectionSelected(Boolean selected, Direction direction) { }
	// RVA: 0x20234d4 VA: 0x759463b4d4
	private Void _EquipCharacter() { }
	// RVA: 0x20236e8 VA: 0x759463b6e8
	private Void _DoEquipCharacter(Output replaceData) { }
	// RVA: 0x2023970 VA: 0x759463b970
	private Void _WaitForEquip() { }
	// RVA: 0x20235f4 VA: 0x759463b5f4
	private Void _UseMagic(Direction direction) { }
	// RVA: 0x2022788 VA: 0x759463a788
	private List`1 _GetMagicCharChessInstIds() { }
	// RVA: 0x20239dc VA: 0x759463b9dc
	private Boolean _IsBeginTileValid(Tile tile) { }
	// RVA: 0x2023b54 VA: 0x759463bb54
	private Character _CreateDummy(AutoChessUnitQuery query) { }
	// RVA: 0x2021a10 VA: 0x7594639a10
	private Void _CheckSpell() { }
	// RVA: 0x2021554 VA: 0x7594639554
	private Void _CreateOutline() { }
	// RVA: 0x2023cc4 VA: 0x759463bcc4
	private Void _ClearOutline() { }
	// RVA: 0x2023e80 VA: 0x759463be80
	private Boolean _CheckBuildable(Tile tile) { }
	// RVA: 0x2023f40 VA: 0x759463bf40
	private Boolean _CheckBuildable(Tile begin, Tile current) { }
	// RVA: 0x2021cc8 VA: 0x7594639cc8
	private Void _UpdateInternal() { }
	// RVA: 0x2024468 VA: 0x759463c468
	private Void _UpdateCharacterInfo(String chessId) { }
	// RVA: 0x20246d0 VA: 0x759463c6d0
	private Void _ResetCharacterInfo() { }
	// RVA: 0x202206c VA: 0x759463a06c
	private Void _ClearDummy() { }
	// RVA: 0x2024004 VA: 0x759463c004
	private Void _TryMoveToNextState() { }
	// RVA: 0x2024750 VA: 0x759463c750
	private Void _TutorialTryRaiseBattlePutDownSignal() { }
	// RVA: 0x20249f8 VA: 0x759463c9f8
	private Void _DoShowPanel() { }
	// RVA: 0x2024a9c VA: 0x759463ca9c
	public Void OnConfirmFinish(Object obj) { }
	// RVA: 0x2024bc4 VA: 0x759463cbc4
	public Void OpenReplaceDlgSuccess(Object obj) { }
	// RVA: 0x2024904 VA: 0x759463c904
	private Void _DoBattleOverlap(Character overlapCharacter) { }
	// RVA: 0x20221a0 VA: 0x759463a1a0
	private Void _RevertBattleOverlap(Character currentCharacter) { }
	// RVA: 0x2021478 VA: 0x7594639478
	private Void _SwitchToDefaultState() { }
	// RVA: 0x2024c44 VA: 0x759463cc44
	public Void .ctor() { }
	// RVA: 0x2024e28 VA: 0x759463ce28
	private Void <_BindDragInterruptIfNot>b__53_0(Object _) { }
	// RVA: 0x2024ebc VA: 0x759463cebc
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x2024ec4 VA: 0x759463cec4
	private Boolean <>xLuaBaseProxy_get_enableBackpress() { }
	// RVA: 0x2024ecc VA: 0x759463cecc
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x2024ed4 VA: 0x759463ced4
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x2024edc VA: 0x759463cedc
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```