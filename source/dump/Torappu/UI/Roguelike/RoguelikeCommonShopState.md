# RoguelikeCommonShopState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _panelTopMenu`

- `UIGuidebookTrigger _guideBookTrigger`

- `RoguelikeCommonShopController _shopViewController`

- `Boolean m_inited`

- `RoguelikeShopStateBean m_stateBean`


## Methods

- `Void OnDestroy()`

- `Void _InitIfNot()`

- `Void _TriggerBGMSignal(String)`

- `Void _ClearBGM()`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <_InitIfNot>b__11_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCommonShopState : PopupFadeState
{
	private RectTransform _panelTopMenu; // 0x70
	private UIGuidebookTrigger _guideBookTrigger; // 0x78
	private RoguelikeCommonShopController _shopViewController; // 0x80
	private Boolean m_inited; // 0x88
	private RoguelikeShopStateBean m_stateBean; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__TriggerBGMSignal; // 0x38
	private static DelegateBridge __Hotfix0__ClearBGM; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2adc0f0 VA: 0x75950f40f0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2adc158 VA: 0x75950f4158
	protected override Void OnEnter() { }
	// RVA: 0x2adc574 VA: 0x75950f4574
	protected override Void OnResume() { }
	// RVA: 0x2adc68c VA: 0x75950f468c
	protected override Void OnExit() { }
	// RVA: 0x2adc80c VA: 0x75950f480c
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2adc9a0 VA: 0x75950f49a0
	private Void OnDestroy() { }
	// RVA: 0x2adc328 VA: 0x75950f4328
	private Void _InitIfNot() { }
	// RVA: 0x2adc40c VA: 0x75950f440c
	private Void _TriggerBGMSignal(String topicId) { }
	// RVA: 0x2adc760 VA: 0x75950f4760
	private Void _ClearBGM() { }
	// RVA: 0x2adca08 VA: 0x75950f4a08
	public Void .ctor() { }
	// RVA: 0x2adcab8 VA: 0x75950f4ab8
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x2adcae0 VA: 0x75950f4ae0
	private Void <_InitIfNot>b__11_0() { }
	// RVA: 0x2adcb64 VA: 0x75950f4b64
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2adcb6c VA: 0x75950f4b6c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2adcb74 VA: 0x75950f4b74
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2adcb7c VA: 0x75950f4b7c
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
}
```