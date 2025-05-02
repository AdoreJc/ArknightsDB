# RoguelikeShopStatusView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _interactGroup`

- `Boolean m_initRender`

- `Single m_maxHideTime`

- `Single m_maxShowTime`

- `Tween m_delayedShow`

- `Single m_delayTime`

- `Tween m_delayedInteract`


## Properties

- `Boolean interactable`


## Methods

- `Boolean get_interactable()`

- `Void InitPanels(List`1)`

- `Void Init()`

- `Void _UpdateView(RoguelikeGameShopStatusEnum, Boolean)`

- `Void _StopPossibleTweens()`

- `Void _TestPanelsAndHideIfNeed(RoguelikeGameShopStatusEnum, Boolean)`

- `Void _ShowPanelsOrDelayIfNeed(RoguelikeGameShopStatusEnum, Boolean)`

- `Single _CollectDelayTimeForPanel(IRoguelikeGameShopVisibility)`

- `Void _GenerateDalayTweens(RoguelikeGameShopStatusEnum, Boolean)`

- `Void _GenerateInteractTween()`

- `Void <_GenerateInteractTween>b__24_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeShopStatusView : DataBinder`1
{
	private const Single INTERACT_CHECK_INTERVAL; // 0x0
	private CanvasGroup _interactGroup; // 0x20
	private readonly List`1 m_viewList; // 0x28
	private Boolean m_initRender; // 0x30
	private readonly List`1 m_showViewList; // 0x38
	private readonly Dictionary`2 m_hideViewDict; // 0x40
	private Single m_maxHideTime; // 0x48
	private Single m_maxShowTime; // 0x4c
	private readonly List`1 m_delayedShowItemList; // 0x50
	private Tween m_delayedShow; // 0x58
	private Single m_delayTime; // 0x60
	private Tween m_delayedInteract; // 0x68
	private static DelegateBridge __Hotfix0_get_interactable; // 0x0
	private static DelegateBridge __Hotfix0_InitPanels; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__UpdateView; // 0x20
	private static DelegateBridge __Hotfix0__StopPossibleTweens; // 0x28
	private static DelegateBridge __Hotfix0__TestPanelsAndHideIfNeed; // 0x30
	private static DelegateBridge __Hotfix0__ShowPanelsOrDelayIfNeed; // 0x38
	private static DelegateBridge __Hotfix0__CollectDelayTimeForPanel; // 0x40
	private static DelegateBridge __Hotfix0__GenerateDalayTweens; // 0x48
	private static DelegateBridge __Hotfix0__GenerateInteractTween; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Boolean interactable { get; }

	// RVA: 0x2aed54c VA: 0x759510554c
	public Boolean get_interactable() { }
	// RVA: 0x2aed5c0 VA: 0x75951055c0
	public Void InitPanels(List`1 viewList) { }
	// RVA: 0x2aed778 VA: 0x7595105778
	public Void Init() { }
	// RVA: 0x2aed7e4 VA: 0x75951057e4
	public override Void OnValueChanged(RoguelikeGameShopStatusProperty property) { }
	// RVA: 0x2aed8a4 VA: 0x75951058a4
	private Void _UpdateView(RoguelikeGameShopStatusEnum shopStatus, Boolean isFastMode) { }
	// RVA: 0x2aed9f4 VA: 0x75951059f4
	private Void _StopPossibleTweens() { }
	// RVA: 0x2aedaa8 VA: 0x7595105aa8
	private Void _TestPanelsAndHideIfNeed(RoguelikeGameShopStatusEnum shopStatus, Boolean isFastMode) { }
	// RVA: 0x2aedda8 VA: 0x7595105da8
	private Void _ShowPanelsOrDelayIfNeed(RoguelikeGameShopStatusEnum shopStatus, Boolean isFastMode) { }
	// RVA: 0x2aee484 VA: 0x7595106484
	private Single _CollectDelayTimeForPanel(IRoguelikeGameShopVisibility panel) { }
	// RVA: 0x2aee058 VA: 0x7595106058
	private Void _GenerateDalayTweens(RoguelikeGameShopStatusEnum shopStatus, Boolean isFastMode) { }
	// RVA: 0x2aee7a8 VA: 0x75951067a8
	private Void _GenerateInteractTween() { }
	// RVA: 0x2aee950 VA: 0x7595106950
	public Void .ctor() { }
	// RVA: 0x2aeeafc VA: 0x7595106afc
	private Void <_GenerateInteractTween>b__24_0() { }
}
```