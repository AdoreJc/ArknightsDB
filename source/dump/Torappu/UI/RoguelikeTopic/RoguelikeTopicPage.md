# RoguelikeTopicPage

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `CanvasGroup _blackLoading`

- `CanvasGroup _topLayerMenus`

- `FadeSwitchTween m_blackLoadingTween`

- `String m_topicId`


## Properties

- `FadeSwitchTween blackLoadingSwitch`


## Methods

- `FadeSwitchTween get_blackLoadingSwitch()`

- `StateEngine GetStateEngine()`

- `Void _ConsumeTrackPoints()`

- `Void _DoAutoKeyVisual()`

- `String GetTopicId()`

- `Boolean _ValidateTopicId(String, out)`

- `IEnumerator _TopicEnterShowEffect()`

- `Boolean _CheckIfUseFastEnterAndMarkTrace()`

- `Void _DisplayTopMenuLayersWithConfig(DisplayParentConfig)`

- `IEnumerator <>n__0(Boolean)`

- `IEnumerator <>n__1(Boolean)`

- `Void <_TopicEnterShowEffect>b__19_0()`

- `Void <>xLuaBaseProxy_OnPageRouted()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicPage : StateEnginePage
{
	private const Single BLACK_FADEIN_DUR; // 0x0
	private CanvasGroup _blackLoading; // 0xe8
	private CanvasGroup _topLayerMenus; // 0xf0
	private FadeSwitchTween m_blackLoadingTween; // 0xf8
	private String m_topicId; // 0x100
	private static DelegateBridge __Hotfix0_get_blackLoadingSwitch; // 0x0
	private static DelegateBridge __Hotfix0_GetStateEngine; // 0x8
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x10
	private static DelegateBridge __Hotfix0_OnCreate; // 0x18
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x20
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x28
	private static DelegateBridge __Hotfix0__ConsumeTrackPoints; // 0x30
	private static DelegateBridge __Hotfix0__DoAutoKeyVisual; // 0x38
	private static DelegateBridge __Hotfix0_GetTopicId; // 0x40
	private static DelegateBridge __Hotfix0__ValidateTopicId; // 0x48
	private static DelegateBridge __Hotfix0__TopicEnterShowEffect; // 0x50
	private static DelegateBridge __Hotfix0__CheckIfUseFastEnterAndMarkTrace; // 0x58
	private static DelegateBridge __Hotfix0__DisplayTopMenuLayersWithConfig; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	protected FadeSwitchTween blackLoadingSwitch { get; }

	// RVA: 0x266db28 VA: 0x7594c85b28
	protected FadeSwitchTween get_blackLoadingSwitch() { }
	// RVA: 0x266dc04 VA: 0x7594c85c04
	public StateEngine GetStateEngine() { }
	// RVA: 0x266dc70 VA: 0x7594c85c70
	protected override Void OnPageRouted() { }
	// RVA: 0x266dd90 VA: 0x7594c85d90
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x266e20c VA: 0x7594c8620c
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x266e2fc VA: 0x7594c862fc
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x266de7c VA: 0x7594c85e7c
	private Void _ConsumeTrackPoints() { }
	// RVA: 0x266deec VA: 0x7594c85eec
	private Void _DoAutoKeyVisual() { }
	// RVA: 0x266e3ec VA: 0x7594c863ec
	public String GetTopicId() { }
	// RVA: 0x266e4a8 VA: 0x7594c864a8
	private Boolean _ValidateTopicId(String topicId, out String fallbackTopicId) { }
	// RVA: 0x266e5d8 VA: 0x7594c865d8
	private IEnumerator _TopicEnterShowEffect() { }
	// RVA: 0x266e6ac VA: 0x7594c866ac
	private Boolean _CheckIfUseFastEnterAndMarkTrace() { }
	// RVA: 0x266e940 VA: 0x7594c86940
	private Void _DisplayTopMenuLayersWithConfig(DisplayParentConfig config) { }
	// RVA: 0x266e9e8 VA: 0x7594c869e8
	public Void .ctor() { }
	// RVA: 0x266ea58 VA: 0x7594c86a58
	private IEnumerator <>n__0(Boolean isFromStack) { }
	// RVA: 0x266ea64 VA: 0x7594c86a64
	private IEnumerator <>n__1(Boolean isIntoStack) { }
	// RVA: 0x266ea70 VA: 0x7594c86a70
	private Void <_TopicEnterShowEffect>b__19_0() { }
	// RVA: 0x266ea90 VA: 0x7594c86a90
	private Void <>xLuaBaseProxy_OnPageRouted() { }
	// RVA: 0x266ea98 VA: 0x7594c86a98
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x266eaa0 VA: 0x7594c86aa0
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x266eaac VA: 0x7594c86aac
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```