# Rl03OuterBuffController

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Rl03OuterBuffView _buffView`

- `Rl03OuterBuffSummaryView _summaryView`

- `RectTransform _topMenuContainer`

- `UIFadeFloatPanel _panelSummary`

- `GameObject _panelContent`

- `Boolean m_isInited`

- `String m_topicId`

- `Rl03OuterBuffProperty m_buffProperty`

- `Rl03OuterBuffSummaryProperty m_summaryProperty`


## Methods

- `Void _InitIfNot()`

- `Void _OnSummaryShow()`

- `Void _OnSunmmaryHide()`

- `Void _OnNodeClick(String)`

- `Void _OnNodeUpgrade(String)`

- `Void <>xLuaBaseProxy_Init()`

- `Void <>xLuaBaseProxy_OnEnter(String)`

- `Void <>xLuaBaseProxy_OnResume(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffController : RoguelikeTopicOuterBuffController
{
	private Rl03OuterBuffView _buffView; // 0x28
	private Rl03OuterBuffSummaryView _summaryView; // 0x30
	private RectTransform _topMenuContainer; // 0x38
	private UIFadeFloatPanel _panelSummary; // 0x40
	private GameObject _panelContent; // 0x48
	private Boolean m_isInited; // 0x50
	private String m_topicId; // 0x58
	private Rl03OuterBuffProperty m_buffProperty; // 0x60
	private Rl03OuterBuffSummaryProperty m_summaryProperty; // 0x68
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnSummaryShow; // 0x20
	private static DelegateBridge __Hotfix0__OnSunmmaryHide; // 0x28
	private static DelegateBridge __Hotfix0__OnNodeClick; // 0x30
	private static DelegateBridge __Hotfix0__OnNodeUpgrade; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x26a8310 VA: 0x7594cc0310
	public override Void Init() { }
	// RVA: 0x26a8678 VA: 0x7594cc0678
	public override Void OnEnter(String topicId) { }
	// RVA: 0x26a98fc VA: 0x7594cc18fc
	public override Void OnResume(Boolean isResumedFromStack) { }
	// RVA: 0x26a8384 VA: 0x7594cc0384
	private Void _InitIfNot() { }
	// RVA: 0x26a9bcc VA: 0x7594cc1bcc
	private Void _OnSummaryShow() { }
	// RVA: 0x26a9db8 VA: 0x7594cc1db8
	private Void _OnSunmmaryHide() { }
	// RVA: 0x26a9ec0 VA: 0x7594cc1ec0
	private Void _OnNodeClick(String buffId) { }
	// RVA: 0x26a9fd0 VA: 0x7594cc1fd0
	private Void _OnNodeUpgrade(String buffId) { }
	// RVA: 0x26aa464 VA: 0x7594cc2464
	public Void .ctor() { }
	// RVA: 0x26aa5b8 VA: 0x7594cc25b8
	private Void <>xLuaBaseProxy_Init() { }
	// RVA: 0x26aa5c0 VA: 0x7594cc25c0
	private Void <>xLuaBaseProxy_OnEnter(String P0) { }
	// RVA: 0x26aa5c8 VA: 0x7594cc25c8
	private Void <>xLuaBaseProxy_OnResume(Boolean P0) { }
}
```