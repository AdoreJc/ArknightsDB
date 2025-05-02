# UIDragAndPutDownState

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIDirectionSelector _directionSelector`

- `Single _tileLocateRadius`

- `Vector2 _touchOffset`

- `State m_state`

- `Transform m_dragPlane`

- `Character m_dummy`

- `Tile m_currentTile`

- `UICard <uiCard>k__BackingField`

- `Card <card>k__BackingField`


## Properties

- `UICharacterInfoPanel characterInfo`

- `State state`

- `UICard uiCard`

- `Card card`


## Methods

- `UICharacterInfoPanel get_characterInfo()`

- `State get_state()`

- `UICard get_uiCard()`

- `Void set_uiCard(UICard)`

- `Card get_card()`

- `Void set_card(Card)`

- `Void _OnBeginDrag(UICard)`

- `Void _OnEndDrag()`

- `Void _OnBottomMaskClicked(Object)`

- `Void _ClearDummy()`

- `Boolean _CheckLocatable(Tile, Vector2)`

- `Void _PutDownInternal(Tile)`

- `Void _UpdateBuildableHighlight()`

- `Boolean _TryGetScreenPos(out)`

- `Void _UpdateInternal()`

- `Void _OnDirectionSelected(Boolean, Direction)`

- `Void _MoveToMatch(Tile)`

- `Vector2 _ConvertScreenPos(Vector2)`

- `Void _EnableBuildableHighlight()`

- `Boolean _CheckBuildable(Tile)`

- `Void OnDestroy()`

- `Void <OnInit>b__34_0(Object)`

- `Void <OnInit>b__34_1(Object)`

- `Boolean <>xLuaBaseProxy_get_enablePause()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIDragAndPutDownState : UIStateNode
{
	private const Single DRAG_UNHOOK_RADIUS_SQR; // 0x0
	private UIDirectionSelector _directionSelector; // 0x20
	private Single _tileLocateRadius; // 0x28
	private Vector2 _touchOffset; // 0x2c
	private State m_state; // 0x34
	private Transform m_dragPlane; // 0x38
	private Character m_dummy; // 0x40
	private Tile m_currentTile; // 0x48
	private UICard <uiCard>k__BackingField; // 0x50
	private Card <card>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_characterInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_uiState; // 0x8
	private static DelegateBridge __Hotfix0_get_state; // 0x10
	private static DelegateBridge __Hotfix0_get_uiCard; // 0x18
	private static DelegateBridge __Hotfix0_set_uiCard; // 0x20
	private static DelegateBridge __Hotfix0_get_card; // 0x28
	private static DelegateBridge __Hotfix0_set_card; // 0x30
	private static DelegateBridge __Hotfix0_get_enablePause; // 0x38
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x40
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x48
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x50
	private static DelegateBridge __Hotfix0__OnBeginDrag; // 0x58
	private static DelegateBridge __Hotfix0__OnEndDrag; // 0x60
	private static DelegateBridge __Hotfix0__OnBottomMaskClicked; // 0x68
	private static DelegateBridge __Hotfix0_OnInit; // 0x70
	private static DelegateBridge __Hotfix0_OnEnter; // 0x78
	private static DelegateBridge __Hotfix0_OnTick; // 0x80
	private static DelegateBridge __Hotfix0_OnExit; // 0x88
	private static DelegateBridge __Hotfix0__ClearDummy; // 0x90
	private static DelegateBridge __Hotfix0__CheckLocatable; // 0x98
	private static DelegateBridge __Hotfix0__PutDownInternal; // 0xa0
	private static DelegateBridge __Hotfix0__UpdateBuildableHighlight; // 0xa8
	private static DelegateBridge __Hotfix0__TryGetScreenPos; // 0xb0
	private static DelegateBridge __Hotfix0__UpdateInternal; // 0xb8
	private static DelegateBridge __Hotfix0__OnDirectionSelected; // 0xc0
	private static DelegateBridge __Hotfix0__MoveToMatch; // 0xc8
	private static DelegateBridge __Hotfix0__ConvertScreenPos; // 0xd0
	private static DelegateBridge __Hotfix0__EnableBuildableHighlight; // 0xd8
	private static DelegateBridge __Hotfix0__CheckBuildable; // 0xe0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	private UICharacterInfoPanel characterInfo { get; }
	public override UIStateEnum uiState { get; }
	public State state { get; }
	public UICard uiCard { get; set; }
	public Card card { get; set; }
	public override Boolean enablePause { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enablePerspectiveCanvas { get; }

	// RVA: 0x20596e8 VA: 0x75946716e8
	private UICharacterInfoPanel get_characterInfo() { }
	// RVA: 0x2059774 VA: 0x7594671774
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20597dc VA: 0x75946717dc
	public State get_state() { }
	// RVA: 0x2059844 VA: 0x7594671844
	public UICard get_uiCard() { }
	// RVA: 0x20598ac VA: 0x75946718ac
	private Void set_uiCard(UICard value) { }
	// RVA: 0x2059930 VA: 0x7594671930
	public Card get_card() { }
	// RVA: 0x2059998 VA: 0x7594671998
	private Void set_card(Card value) { }
	// RVA: 0x2059a1c VA: 0x7594671a1c
	public override Boolean get_enablePause() { }
	// RVA: 0x2059a80 VA: 0x7594671a80
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x2059ae4 VA: 0x7594671ae4
	public override Boolean get_enableShowRange() { }
	// RVA: 0x2059b48 VA: 0x7594671b48
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x2059bb0 VA: 0x7594671bb0
	private Void _OnBeginDrag(UICard uiCard) { }
	// RVA: 0x2059d3c VA: 0x7594671d3c
	private Void _OnEndDrag() { }
	// RVA: 0x205a04c VA: 0x759467204c
	private Void _OnBottomMaskClicked(Object arg) { }
	// RVA: 0x205a194 VA: 0x7594672194
	public override Void OnInit(UIStateEnum uiState, UIStateMachine stateMachine) { }
	// RVA: 0x205a400 VA: 0x7594672400
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x205ad8c VA: 0x7594672d8c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x205af44 VA: 0x7594672f44
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x205b0e0 VA: 0x75946730e0
	private Void _ClearDummy() { }
	// RVA: 0x205b2f4 VA: 0x75946732f4
	private Boolean _CheckLocatable(Tile tile, Vector2 mapPos) { }
	// RVA: 0x2059da8 VA: 0x7594671da8
	private Void _PutDownInternal(Tile tile) { }
	// RVA: 0x205ae2c VA: 0x7594672e2c
	private Void _UpdateBuildableHighlight() { }
	// RVA: 0x205b668 VA: 0x7594673668
	private Boolean _TryGetScreenPos(out Vector2 screenPos) { }
	// RVA: 0x205a958 VA: 0x7594672958
	private Void _UpdateInternal() { }
	// RVA: 0x205b4bc VA: 0x75946734bc
	private Void _OnDirectionSelected(Boolean selected, Direction direction) { }
	// RVA: 0x205b3c0 VA: 0x75946733c0
	private Void _MoveToMatch(Tile tile) { }
	// RVA: 0x205b7d4 VA: 0x75946737d4
	private Vector2 _ConvertScreenPos(Vector2 screenPos) { }
	// RVA: 0x205a7a0 VA: 0x75946727a0
	private Void _EnableBuildableHighlight() { }
	// RVA: 0x205b884 VA: 0x7594673884
	private Boolean _CheckBuildable(Tile tile) { }
	// RVA: 0x205ba58 VA: 0x7594673a58
	private Void OnDestroy() { }
	// RVA: 0x205bac0 VA: 0x7594673ac0
	public Void .ctor() { }
	// RVA: 0x205bb74 VA: 0x7594673b74
	private Void <OnInit>b__34_0(Object card) { }
	// RVA: 0x205bc3c VA: 0x7594673c3c
	private Void <OnInit>b__34_1(Object _) { }
	// RVA: 0x205bca8 VA: 0x7594673ca8
	private Boolean <>xLuaBaseProxy_get_enablePause() { }
	// RVA: 0x205bcb0 VA: 0x7594673cb0
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x205bcb8 VA: 0x7594673cb8
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x205bcc0 VA: 0x7594673cc0
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x205bcc8 VA: 0x7594673cc8
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x205bcd0 VA: 0x7594673cd0
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x205bcd8 VA: 0x7594673cd8
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```