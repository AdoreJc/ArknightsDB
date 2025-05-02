# RoguelikeTopicController

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `ResourceBarViewProperty _resourceBarProperty`

- `StateEngine _stateEngine`

- `RectTransform _topMenuContainer`

- `RectTransform _resourceContainer`

- `RectTransform _compDialogContainer`

- `RoguelikeTopicModeViewProperty m_modeProperty`

- `OnStateChangeListener m_stateEngineListener`

- `CommonTopMenu m_topMenu`

- `UISwitchTween m_topMenuSwitchTween`

- `UISwitchTween m_resourceSwitchTween`

- `String m_bgmInstIdAlias`

- `UICompDialogMgr m_dialogMgr`

- `RoguelikeTopicTheme <theme>k__BackingField`

- `String <topicId>k__BackingField`


## Properties

- `RoguelikeTopicModeViewProperty modeProperty`

- `RoguelikeTopicTheme theme`

- `String topicId`

- `UICompDialogMgr dialogMgr`


## Methods

- `RoguelikeTopicModeViewProperty get_modeProperty()`

- `RoguelikeTopicTheme get_theme()`

- `Void set_theme(RoguelikeTopicTheme)`

- `String get_topicId()`

- `Void set_topicId(String)`

- `UICompDialogMgr get_dialogMgr()`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void UpdateResource(Boolean)`

- `Void _OnBack()`

- `Void _OnBeforeTransition(Type, Type, Additions)`

- `RoguelikeTopicTheme _LoadTheme(String)`

- `Void _TriggerBGMSignal()`

- `String GetBgmInstIdAlias()`

- `Int64 _GetBGMInstId()`

- `Void _ClearBGM()`

- `String _GetBGMSignal()`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicController : PageSingleComponent, IPlayerDataListener, IHotfixable, IDataBindWrapper
{
	private const Single FADE_TWEEN_DURATION; // 0x0
	private static Type[] HIDE_TOP_MENU_STATES; // 0x0
	private static Type[] SHOW_RESOURCE_BAR_STATES; // 0x8
	private ResourceBarViewProperty _resourceBarProperty; // 0x20
	private StateEngine _stateEngine; // 0x28
	private RectTransform _topMenuContainer; // 0x30
	private RectTransform _resourceContainer; // 0x38
	private RectTransform _compDialogContainer; // 0x40
	private RoguelikeTopicModeViewProperty m_modeProperty; // 0x48
	private OnStateChangeListener m_stateEngineListener; // 0x50
	private CommonTopMenu m_topMenu; // 0x58
	private UISwitchTween m_topMenuSwitchTween; // 0x60
	private UISwitchTween m_resourceSwitchTween; // 0x68
	private String m_bgmInstIdAlias; // 0x70
	private UICompDialogMgr m_dialogMgr; // 0x78
	private RoguelikeTopicTheme <theme>k__BackingField; // 0x80
	private String <topicId>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_modeProperty; // 0x10
	private static DelegateBridge __Hotfix0_get_theme; // 0x18
	private static DelegateBridge __Hotfix0_set_theme; // 0x20
	private static DelegateBridge __Hotfix0_get_topicId; // 0x28
	private static DelegateBridge __Hotfix0_set_topicId; // 0x30
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x38
	private static DelegateBridge __Hotfix0_OnCreate; // 0x40
	private static DelegateBridge __Hotfix0_OnStart; // 0x48
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x50
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x58
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x60
	private static DelegateBridge __Hotfix0_UpdateResource; // 0x68
	private static DelegateBridge __Hotfix0__OnBack; // 0x70
	private static DelegateBridge __Hotfix0__OnBeforeTransition; // 0x78
	private static DelegateBridge __Hotfix0__CreateCommonTopMenu; // 0x80
	private static DelegateBridge __Hotfix0__LoadTheme; // 0x88
	private static DelegateBridge __Hotfix0__TriggerBGMSignal; // 0x90
	private static DelegateBridge __Hotfix0_GetBgmInstIdAlias; // 0x98
	private static DelegateBridge __Hotfix0__GetBGMInstId; // 0xa0
	private static DelegateBridge __Hotfix0__CreateRoguelikeTopicMusicChunk; // 0xa8
	private static DelegateBridge __Hotfix0__ClearBGM; // 0xb0
	private static DelegateBridge __Hotfix0__GetBGMSignal; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public RoguelikeTopicModeViewProperty modeProperty { get; }
	public RoguelikeTopicTheme theme { get; set; }
	public String topicId { get; set; }
	public UICompDialogMgr dialogMgr { get; }

	// RVA: 0x266a9b4 VA: 0x7594c829b4
	public RoguelikeTopicModeViewProperty get_modeProperty() { }
	// RVA: 0x2659818 VA: 0x7594c71818
	public RoguelikeTopicTheme get_theme() { }
	// RVA: 0x266aa2c VA: 0x7594c82a2c
	private Void set_theme(RoguelikeTopicTheme value) { }
	// RVA: 0x266a634 VA: 0x7594c82634
	public String get_topicId() { }
	// RVA: 0x266aac0 VA: 0x7594c82ac0
	private Void set_topicId(String value) { }
	// RVA: 0x266ab54 VA: 0x7594c82b54
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x266abcc VA: 0x7594c82bcc
	protected override Void OnCreate() { }
	// RVA: 0x266b290 VA: 0x7594c83290
	protected override Void OnStart() { }
	// RVA: 0x266b530 VA: 0x7594c83530
	protected override Void OnDestroy() { }
	// RVA: 0x266b66c VA: 0x7594c8366c
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x266b71c VA: 0x7594c8371c
	public Void OnPlayerDataChanged() { }
	// RVA: 0x266b790 VA: 0x7594c83790
	public Void UpdateResource(Boolean show) { }
	// RVA: 0x266b8a4 VA: 0x7594c838a4
	private Void _OnBack() { }
	// RVA: 0x266ba28 VA: 0x7594c83a28
	private Void _OnBeforeTransition(Type stateType, Type toType, Additions additions) { }
	// RVA: 0x266b074 VA: 0x7594c83074
	private static CommonTopMenu _CreateCommonTopMenu(RectTransform container, Action onBackClick) { }
	// RVA: 0x266afac VA: 0x7594c82fac
	private RoguelikeTopicTheme _LoadTheme(String topicId) { }
	// RVA: 0x266b314 VA: 0x7594c83314
	private Void _TriggerBGMSignal() { }
	// RVA: 0x266bd88 VA: 0x7594c83d88
	public String GetBgmInstIdAlias() { }
	// RVA: 0x266bb68 VA: 0x7594c83b68
	private Int64 _GetBGMInstId() { }
	// RVA: 0x266bc90 VA: 0x7594c83c90
	private static ChunkConfig _CreateRoguelikeTopicMusicChunk(String subSignal) { }
	// RVA: 0x266b5b4 VA: 0x7594c835b4
	private Void _ClearBGM() { }
	// RVA: 0x266bc18 VA: 0x7594c83c18
	private String _GetBGMSignal() { }
	// RVA: 0x266be00 VA: 0x7594c83e00
	public Void .ctor() { }
	// RVA: 0x266bf38 VA: 0x7594c83f38
	private static Void .cctor() { }
	// RVA: 0x266c288 VA: 0x7594c84288
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x266c290 VA: 0x7594c84290
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x266c298 VA: 0x7594c84298
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```