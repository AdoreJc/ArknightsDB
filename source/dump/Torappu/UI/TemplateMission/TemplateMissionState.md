# TemplateMissionState

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `RectTransform _viewContainer`

- `TemplateMissionStateBean m_missionStateBean`

- `AbstractTemplateMissionViewController m_missionController`


## Methods

- `Void EventOnBackClicked()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _InitController(TemplateMissionInputParam)`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionState : PopupFadeState, IValueMsgReceiver
{
	private RectTransform _viewContainer; // 0x70
	private TemplateMissionStateBean m_missionStateBean; // 0x78
	private AbstractTemplateMissionViewController m_missionController; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__InitController; // 0x28
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x236c358 VA: 0x7594984358
	public override IStateBean GetCacheBean() { }
	// RVA: 0x236c3c0 VA: 0x75949843c0
	protected override Void OnEnter() { }
	// RVA: 0x236c740 VA: 0x7594984740
	protected override Void OnResume() { }
	// RVA: 0x236c80c VA: 0x759498480c
	public Void EventOnBackClicked() { }
	// RVA: 0x236c968 VA: 0x7594984968
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x236c560 VA: 0x7594984560
	private Void _InitController(TemplateMissionInputParam inputParam) { }
	// RVA: 0x236cae4 VA: 0x7594984ae4
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x236cc78 VA: 0x7594984c78
	public Void .ctor() { }
	// RVA: 0x236cdd0 VA: 0x7594984dd0
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x236cdf8 VA: 0x7594984df8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x236ce00 VA: 0x7594984e00
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x236ce08 VA: 0x7594984e08
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```