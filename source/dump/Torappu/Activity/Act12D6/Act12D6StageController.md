# Act12D6StageController

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Boolean m_isControllerReady`

- `Action <onRogueLikeEnd>k__BackingField`


## Properties

- `Action onRogueLikeEnd`


## Methods

- `Action get_onRogueLikeEnd()`

- `Void set_onRogueLikeEnd(Action)`

- `Boolean _CheckIfToShowGameEnd()`

- `IEnumerator _OpenGameEndCoroutine()`

- `IEnumerator _WaitForControllerReady()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`

- `Void <>xLuaBaseProxy_OnRewardTimeout()`

- `Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext)`

- `String <>xLuaBaseProxy_GetBGMSignal()`

- `IEnumerator <>xLuaBaseProxy_GetReadySignalForStagePage()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6StageController : ActivityStageController, IHotfixable
{
	private Boolean m_isControllerReady; // 0x60
	private Action <onRogueLikeEnd>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onRogueLikeEnd; // 0x0
	private static DelegateBridge __Hotfix0_set_onRogueLikeEnd; // 0x8
	private static DelegateBridge __Hotfix0_CreateBridge; // 0x10
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x18
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x20
	private static DelegateBridge __Hotfix0_OnRewardTimeout; // 0x28
	private static DelegateBridge __Hotfix0_OnStagePageResumed; // 0x30
	private static DelegateBridge __Hotfix0_GetBGMSignal; // 0x38
	private static DelegateBridge __Hotfix0_GetReadySignalForStagePage; // 0x40
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x48
	private static DelegateBridge __Hotfix0__CheckIfToShowGameEnd; // 0x50
	private static DelegateBridge __Hotfix0__OpenGameEndCoroutine; // 0x58
	private static DelegateBridge __Hotfix0__WaitForControllerReady; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Action onRogueLikeEnd { get; set; }

	// RVA: 0x346aed0 VA: 0x7595a82ed0
	public Action get_onRogueLikeEnd() { }
	// RVA: 0x346af38 VA: 0x7595a82f38
	public Void set_onRogueLikeEnd(Action value) { }
	// RVA: 0x346afbc VA: 0x7595a82fbc
	protected override ActivityStageBridge CreateBridge() { }
	// RVA: 0x346b05c VA: 0x7595a8305c
	protected override Void OnLoaded() { }
	// RVA: 0x346b1d0 VA: 0x7595a831d0
	protected override Void OnStageTimeout() { }
	// RVA: 0x346b364 VA: 0x7595a83364
	protected override Void OnRewardTimeout() { }
	// RVA: 0x346b4f8 VA: 0x7595a834f8
	protected override Void OnStagePageResumed(UIPageTransContext context) { }
	// RVA: 0x346b5a0 VA: 0x7595a835a0
	protected override String GetBGMSignal() { }
	// RVA: 0x346b71c VA: 0x7595a8371c
	public override IEnumerator GetReadySignalForStagePage() { }
	// RVA: 0x346b920 VA: 0x7595a83920
	protected override IEnumerator ShowCoroutine() { }
	// RVA: 0x346b7a0 VA: 0x7595a837a0
	private Boolean _CheckIfToShowGameEnd() { }
	// RVA: 0x346b9f4 VA: 0x7595a839f4
	private IEnumerator _OpenGameEndCoroutine() { }
	// RVA: 0x346b874 VA: 0x7595a83874
	private IEnumerator _WaitForControllerReady() { }
	// RVA: 0x346baf0 VA: 0x7595a83af0
	public Void .ctor() { }
	// RVA: 0x346bb60 VA: 0x7595a83b60
	private IEnumerator <>n__0() { }
	// RVA: 0x346bb68 VA: 0x7595a83b68
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x346bb70 VA: 0x7595a83b70
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
	// RVA: 0x346bb78 VA: 0x7595a83b78
	private Void <>xLuaBaseProxy_OnRewardTimeout() { }
	// RVA: 0x346bb80 VA: 0x7595a83b80
	private Void <>xLuaBaseProxy_OnStagePageResumed(UIPageTransContext P0) { }
	// RVA: 0x346bbb0 VA: 0x7595a83bb0
	private String <>xLuaBaseProxy_GetBGMSignal() { }
	// RVA: 0x346bbb8 VA: 0x7595a83bb8
	private IEnumerator <>xLuaBaseProxy_GetReadySignalForStagePage() { }
	// RVA: 0x346bbc0 VA: 0x7595a83bc0
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine() { }
}
```