# VecBreakDefenseDefaultState

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `RectTransform _topMenuParent`

- `VecBreakDefenseView _view`

- `UIGuidebookTrigger _guidebookTrigger`

- `VecBreakDefensePage m_page`

- `VecBreakDefenseProp m_prop`

- `Int32 m_dialogInst`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnBtnBack()`

- `Void _OpenGuidebook(Story)`

- `Void _OnClickEnemy(String)`

- `Void _OnClickMap(String)`

- `Void _OnClickRetreat(String)`

- `Void _RetreatDefend(String)`

- `Void _OnClickEnterStage(String)`

- `Void <_RetreatDefend>b__19_0(VecBreakSetDefendResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakDefenseDefaultState : State, IValueMsgReceiver
{
	private RectTransform _topMenuParent; // 0x50
	private VecBreakDefenseView _view; // 0x58
	private UIGuidebookTrigger _guidebookTrigger; // 0x60
	public const Int32 MSG_ENEMY_CLICK; // 0x0
	public const Int32 MSG_RETREAT_CLICK; // 0x0
	public const Int32 MSG_ENTER_STAGE_CLICK; // 0x0
	public const Int32 MSG_MAP_CLICK; // 0x0
	private VecBreakDefensePage m_page; // 0x68
	private VecBreakDefenseProp m_prop; // 0x70
	private Int32 m_dialogInst; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnMessage; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__EventOnBtnBack; // 0x20
	private static DelegateBridge __Hotfix0__OpenGuidebook; // 0x28
	private static DelegateBridge __Hotfix0__OnClickEnemy; // 0x30
	private static DelegateBridge __Hotfix0__OnClickMap; // 0x38
	private static DelegateBridge __Hotfix0__OnClickRetreat; // 0x40
	private static DelegateBridge __Hotfix0__RetreatDefend; // 0x48
	private static DelegateBridge __Hotfix0__OnClickEnterStage; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x22ca430 VA: 0x75948e2430
	public override IStateBean GetCacheBean() { }
	// RVA: 0x22ca494 VA: 0x75948e2494
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x22caed4 VA: 0x75948e2ed4
	protected override Void OnEnter() { }
	// RVA: 0x22cb208 VA: 0x75948e3208
	protected override Void OnResume() { }
	// RVA: 0x22cb2cc VA: 0x75948e32cc
	private Void _EventOnBtnBack() { }
	// RVA: 0x22cb3ac VA: 0x75948e33ac
	private Void _OpenGuidebook(Story story) { }
	// RVA: 0x22ca5ac VA: 0x75948e25ac
	private Void _OnClickEnemy(String stageId) { }
	// RVA: 0x22cacbc VA: 0x75948e2cbc
	private Void _OnClickMap(String stageId) { }
	// RVA: 0x22ca758 VA: 0x75948e2758
	private Void _OnClickRetreat(String stageId) { }
	// RVA: 0x22cb5c4 VA: 0x75948e35c4
	private Void _RetreatDefend(String stageId) { }
	// RVA: 0x22ca9b4 VA: 0x75948e29b4
	private Void _OnClickEnterStage(String stageId) { }
	// RVA: 0x22cb89c VA: 0x75948e389c
	public Void .ctor() { }
	// RVA: 0x22cb90c VA: 0x75948e390c
	private Void <_RetreatDefend>b__19_0(VecBreakSetDefendResponse response) { }
	// RVA: 0x22cbb80 VA: 0x75948e3b80
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x22cbb88 VA: 0x75948e3b88
	private Void <>xLuaBaseProxy_OnResume() { }
}
```