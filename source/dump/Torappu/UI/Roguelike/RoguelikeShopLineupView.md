# RoguelikeShopLineupView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `LineupLayer _layer`

- `CanvasGroup _rootGroup`

- `LoopVerticalScrollRect _loopScrollRect`

- `RoguelikeShopGoodsLoopAdapter _goodsLoopAdapter`

- `RoguelikeShopLineupAddonView _addonView`

- `Boolean m_hasInited`

- `RoguelikeShopLineupControllerBindings m_controllerBindings`


## Properties

- `LineupLayer layer`


## Methods

- `LineupLayer get_layer()`

- `RoguelikeGameShopStatusEnum GetShopStatus()`

- `RoguelikeGameShopStatusEnum GetRivalStatus()`

- `Void Init()`

- `Single SetShow(Boolean, Boolean, RoguelikeGameShopStatusEnum)`

- `Void BindShopController(RoguelikeShopLineupControllerBindings)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeShopLineupView : DataBinder`1, IRoguelikeGameShopVisibility
{
	private LineupLayer _layer; // 0x20
	private CanvasGroup _rootGroup; // 0x28
	private LoopVerticalScrollRect _loopScrollRect; // 0x30
	private RoguelikeShopGoodsLoopAdapter _goodsLoopAdapter; // 0x38
	private RoguelikeShopLineupAddonView _addonView; // 0x40
	private Boolean m_hasInited; // 0x48
	private RoguelikeShopLineupControllerBindings m_controllerBindings; // 0x50
	private static DelegateBridge __Hotfix0_get_layer; // 0x0
	private static DelegateBridge __Hotfix0_GetShopStatus; // 0x8
	private static DelegateBridge __Hotfix0_GetRivalStatus; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_SetShow; // 0x28
	private static DelegateBridge __Hotfix0_BindShopController; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public LineupLayer layer { get; }

	// RVA: 0x2aeadac VA: 0x7595102dac
	public LineupLayer get_layer() { }
	// RVA: 0x2aeae14 VA: 0x7595102e14
	public RoguelikeGameShopStatusEnum GetShopStatus() { }
	// RVA: 0x2aeae94 VA: 0x7595102e94
	public RoguelikeGameShopStatusEnum GetRivalStatus() { }
	// RVA: 0x2aeaf10 VA: 0x7595102f10
	public override Void OnValueChanged(RoguelikeGameShopGoodsProperty property) { }
	// RVA: 0x2aeb004 VA: 0x7595103004
	public Void Init() { }
	// RVA: 0x2aeb07c VA: 0x759510307c
	public Single SetShow(Boolean isShow, Boolean fastMode, RoguelikeGameShopStatusEnum current) { }
	// RVA: 0x2aeb1dc VA: 0x75951031dc
	public Void BindShopController(RoguelikeShopLineupControllerBindings bindings) { }
	// RVA: 0x2aeb288 VA: 0x7595103288
	public Void .ctor() { }
}
```