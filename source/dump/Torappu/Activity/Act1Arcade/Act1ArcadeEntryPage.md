# Act1ArcadeEntryPage

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `RectTransform _commonDlgContainer`

- `CanvasGroup _fisheyeRootCanvas`

- `CanvasGroup _commonRootCanvas`

- `Act1ArcadeComponentHolder m_componentHolder`

- `DataBundle m_savedInst`

- `UICompDialogMgr m_commonDlgMgr`

- `Act1ArcadeStateViewStatusComp m_statusViewComp`

- `OnStateChangeListener m_stateChangeListener`


## Properties

- `String actId`

- `DataBundle savedInst`

- `UICompDialogMgr commonDlgMgr`

- `Act1ArcadeStateViewStatusComp statusViewComp`


## Methods

- `String get_actId()`

- `DataBundle get_savedInst()`

- `UICompDialogMgr get_commonDlgMgr()`

- `Act1ArcadeStateViewStatusComp get_statusViewComp()`

- `Void _OnRouteToState(Type)`

- `Void _OnStatePreResume(Type, Boolean)`

- `Void _OnStateResume(Type, Boolean)`

- `Void _TriggerBGMSignal()`

- `Void _SetPageShow(Boolean)`

- `IEnumerator <>n__0()`

- `Void <OnStateEngineReady>b__22_0(Type, Type, Additions)`

- `Void <OnStateEngineReady>b__22_1(Type, Boolean, Additions)`

- `Void <OnStateEngineReady>b__22_2(Type, Boolean, Additions)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`

- `Void <>xLuaBaseProxy_OnPageRouted()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `Void <>xLuaBaseProxy_OnStateEngineReady(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeEntryPage : StateEnginePage
{
	private RectTransform _commonDlgContainer; // 0xe8
	private CanvasGroup _fisheyeRootCanvas; // 0xf0
	private CanvasGroup _commonRootCanvas; // 0xf8
	private Act1ArcadeComponentHolder m_componentHolder; // 0x100
	private DataBundle m_savedInst; // 0x108
	private UICompDialogMgr m_commonDlgMgr; // 0x110
	private Act1ArcadeStateViewStatusComp m_statusViewComp; // 0x118
	private OnStateChangeListener m_stateChangeListener; // 0x120
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_savedInst; // 0x8
	private static DelegateBridge __Hotfix0_get_commonDlgMgr; // 0x10
	private static DelegateBridge __Hotfix0_get_statusViewComp; // 0x18
	private static DelegateBridge __Hotfix0_OnCreate; // 0x20
	private static DelegateBridge __Hotfix0_OnStart; // 0x28
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x30
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x38
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x40
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x48
	private static DelegateBridge __Hotfix0_OnStateEngineReady; // 0x50
	private static DelegateBridge __Hotfix0__OnRouteToState; // 0x58
	private static DelegateBridge __Hotfix0__OnStatePreResume; // 0x60
	private static DelegateBridge __Hotfix0__OnStateResume; // 0x68
	private static DelegateBridge __Hotfix0__TriggerBGMSignal; // 0x70
	private static DelegateBridge __Hotfix0__SetPageShow; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public String actId { get; }
	public DataBundle savedInst { get; }
	public UICompDialogMgr commonDlgMgr { get; }
	public Act1ArcadeStateViewStatusComp statusViewComp { get; }

	// RVA: 0x33ec050 VA: 0x7595a04050
	public String get_actId() { }
	// RVA: 0x33ec114 VA: 0x7595a04114
	public DataBundle get_savedInst() { }
	// RVA: 0x33ec17c VA: 0x7595a0417c
	public UICompDialogMgr get_commonDlgMgr() { }
	// RVA: 0x33ec1e4 VA: 0x7595a041e4
	public Act1ArcadeStateViewStatusComp get_statusViewComp() { }
	// RVA: 0x33ec2bc VA: 0x7595a042bc
	protected override Void OnCreate(DataBundle dataBundle) { }
	// RVA: 0x33ec394 VA: 0x7595a04394
	protected override Void OnStart() { }
	// RVA: 0x33ec69c VA: 0x7595a0469c
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x33ec78c VA: 0x7595a0478c
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x33ec87c VA: 0x7595a0487c
	protected override Void OnPageRouted() { }
	// RVA: 0x33eca54 VA: 0x7595a04a54
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x33ecb28 VA: 0x7595a04b28
	protected override Void OnStateEngineReady(Boolean isPageFromStack) { }
	// RVA: 0x33ecdb4 VA: 0x7595a04db4
	private Void _OnRouteToState(Type targetStateType) { }
	// RVA: 0x33ece40 VA: 0x7595a04e40
	private Void _OnStatePreResume(Type targetStateType, Boolean isFromStack) { }
	// RVA: 0x33eced8 VA: 0x7595a04ed8
	private Void _OnStateResume(Type targetStateType, Boolean isFromStack) { }
	// RVA: 0x33ec508 VA: 0x7595a04508
	private Void _TriggerBGMSignal() { }
	// RVA: 0x33ed284 VA: 0x7595a05284
	private Void _SetPageShow(Boolean isShow) { }
	// RVA: 0x33ed340 VA: 0x7595a05340
	public Void .ctor() { }
	// RVA: 0x33ed3b0 VA: 0x7595a053b0
	private IEnumerator <>n__0() { }
	// RVA: 0x33ed3b8 VA: 0x7595a053b8
	private Void <OnStateEngineReady>b__22_0(Type from, Type to, Additions add) { }
	// RVA: 0x33ed3c0 VA: 0x7595a053c0
	private Void <OnStateEngineReady>b__22_1(Type stateType, Boolean isStateFromStack, Additions add) { }
	// RVA: 0x33ed3c8 VA: 0x7595a053c8
	private Void <OnStateEngineReady>b__22_2(Type stateType, Boolean isStateFromStack, Additions add) { }
	// RVA: 0x33ed3d0 VA: 0x7595a053d0
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x33ed3d8 VA: 0x7595a053d8
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x33ed3e0 VA: 0x7595a053e0
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x33ed3ec VA: 0x7595a053ec
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
	// RVA: 0x33ed3f8 VA: 0x7595a053f8
	private Void <>xLuaBaseProxy_OnPageRouted() { }
	// RVA: 0x33ed400 VA: 0x7595a05400
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x33ed408 VA: 0x7595a05408
	private Void <>xLuaBaseProxy_OnStateEngineReady(Boolean P0) { }
}
```