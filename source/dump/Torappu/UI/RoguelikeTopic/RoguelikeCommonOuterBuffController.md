# RoguelikeCommonOuterBuffController

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeCommonOuterBuffDataRouter _dataRouter`

- `RoguelikeCommonOuterBuffView _buffView`

- `RoguelikeCommonOuterBuffSummaryView _summaryView`

- `RectTransform _topMenuContainer`

- `UIFadeFloatPanel _panelSummary`

- `GameObject _panelContent`

- `Boolean m_isInited`

- `String m_topicId`

- `RoguelikeCommonOuterBuffProperty m_buffProperty`

- `RoguelikeCommonOuterBuffSummaryProperty m_summaryProperty`


## Methods

- `Void _InitIfNot()`

- `RoguelikeCommonDevelopmentData _LoadDevelopmentData()`

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
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffController : RoguelikeTopicOuterBuffController
{
	private RoguelikeCommonOuterBuffDataRouter _dataRouter; // 0x28
	private RoguelikeCommonOuterBuffView _buffView; // 0x30
	private RoguelikeCommonOuterBuffSummaryView _summaryView; // 0x38
	private RectTransform _topMenuContainer; // 0x40
	private UIFadeFloatPanel _panelSummary; // 0x48
	private GameObject _panelContent; // 0x50
	private Boolean m_isInited; // 0x58
	private String m_topicId; // 0x60
	private RoguelikeCommonOuterBuffProperty m_buffProperty; // 0x68
	private RoguelikeCommonOuterBuffSummaryProperty m_summaryProperty; // 0x70
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__LoadDevelopmentData; // 0x20
	private static DelegateBridge __Hotfix0__OnSummaryShow; // 0x28
	private static DelegateBridge __Hotfix0__OnSunmmaryHide; // 0x30
	private static DelegateBridge __Hotfix0__OnNodeClick; // 0x38
	private static DelegateBridge __Hotfix0__OnNodeUpgrade; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x265e744 VA: 0x7594c76744
	public override Void Init() { }
	// RVA: 0x265eb08 VA: 0x7594c76b08
	public override Void OnEnter(String topicId) { }
	// RVA: 0x265fed4 VA: 0x7594c77ed4
	public override Void OnResume(Boolean isResumedFromStack) { }
	// RVA: 0x265e818 VA: 0x7594c76818
	private Void _InitIfNot() { }
	// RVA: 0x265ed18 VA: 0x7594c76d18
	private RoguelikeCommonDevelopmentData _LoadDevelopmentData() { }
	// RVA: 0x26603a0 VA: 0x7594c783a0
	private Void _OnSummaryShow() { }
	// RVA: 0x266058c VA: 0x7594c7858c
	private Void _OnSunmmaryHide() { }
	// RVA: 0x2660694 VA: 0x7594c78694
	private Void _OnNodeClick(String buffId) { }
	// RVA: 0x26607a4 VA: 0x7594c787a4
	private Void _OnNodeUpgrade(String buffId) { }
	// RVA: 0x2660c38 VA: 0x7594c78c38
	public Void .ctor() { }
	// RVA: 0x2660e60 VA: 0x7594c78e60
	private Void <>xLuaBaseProxy_Init() { }
	// RVA: 0x2660e64 VA: 0x7594c78e64
	private Void <>xLuaBaseProxy_OnEnter(String P0) { }
	// RVA: 0x2660e68 VA: 0x7594c78e68
	private Void <>xLuaBaseProxy_OnResume(Boolean P0) { }
}
```