# Act20sideCartShowState

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Transform _carCont`

- `Act20sideCarObject _carObj`

- `Image _coloredImage`

- `Single _scaleFloat`

- `Act20sideCarShowBtnHolder _btnHolder`

- `UICommonTrackPoint _trackPointDraw`

- `UICommonTrackPoint _trackPointVote`

- `UICommonTrackPoint _trackPointFunGame`

- `GameObject _panelNormal`

- `GameObject _panelRetro`

- `GameObject _panelHandBook`

- `TrackPointViewProperty m_trackPointDraw`

- `TrackPointViewProperty m_trackPointFunGame`

- `TrackPointViewProperty m_trackPointVote`

- `Act20sideCarObject m_carObj`

- `Boolean m_isRetro`

- `Boolean m_isInited`

- `Act20sideCartShowStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void OnSelectCompState()`

- `Void OnEntertainCompetitionState()`

- `Void OnVoteState()`

- `Void OnEnterMilestoneState()`

- `Void OnRender()`

- `Void OnCarDetailClick()`

- `Void <RegisterToDataListener>b__21_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCartShowState : State
{
	private Transform _carCont; // 0x50
	private Act20sideCarObject _carObj; // 0x58
	private List`1 _carObjList; // 0x60
	private Image _coloredImage; // 0x68
	private Single _scaleFloat; // 0x70
	private Act20sideCarShowBtnHolder _btnHolder; // 0x78
	private UICommonTrackPoint _trackPointDraw; // 0x80
	private UICommonTrackPoint _trackPointVote; // 0x88
	private UICommonTrackPoint _trackPointFunGame; // 0x90
	private GameObject _panelNormal; // 0x98
	private GameObject _panelRetro; // 0xa0
	private GameObject _panelHandBook; // 0xa8
	private TrackPointViewProperty m_trackPointDraw; // 0xb0
	private TrackPointViewProperty m_trackPointFunGame; // 0xb8
	private TrackPointViewProperty m_trackPointVote; // 0xc0
	private Act20sideCarObject m_carObj; // 0xc8
	private Boolean m_isRetro; // 0xd0
	private Boolean m_isInited; // 0xd1
	private Act20sideCartShowStateBean m_stateBean; // 0xd8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_OnSelectCompState; // 0x18
	private static DelegateBridge __Hotfix0_OnEntertainCompetitionState; // 0x20
	private static DelegateBridge __Hotfix0_OnVoteState; // 0x28
	private static DelegateBridge __Hotfix0_OnEnterMilestoneState; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0_OnResume; // 0x40
	private static DelegateBridge __Hotfix0_OnRender; // 0x48
	private static DelegateBridge __Hotfix0_OnCarDetailClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x32f1dfc VA: 0x7595909dfc
	private Void _InitIfNot() { }
	// RVA: 0x32f1f88 VA: 0x7595909f88
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32f1ff0 VA: 0x7595909ff0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x32f2168 VA: 0x759590a168
	public Void OnSelectCompState() { }
	// RVA: 0x32f2274 VA: 0x759590a274
	public Void OnEntertainCompetitionState() { }
	// RVA: 0x32f2380 VA: 0x759590a380
	public Void OnVoteState() { }
	// RVA: 0x32f2474 VA: 0x759590a474
	public Void OnEnterMilestoneState() { }
	// RVA: 0x32f2610 VA: 0x759590a610
	protected override Void OnEnter() { }
	// RVA: 0x32f2ae0 VA: 0x759590aae0
	protected override Void OnResume() { }
	// RVA: 0x32f27ac VA: 0x759590a7ac
	public Void OnRender() { }
	// RVA: 0x32f2b70 VA: 0x759590ab70
	public Void OnCarDetailClick() { }
	// RVA: 0x32f2c90 VA: 0x759590ac90
	public Void .ctor() { }
	// RVA: 0x32f2dd0 VA: 0x759590add0
	private Void <RegisterToDataListener>b__21_0(IStateBean stateBean) { }
	// RVA: 0x32f2e60 VA: 0x759590ae60
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x32f2e68 VA: 0x759590ae68
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x32f2e70 VA: 0x759590ae70
	private Void <>xLuaBaseProxy_OnResume() { }
}
```