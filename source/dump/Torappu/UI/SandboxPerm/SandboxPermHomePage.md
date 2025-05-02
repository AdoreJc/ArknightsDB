# SandboxPermHomePage

**Namespace:** `Torappu.UI.SandboxPerm`


## Fields

- `RectTransform _topMenuContainer`

- `CanvasGroup _canvasBlackLoading`

- `CanvasGroup _canvasTopLayer`

- `CanvasGroup _canvasHomeState`

- `FadeSwitchTween m_blackLoadingTween`

- `String m_topicId`


## Properties

- `FadeSwitchTween blackLoadingSwitch`

- `String topicId`

- `Boolean backFromBattle`


## Methods

- `FadeSwitchTween get_blackLoadingSwitch()`

- `String get_topicId()`

- `Boolean get_backFromBattle()`

- `Void _TriggerBGMSignal()`

- `Int64 _GetBGMInstId()`

- `Void _ClearBGM()`

- `Void _EventBackClick()`

- `IEnumerator _TopicEnterShowEffect()`

- `Boolean _CheckIfUseFastEnterAndMarkTrace()`

- `IEnumerator <>n__0(Boolean)`

- `IEnumerator <>n__1(Boolean)`

- `Void <_TopicEnterShowEffect>b__24_0()`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm
public class SandboxPermHomePage : StateEnginePage
{
	private const Single DUR_BLACK_LOADING_FADEIN; // 0x0
	private RectTransform _topMenuContainer; // 0xe8
	private CanvasGroup _canvasBlackLoading; // 0xf0
	private CanvasGroup _canvasTopLayer; // 0xf8
	private CanvasGroup _canvasHomeState; // 0x100
	private FadeSwitchTween m_blackLoadingTween; // 0x108
	private String m_topicId; // 0x110
	private static DelegateBridge __Hotfix0_get_blackLoadingSwitch; // 0x0
	private static DelegateBridge __Hotfix0_get_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_backFromBattle; // 0x10
	private static DelegateBridge __Hotfix0_OnStart; // 0x18
	private static DelegateBridge __Hotfix0_OnCreate; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x30
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x38
	private static DelegateBridge __Hotfix0__TriggerBGMSignal; // 0x40
	private static DelegateBridge __Hotfix0__GetBGMInstId; // 0x48
	private static DelegateBridge __Hotfix0__ClearBGM; // 0x50
	private static DelegateBridge __Hotfix0__EventBackClick; // 0x58
	private static DelegateBridge __Hotfix0__TopicEnterShowEffect; // 0x60
	private static DelegateBridge __Hotfix0__CheckIfUseFastEnterAndMarkTrace; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	protected FadeSwitchTween blackLoadingSwitch { get; }
	public String topicId { get; }
	public Boolean backFromBattle { get; }

	// RVA: 0x247bfa0 VA: 0x7594a93fa0
	protected FadeSwitchTween get_blackLoadingSwitch() { }
	// RVA: 0x247c07c VA: 0x7594a9407c
	public String get_topicId() { }
	// RVA: 0x247c150 VA: 0x7594a94150
	public Boolean get_backFromBattle() { }
	// RVA: 0x247c1e4 VA: 0x7594a941e4
	protected override Void OnStart() { }
	// RVA: 0x247c3b8 VA: 0x7594a943b8
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x247c624 VA: 0x7594a94624
	protected override Void OnDestroy() { }
	// RVA: 0x247c740 VA: 0x7594a94740
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x247c830 VA: 0x7594a94830
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x247c270 VA: 0x7594a94270
	private Void _TriggerBGMSignal() { }
	// RVA: 0x247c920 VA: 0x7594a94920
	private Int64 _GetBGMInstId() { }
	// RVA: 0x247c698 VA: 0x7594a94698
	private Void _ClearBGM() { }
	// RVA: 0x247c994 VA: 0x7594a94994
	private Void _EventBackClick() { }
	// RVA: 0x247cc1c VA: 0x7594a94c1c
	private IEnumerator _TopicEnterShowEffect() { }
	// RVA: 0x247ccf0 VA: 0x7594a94cf0
	private Boolean _CheckIfUseFastEnterAndMarkTrace() { }
	// RVA: 0x247cd90 VA: 0x7594a94d90
	public Void .ctor() { }
	// RVA: 0x247ce38 VA: 0x7594a94e38
	private IEnumerator <>n__0(Boolean isFromStack) { }
	// RVA: 0x247ce44 VA: 0x7594a94e44
	private IEnumerator <>n__1(Boolean isIntoStack) { }
	// RVA: 0x247ce50 VA: 0x7594a94e50
	private Void <_TopicEnterShowEffect>b__24_0() { }
	// RVA: 0x247ce70 VA: 0x7594a94e70
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x247ce78 VA: 0x7594a94e78
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x247ce80 VA: 0x7594a94e80
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x247ce88 VA: 0x7594a94e88
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x247ce94 VA: 0x7594a94e94
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```