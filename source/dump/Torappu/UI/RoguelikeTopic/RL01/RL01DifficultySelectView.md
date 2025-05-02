# RL01DifficultySelectView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL01`


## Fields

- `SimpleLayoutContent _difficultyList`

- `UIAnimationLocation _diffDetailAnim`

- `AnimationSwitchTween m_detailSwitch`

- `Adapter m_adapter`

- `RoguelikeTopicModeViewModel m_exploreModel`


## Methods

- `Void EventOnOpenDifficultyDetail()`

- `Void <>xLuaBaseProxy_SetVisible(Boolean, Boolean)`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL01
public class RL01DifficultySelectView : RoguelikeTopicDifficultySelectBaseView
{
	private SimpleLayoutContent _difficultyList; // 0x30
	private UIAnimationLocation _diffDetailAnim; // 0x38
	private AnimationSwitchTween m_detailSwitch; // 0x48
	private Adapter m_adapter; // 0x50
	private RoguelikeTopicModeViewModel m_exploreModel; // 0x58
	private static DelegateBridge __Hotfix0_OnRefresh; // 0x0
	private static DelegateBridge __Hotfix0_SetVisible; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_EventOnOpenDifficultyDetail; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x26c6e50 VA: 0x7594cdee50
	protected override Void OnRefresh(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26c6f30 VA: 0x7594cdef30
	protected override Void SetVisible(Boolean v, Boolean immediately) { }
	// RVA: 0x26c6fd8 VA: 0x7594cdefd8
	protected override Void OnInit() { }
	// RVA: 0x26c71b8 VA: 0x7594cdf1b8
	public Void EventOnOpenDifficultyDetail() { }
	// RVA: 0x26c7250 VA: 0x7594cdf250
	public Void .ctor() { }
	// RVA: 0x26c72c0 VA: 0x7594cdf2c0
	private Void <>xLuaBaseProxy_SetVisible(Boolean P0, Boolean P1) { }
	// RVA: 0x26c72d0 VA: 0x7594cdf2d0
	private Void <>xLuaBaseProxy_OnInit() { }
}
```