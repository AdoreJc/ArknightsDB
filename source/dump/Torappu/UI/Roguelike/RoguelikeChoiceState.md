# RoguelikeChoiceState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _choiceViewContainer`

- `RectTransform _topMenuContainer`

- `Boolean m_hasInited`

- `RoguelikeChoiceStateBean m_stateBean`

- `RoguelikeDungeonPage m_page`

- `RoguelikeDungeonController m_controller`

- `String m_topicId`

- `RoguelikeChoiceView m_choiceView`

- `MenuAdapter m_menuAdapter`

- `RoguelikeChoiceEffectBase m_effectInst`


## Methods

- `Void OnDestroy()`

- `Void _InitIfNot()`

- `Void _SetEffectVisible(Boolean)`

- `Void _QuitChoiceScene()`

- `Void _TriggerBGMSignal()`

- `Void _ClearBGM()`

- `Void _ShowRoguelikeMenu(Boolean)`

- `Void _SendSelectChoiceRequest(String, Action)`

- `Void _UpdateDataAndRender(Boolean)`

- `Void _SelectChoice(String)`

- `Void <_SelectChoice>b__24_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeChoiceState : PopupFadeState, IHotfixable
{
	private RectTransform _choiceViewContainer; // 0x70
	private RectTransform _topMenuContainer; // 0x78
	private Boolean m_hasInited; // 0x80
	private RoguelikeChoiceStateBean m_stateBean; // 0x88
	private RoguelikeDungeonPage m_page; // 0x90
	private RoguelikeDungeonController m_controller; // 0x98
	private String m_topicId; // 0xa0
	private RoguelikeChoiceView m_choiceView; // 0xa8
	private MenuAdapter m_menuAdapter; // 0xb0
	private RoguelikeChoiceEffectBase m_effectInst; // 0xb8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__SetEffectVisible; // 0x30
	private static DelegateBridge __Hotfix0__QuitChoiceScene; // 0x38
	private static DelegateBridge __Hotfix0__TriggerBGMSignal; // 0x40
	private static DelegateBridge __Hotfix0__ClearBGM; // 0x48
	private static DelegateBridge __Hotfix0__ShowRoguelikeMenu; // 0x50
	private static DelegateBridge __Hotfix0__SendSelectChoiceRequest; // 0x58
	private static DelegateBridge __Hotfix0__UpdateDataAndRender; // 0x60
	private static DelegateBridge __Hotfix0__SelectChoice; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x29ef2e8 VA: 0x75950072e8
	protected override Void OnEnter() { }
	// RVA: 0x29efd58 VA: 0x7595007d58
	protected override Void OnResume() { }
	// RVA: 0x29efdfc VA: 0x7595007dfc
	protected override Void OnExit() { }
	// RVA: 0x29eff28 VA: 0x7595007f28
	public override IStateBean GetCacheBean() { }
	// RVA: 0x29eff90 VA: 0x7595007f90
	private Void OnDestroy() { }
	// RVA: 0x29ef4c8 VA: 0x75950074c8
	private Void _InitIfNot() { }
	// RVA: 0x29efa9c VA: 0x7595007a9c
	private Void _SetEffectVisible(Boolean isVisible) { }
	// RVA: 0x29f0264 VA: 0x7595008264
	private Void _QuitChoiceScene() { }
	// RVA: 0x29efbc8 VA: 0x7595007bc8
	private Void _TriggerBGMSignal() { }
	// RVA: 0x29efe7c VA: 0x7595007e7c
	private Void _ClearBGM() { }
	// RVA: 0x29f04cc VA: 0x75950084cc
	private Void _ShowRoguelikeMenu(Boolean isShow) { }
	// RVA: 0x29f05e8 VA: 0x75950085e8
	private Void _SendSelectChoiceRequest(String choiceId, Action onComplete) { }
	// RVA: 0x29ef918 VA: 0x7595007918
	private Void _UpdateDataAndRender(Boolean needFade) { }
	// RVA: 0x29f0958 VA: 0x7595008958
	private Void _SelectChoice(String choiceId) { }
	// RVA: 0x29f0b0c VA: 0x7595008b0c
	public Void .ctor() { }
	// RVA: 0x29f0c64 VA: 0x7595008c64
	private Void <_SelectChoice>b__24_0() { }
	// RVA: 0x29f0cbc VA: 0x7595008cbc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x29f0cc4 VA: 0x7595008cc4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x29f0ccc VA: 0x7595008ccc
	private Void <>xLuaBaseProxy_OnExit() { }
}
```