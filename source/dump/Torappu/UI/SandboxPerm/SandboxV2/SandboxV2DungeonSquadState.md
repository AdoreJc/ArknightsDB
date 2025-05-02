# SandboxV2DungeonSquadState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2SquadGroupPanel _squadGroupPanelPrefab`

- `Transform _charRepoContainer`

- `SandboxV2SquadStartBattleView _startBattleView`

- `RectTransform _backRt`

- `Text _textActionCost`

- `Boolean m_hasInited`

- `String m_topicId`

- `SandboxV2DungeonSquadStateBean m_stateBean`

- `SandboxV2SquadGroupPanel m_squadGroupPanel`

- `OpenOption m_cachedOpenOption`

- `Int32 m_cachedDineCharInstId`

- `Input m_cachedToolSelectInput`

- `Int32 m_workbenchMakeDialogInst`


## Methods

- `Void _InitIfNot()`

- `Void _EventOnBtnBack()`

- `Void EventOnBtnBack()`

- `Void _OnJumpFromToolSelectState(IStateBean)`

- `Void _OnJumpToToolSelectState(IStateBean)`

- `Void _OnJumpFromCharSelectState(IStateBean)`

- `Void _OnJumpToCharSelectState(IStateBean)`

- `Void _OnJumpFromDineState(IStateBean)`

- `Void _OnJumpToDineState(IStateBean)`

- `Void OpenCharSelectState(OpenOption)`

- `Void OpenDineState(Int32)`

- `Void OpenToolSelectState(Input)`

- `Boolean IsStateStable()`

- `Boolean IsRepoShow()`

- `Boolean IsNaviPanelShow()`

- `SandboxV2SquadPanelShowMode GetPanelShowMode()`

- `Void OpenWorkbenchDialog(Options)`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _HandleWorkbenchCallback(ValueBundle)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnBattleStart()`

- `Void _EventOnMakeDrink()`

- `Void <_EventOnBtnBack>b__18_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonSquadState : PopupFadeState, ISandboxV2SquadPanelContext, ICompDialogCallBack, IValueMsgReceiver
{
	private SandboxV2SquadGroupPanel _squadGroupPanelPrefab; // 0x70
	private Transform _charRepoContainer; // 0x78
	private SandboxV2SquadStartBattleView _startBattleView; // 0x80
	private RectTransform _backRt; // 0x88
	private Text _textActionCost; // 0x90
	public const Int32 MSG_START_BATTLE; // 0x0
	public const Int32 MSG_MAKE_DRINK; // 0x0
	private Boolean m_hasInited; // 0x98
	private String m_topicId; // 0xa0
	private SandboxV2DungeonSquadStateBean m_stateBean; // 0xa8
	private SandboxV2SquadGroupPanel m_squadGroupPanel; // 0xb0
	private OpenOption m_cachedOpenOption; // 0xb8
	private Int32 m_cachedDineCharInstId; // 0x110
	private Input m_cachedToolSelectInput; // 0x118
	private Int32 m_workbenchMakeDialogInst; // 0x148
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__EventOnBtnBack; // 0x18
	private static DelegateBridge __Hotfix0_EventOnBtnBack; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x30
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x38
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x40
	private static DelegateBridge __Hotfix0__OnJumpFromToolSelectState; // 0x48
	private static DelegateBridge __Hotfix0__OnJumpToToolSelectState; // 0x50
	private static DelegateBridge __Hotfix0__OnJumpFromCharSelectState; // 0x58
	private static DelegateBridge __Hotfix0__OnJumpToCharSelectState; // 0x60
	private static DelegateBridge __Hotfix0__OnJumpFromDineState; // 0x68
	private static DelegateBridge __Hotfix0__OnJumpToDineState; // 0x70
	private static DelegateBridge __Hotfix0_OpenCharSelectState; // 0x78
	private static DelegateBridge __Hotfix0_OpenDineState; // 0x80
	private static DelegateBridge __Hotfix0_OpenToolSelectState; // 0x88
	private static DelegateBridge __Hotfix0_GetBinderView; // 0x90
	private static DelegateBridge __Hotfix0_IsStateStable; // 0x98
	private static DelegateBridge __Hotfix0_IsRepoShow; // 0xa0
	private static DelegateBridge __Hotfix0_IsNaviPanelShow; // 0xa8
	private static DelegateBridge __Hotfix0_GetPanelShowMode; // 0xb0
	private static DelegateBridge __Hotfix0_OpenWorkbenchDialog; // 0xb8
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0xc0
	private static DelegateBridge __Hotfix0__HandleWorkbenchCallback; // 0xc8
	private static DelegateBridge __Hotfix0_OnMessage; // 0xd0
	private static DelegateBridge __Hotfix0__EventOnBattleStart; // 0xd8
	private static DelegateBridge __Hotfix0__EventOnMakeDrink; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8


	// RVA: 0x2543048 VA: 0x7594b5b048
	protected override Void OnEnter() { }
	// RVA: 0x25433a4 VA: 0x7594b5b3a4
	protected override Void OnResume() { }
	// RVA: 0x2543194 VA: 0x7594b5b194
	private Void _InitIfNot() { }
	// RVA: 0x2543484 VA: 0x7594b5b484
	private Void _EventOnBtnBack() { }
	// RVA: 0x254355c VA: 0x7594b5b55c
	public Void EventOnBtnBack() { }
	// RVA: 0x25435c4 VA: 0x7594b5b5c4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x254362c VA: 0x7594b5b62c
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x25436a4 VA: 0x7594b5b6a4
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2543908 VA: 0x7594b5b908
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2543b6c VA: 0x7594b5bb6c
	private Void _OnJumpFromToolSelectState(IStateBean stateBean) { }
	// RVA: 0x2543ca8 VA: 0x7594b5bca8
	private Void _OnJumpToToolSelectState(IStateBean stateBean) { }
	// RVA: 0x2543dac VA: 0x7594b5bdac
	private Void _OnJumpFromCharSelectState(IStateBean stateBean) { }
	// RVA: 0x2543efc VA: 0x7594b5befc
	private Void _OnJumpToCharSelectState(IStateBean stateBean) { }
	// RVA: 0x2544000 VA: 0x7594b5c000
	private Void _OnJumpFromDineState(IStateBean obj) { }
	// RVA: 0x2544088 VA: 0x7594b5c088
	private Void _OnJumpToDineState(IStateBean stateBean) { }
	// RVA: 0x2544168 VA: 0x7594b5c168
	public Void OpenCharSelectState(OpenOption option) { }
	// RVA: 0x25442ac VA: 0x7594b5c2ac
	public Void OpenDineState(Int32 charInstId) { }
	// RVA: 0x25443d0 VA: 0x7594b5c3d0
	public Void OpenToolSelectState(Input toolSelectInput) { }
	// RVA: 0x2544510 VA: 0x7594b5c510
	public DataBinder`1 GetBinderView() { }
	// RVA: 0x2544578 VA: 0x7594b5c578
	public Boolean IsStateStable() { }
	// RVA: 0x2544668 VA: 0x7594b5c668
	public Boolean IsRepoShow() { }
	// RVA: 0x25446cc VA: 0x7594b5c6cc
	public Boolean IsNaviPanelShow() { }
	// RVA: 0x2544734 VA: 0x7594b5c734
	public SandboxV2SquadPanelShowMode GetPanelShowMode() { }
	// RVA: 0x25447b8 VA: 0x7594b5c7b8
	public Void OpenWorkbenchDialog(Options options) { }
	// RVA: 0x2544a38 VA: 0x7594b5ca38
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x2544ae0 VA: 0x7594b5cae0
	private Void _HandleWorkbenchCallback(ValueBundle output) { }
	// RVA: 0x2544c18 VA: 0x7594b5cc18
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2544cdc VA: 0x7594b5ccdc
	private Void _EventOnBattleStart() { }
	// RVA: 0x2544ea0 VA: 0x7594b5cea0
	private Void _EventOnMakeDrink() { }
	// RVA: 0x2544f5c VA: 0x7594b5cf5c
	public Void .ctor() { }
	// RVA: 0x2545008 VA: 0x7594b5d008
	private Void <_EventOnBtnBack>b__18_0() { }
	// RVA: 0x2545018 VA: 0x7594b5d018
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2545020 VA: 0x7594b5d020
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2545028 VA: 0x7594b5d028
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2545030 VA: 0x7594b5d030
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x2545038 VA: 0x7594b5d038
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```