# Act3D0CampSelectState

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `CanvasGroup _alphaHandler`

- `RectTransform _campSelectContainer`

- `Act3D0CampSelectView m_campSelectView`


## Methods

- `Void _OnCampSelected(Object)`

- `Void _InitCampSelectView()`

- `Void _OnCampSelectConfirmed(String)`

- `Void _OnCampResultConfirmed()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0CampSelectState : UIPopupState
{
	private const Single FADE_DURATION; // 0x0
	private CanvasGroup _alphaHandler; // 0x60
	private RectTransform _campSelectContainer; // 0x68
	private Act3D0CampSelectView m_campSelectView; // 0x70
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0__OnCampSelected; // 0x18
	private static DelegateBridge __Hotfix0__InitCampSelectView; // 0x20
	private static DelegateBridge __Hotfix0__OnCampSelectConfirmed; // 0x28
	private static DelegateBridge __Hotfix0__OnCampResultConfirmed; // 0x30
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x38
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x40
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x48
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x322c5bc VA: 0x75958445bc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x322c620 VA: 0x7595844620
	protected override Void OnEnter() { }
	// RVA: 0x322cb34 VA: 0x7595844b34
	protected override Void OnExit() { }
	// RVA: 0x322ccb4 VA: 0x7595844cb4
	private Void _OnCampSelected(Object _) { }
	// RVA: 0x322c810 VA: 0x7595844810
	private Void _InitCampSelectView() { }
	// RVA: 0x322cff4 VA: 0x7595844ff4
	private Void _OnCampSelectConfirmed(String campId) { }
	// RVA: 0x322d2bc VA: 0x75958452bc
	private Void _OnCampResultConfirmed() { }
	// RVA: 0x322d330 VA: 0x7595845330
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x322d4a8 VA: 0x75958454a8
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x322d5bc VA: 0x75958455bc
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x322d734 VA: 0x7595845734
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x322d85c VA: 0x759584585c
	public Void .ctor() { }
	// RVA: 0x322d8cc VA: 0x75958458cc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x322d8d4 VA: 0x75958458d4
	private Void <>xLuaBaseProxy_OnExit() { }
}
```