# RL02OuterBuffController

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `RL02OuterBuffDetailView _detailView`

- `RL02OuterBuffMapView _mapView`

- `RectTransform _topMenuContainer`

- `RL02OuterBuffSummaryView _summaryView`

- `Single _scaleShowDetail`

- `UIFadeFloatPanel _panelSummary`

- `RL02OuterBuffProperty m_property`

- `RL02OuterBuffListProperty m_listProperty`

- `LODController m_lodController`

- `MapScaleController m_mapScaleController`

- `FloatController m_floatController`


## Methods

- `Void _OnNodeClicked(String)`

- `Void _OnClearSelectNode()`

- `Void _OnSummaryClicked()`

- `Void _OnSummaryClose()`

- `Void _OnActivateNodeClicked()`

- `Void EventOnScaleChanged(Single)`

- `Void _OnFloatPanelShowChanged(Boolean)`

- `Void <>xLuaBaseProxy_Init()`

- `Void <>xLuaBaseProxy_OnEnter(String)`

- `Void <>xLuaBaseProxy_OnResume(Boolean)`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffController : RoguelikeTopicOuterBuffController, IHotfixable
{
	public const Single ANGLE_PER_SEGMENT; // 0x0
	private RL02OuterBuffDetailView _detailView; // 0x28
	private RL02OuterBuffMapView _mapView; // 0x30
	private RectTransform _topMenuContainer; // 0x38
	private RL02OuterBuffSummaryView _summaryView; // 0x40
	private Single _scaleShowDetail; // 0x48
	private UIFadeFloatPanel _panelSummary; // 0x50
	private RL02OuterBuffProperty m_property; // 0x58
	private RL02OuterBuffListProperty m_listProperty; // 0x60
	private LODController m_lodController; // 0x68
	private MapScaleController m_mapScaleController; // 0x70
	private FloatController m_floatController; // 0x78
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__OnNodeClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnClearSelectNode; // 0x28
	private static DelegateBridge __Hotfix0__OnSummaryClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnSummaryClose; // 0x38
	private static DelegateBridge __Hotfix0__OnActivateNodeClicked; // 0x40
	private static DelegateBridge __Hotfix0_EventOnScaleChanged; // 0x48
	private static DelegateBridge __Hotfix0__OnFloatPanelShowChanged; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x26ba6f0 VA: 0x7594cd26f0
	public override Void Init() { }
	// RVA: 0x26bb568 VA: 0x7594cd3568
	public override Void OnEnter(String topicId) { }
	// RVA: 0x26bcbb8 VA: 0x7594cd4bb8
	public override Void OnResume(Boolean isResumeFromStack) { }
	// RVA: 0x26bccd8 VA: 0x7594cd4cd8
	protected override Void OnDestroy() { }
	// RVA: 0x26bcdb8 VA: 0x7594cd4db8
	private Void _OnNodeClicked(String nodeId) { }
	// RVA: 0x26bcebc VA: 0x7594cd4ebc
	private Void _OnClearSelectNode() { }
	// RVA: 0x26bcf94 VA: 0x7594cd4f94
	private Void _OnSummaryClicked() { }
	// RVA: 0x26bd010 VA: 0x7594cd5010
	private Void _OnSummaryClose() { }
	// RVA: 0x26bd08c VA: 0x7594cd508c
	private Void _OnActivateNodeClicked() { }
	// RVA: 0x26bd43c VA: 0x7594cd543c
	public Void EventOnScaleChanged(Single scale) { }
	// RVA: 0x26bd600 VA: 0x7594cd5600
	private Void _OnFloatPanelShowChanged(Boolean hasPanelShown) { }
	// RVA: 0x26bd738 VA: 0x7594cd5738
	public Void .ctor() { }
	// RVA: 0x26bd8fc VA: 0x7594cd58fc
	private Void <>xLuaBaseProxy_Init() { }
	// RVA: 0x26bd904 VA: 0x7594cd5904
	private Void <>xLuaBaseProxy_OnEnter(String P0) { }
	// RVA: 0x26bd90c VA: 0x7594cd590c
	private Void <>xLuaBaseProxy_OnResume(Boolean P0) { }
	// RVA: 0x26bd918 VA: 0x7594cd5918
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```