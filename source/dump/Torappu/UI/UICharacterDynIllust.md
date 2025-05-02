# UICharacterDynIllust

**Namespace:** `Torappu.UI`


## Fields

- `Single CHAR_INFO_SPREAD_PANEL_ZOOM_MAX`

- `Single DYN_ILLUST_INIT_SECONDS`

- `IllustHandler m_handler`

- `Tweener m_fadeTweener`

- `DynIllustView m_view`

- `State m_state`

- `ActionTimer m_spIdleTimer`

- `EventTrigger m_onClickTrigger`

- `ClickOption m_onClickOption`

- `AnimationOption m_animOption`

- `String <illustId>k__BackingField`


## Methods

- `Void Init(IllustHandler, String, DynIllustView)`

- `Void _EventOnClickEvent()`

- `Void _UpdateState()`

- `Void _ChangeState(State)`

- `Boolean _EnsureViewInst()`

- `Void _ResetSpecialIdleTimer(SPActionType)`

- `Void _OnActionJustActivated(DynIllustAction)`

- `Void _OnActionInteract()`

- `Void _OnActionSpecialIdle()`

- `Void _OnActionStart()`

- `Void <RegisterClick>b__48_0(BaseEventData)`

- `Void <>xLuaBaseProxy_OnEnable()`

- `Void <>xLuaBaseProxy_OnDisable()`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `Void <>xLuaBaseProxy_OnTick()`

- `Void <>xLuaBaseProxy_OnActivated()`

- `Void <>xLuaBaseProxy_OnDeactivated()`

- `Void <>xLuaBaseProxy_RegisterClick(ClickOption)`

- `Void <>xLuaBaseProxy_PlayInteraction()`

- `Void <>xLuaBaseProxy_PlaySpecialManually()`

- `Void <>xLuaBaseProxy_PlayStart()`

- `Void <>xLuaBaseProxy_SetAnimationOption(AnimationOption)`

- `Boolean <>xLuaBaseProxy_IsPlayingInteraction()`

- `Boolean <>xLuaBaseProxy_IsPlayingStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterDynIllust : UICharacterIllust
{
	private Single CHAR_INFO_SPREAD_PANEL_ZOOM_MAX; // 0x18
	private Single DYN_ILLUST_INIT_SECONDS; // 0x1c
	private ListDict`2 SP_IDLE_TIME; // 0x20
	private IllustHandler m_handler; // 0x28
	private Tweener m_fadeTweener; // 0x30
	private DynIllustView m_view; // 0x38
	private State m_state; // 0x40
	private ActionTimer m_spIdleTimer; // 0x44
	private EventTrigger m_onClickTrigger; // 0x58
	private ClickOption m_onClickOption; // 0x60
	private AnimationOption m_animOption; // 0x70
	private Graphic[] m_graphicArray; // 0x78
	private String <illustId>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_illustId; // 0x0
	private static DelegateBridge __Hotfix0_set_illustId; // 0x8
	private static DelegateBridge __Hotfix0_get_isDynamic; // 0x10
	private static DelegateBridge __Hotfix0_get_isActiveIllust; // 0x18
	private static DelegateBridge __Hotfix0_get_rectTransform; // 0x20
	private static DelegateBridge __Hotfix0_get_mainGraphic; // 0x28
	private static DelegateBridge __Hotfix0_get_raycastTarget; // 0x30
	private static DelegateBridge __Hotfix0_set_raycastTarget; // 0x38
	private static DelegateBridge __Hotfix0_get_color; // 0x40
	private static DelegateBridge __Hotfix0_set_color; // 0x48
	private static DelegateBridge __Hotfix0_get_alpha; // 0x50
	private static DelegateBridge __Hotfix0_get_mainTexture; // 0x58
	private static DelegateBridge __Hotfix0_get_rawSize; // 0x60
	private static DelegateBridge __Hotfix0_get_graphics; // 0x68
	private static DelegateBridge __Hotfix0_OnEnable; // 0x70
	private static DelegateBridge __Hotfix0_OnDisable; // 0x78
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x80
	private static DelegateBridge __Hotfix0_OnTick; // 0x88
	private static DelegateBridge __Hotfix0_OnActivated; // 0x90
	private static DelegateBridge __Hotfix0_OnDeactivated; // 0x98
	private static DelegateBridge __Hotfix0_Init; // 0xa0
	private static DelegateBridge __Hotfix0_RegisterClick; // 0xa8
	private static DelegateBridge __Hotfix0__EventOnClickEvent; // 0xb0
	private static DelegateBridge __Hotfix0_Activate; // 0xb8
	private static DelegateBridge __Hotfix0_SetAlpha; // 0xc0
	private static DelegateBridge __Hotfix0_DOFade; // 0xc8
	private static DelegateBridge __Hotfix0_ApplySkinOffset; // 0xd0
	private static DelegateBridge __Hotfix0_GetCharInfoSpreadPanelZoomMax; // 0xd8
	private static DelegateBridge __Hotfix0_PlayInteraction; // 0xe0
	private static DelegateBridge __Hotfix0_PlaySpecialManually; // 0xe8
	private static DelegateBridge __Hotfix0_PlayStart; // 0xf0
	private static DelegateBridge __Hotfix0_SetAnimationOption; // 0xf8
	private static DelegateBridge __Hotfix0_IsPlayingInteraction; // 0x100
	private static DelegateBridge __Hotfix0_IsPlayingStart; // 0x108
	private static DelegateBridge __Hotfix0_GetMainMaterial; // 0x110
	private static DelegateBridge __Hotfix0_SetMainMaterial; // 0x118
	private static DelegateBridge __Hotfix0__UpdateState; // 0x120
	private static DelegateBridge __Hotfix0__ChangeState; // 0x128
	private static DelegateBridge __Hotfix0__EnsureViewInst; // 0x130
	private static DelegateBridge __Hotfix0__ResetSpecialIdleTimer; // 0x138
	private static DelegateBridge __Hotfix0__UniformSPActionTime; // 0x140
	private static DelegateBridge __Hotfix0__OnActionJustActivated; // 0x148
	private static DelegateBridge __Hotfix0__OnActionInteract; // 0x150
	private static DelegateBridge __Hotfix0__OnActionSpecialIdle; // 0x158
	private static DelegateBridge __Hotfix0__OnActionStart; // 0x160
	private static DelegateBridge _c__Hotfix0_ctor; // 0x168

	public override String illustId { get; set; }
	public override Boolean isDynamic { get; }
	public override Boolean isActiveIllust { get; }
	public override RectTransform rectTransform { get; }
	protected override Graphic mainGraphic { get; }
	public override Boolean raycastTarget { get; set; }
	public override Color color { get; set; }
	public override Single alpha { get; }
	public override Texture mainTexture { get; }
	public override Vector2 rawSize { get; }
	public override IList`1 graphics { get; }

	// RVA: 0x212b65c VA: 0x759474365c
	public override String get_illustId() { }
	// RVA: 0x212b6c4 VA: 0x75947436c4
	protected override Void set_illustId(String value) { }
	// RVA: 0x212b748 VA: 0x7594743748
	public override Boolean get_isDynamic() { }
	// RVA: 0x212b7b0 VA: 0x75947437b0
	public override Boolean get_isActiveIllust() { }
	// RVA: 0x212b828 VA: 0x7594743828
	public override RectTransform get_rectTransform() { }
	// RVA: 0x212b89c VA: 0x759474389c
	protected override Graphic get_mainGraphic() { }
	// RVA: 0x212b910 VA: 0x7594743910
	public override Boolean get_raycastTarget() { }
	// RVA: 0x212b99c VA: 0x759474399c
	public override Void set_raycastTarget(Boolean value) { }
	// RVA: 0x212ba40 VA: 0x7594743a40
	public override Color get_color() { }
	// RVA: 0x212bac4 VA: 0x7594743ac4
	public override Void set_color(Color value) { }
	// RVA: 0x212bb90 VA: 0x7594743b90
	public override Single get_alpha() { }
	// RVA: 0x212bc08 VA: 0x7594743c08
	public override Texture get_mainTexture() { }
	// RVA: 0x212bc8c VA: 0x7594743c8c
	public override Vector2 get_rawSize() { }
	// RVA: 0x212bd84 VA: 0x7594743d84
	public override IList`1 get_graphics() { }
	// RVA: 0x212be80 VA: 0x7594743e80
	protected override Void OnEnable() { }
	// RVA: 0x212bf68 VA: 0x7594743f68
	protected override Void OnDisable() { }
	// RVA: 0x212c050 VA: 0x7594744050
	protected override Void OnDestroy() { }
	// RVA: 0x212c13c VA: 0x759474413c
	public override Void OnTick() { }
	// RVA: 0x212c36c VA: 0x759474436c
	public override Void OnActivated() { }
	// RVA: 0x212c4c8 VA: 0x75947444c8
	public override Void OnDeactivated() { }
	// RVA: 0x212c534 VA: 0x7594744534
	public Void Init(IllustHandler handler, String illustId, DynIllustView dynamicIllust) { }
	// RVA: 0x212c620 VA: 0x7594744620
	public override Void RegisterClick(ClickOption clickOption) { }
	// RVA: 0x212c880 VA: 0x7594744880
	private Void _EventOnClickEvent() { }
	// RVA: 0x212c920 VA: 0x7594744920
	public override Void Activate(Boolean fastMode) { }
	// RVA: 0x212c9d0 VA: 0x75947449d0
	public override Void SetAlpha(Single alpha) { }
	// RVA: 0x212ca60 VA: 0x7594744a60
	public override Tween DOFade(Single endValue, Single duration) { }
	// RVA: 0x212cb4c VA: 0x7594744b4c
	public override Void ApplySkinOffset() { }
	// RVA: 0x212cbc4 VA: 0x7594744bc4
	public override Single GetCharInfoSpreadPanelZoomMax() { }
	// RVA: 0x212cc2c VA: 0x7594744c2c
	public override Void PlayInteraction() { }
	// RVA: 0x212cdb0 VA: 0x7594744db0
	public override Void PlaySpecialManually() { }
	// RVA: 0x212cef0 VA: 0x7594744ef0
	public override Void PlayStart() { }
	// RVA: 0x212cfa8 VA: 0x7594744fa8
	public override Void SetAnimationOption(AnimationOption animOption) { }
	// RVA: 0x212d024 VA: 0x7594745024
	public override Boolean IsPlayingInteraction() { }
	// RVA: 0x212d094 VA: 0x7594745094
	public override Boolean IsPlayingStart() { }
	// RVA: 0x212d104 VA: 0x7594745104
	public override Material GetMainMaterial() { }
	// RVA: 0x212d188 VA: 0x7594745188
	public override Void SetMainMaterial(Material mat) { }
	// RVA: 0x212c1a4 VA: 0x75947441a4
	private Void _UpdateState() { }
	// RVA: 0x212c3ec VA: 0x75947443ec
	private Void _ChangeState(State state) { }
	// RVA: 0x212cce0 VA: 0x7594744ce0
	private Boolean _EnsureViewInst() { }
	// RVA: 0x212d478 VA: 0x7594745478
	private Void _ResetSpecialIdleTimer(SPActionType actionType) { }
	// RVA: 0x212d69c VA: 0x759474569c
	private static KeyValuePair`2 _UniformSPActionTime(KeyValuePair`2 timeRange, DynIllust illust) { }
	// RVA: 0x212d200 VA: 0x7594745200
	private Void _OnActionJustActivated(DynIllustAction curAction) { }
	// RVA: 0x212d3a0 VA: 0x75947453a0
	private Void _OnActionInteract() { }
	// RVA: 0x212ce84 VA: 0x7594744e84
	private Void _OnActionSpecialIdle() { }
	// RVA: 0x212d40c VA: 0x759474540c
	private Void _OnActionStart() { }
	// RVA: 0x212d960 VA: 0x7594745960
	public Void .ctor() { }
	// RVA: 0x212db24 VA: 0x7594745b24
	private Void <RegisterClick>b__48_0(BaseEventData data) { }
	// RVA: 0x212db28 VA: 0x7594745b28
	private Void <>xLuaBaseProxy_OnEnable() { }
	// RVA: 0x212db2c VA: 0x7594745b2c
	private Void <>xLuaBaseProxy_OnDisable() { }
	// RVA: 0x212db30 VA: 0x7594745b30
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x212db34 VA: 0x7594745b34
	private Void <>xLuaBaseProxy_OnTick() { }
	// RVA: 0x212db9c VA: 0x7594745b9c
	private Void <>xLuaBaseProxy_OnActivated() { }
	// RVA: 0x212dc04 VA: 0x7594745c04
	private Void <>xLuaBaseProxy_OnDeactivated() { }
	// RVA: 0x212dc6c VA: 0x7594745c6c
	private Void <>xLuaBaseProxy_RegisterClick(ClickOption P0) { }
	// RVA: 0x212dcf0 VA: 0x7594745cf0
	private Void <>xLuaBaseProxy_PlayInteraction() { }
	// RVA: 0x212dd58 VA: 0x7594745d58
	private Void <>xLuaBaseProxy_PlaySpecialManually() { }
	// RVA: 0x212ddc0 VA: 0x7594745dc0
	private Void <>xLuaBaseProxy_PlayStart() { }
	// RVA: 0x212de28 VA: 0x7594745e28
	private Void <>xLuaBaseProxy_SetAnimationOption(AnimationOption P0) { }
	// RVA: 0x212dea8 VA: 0x7594745ea8
	private Boolean <>xLuaBaseProxy_IsPlayingInteraction() { }
	// RVA: 0x212df10 VA: 0x7594745f10
	private Boolean <>xLuaBaseProxy_IsPlayingStart() { }
}
```