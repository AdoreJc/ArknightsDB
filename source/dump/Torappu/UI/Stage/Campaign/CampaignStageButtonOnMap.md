# CampaignStageButtonOnMap

**Namespace:** `Torappu.UI.Stage.Campaign`


## Fields

- `EasyInstancePool _breakRewardTogglePool`

- `Button _stageButton`

- `RectTransform _trackPointHolder`

- `GameObject m_trackPoint`


## Methods

- `Void _RenderTrackPoint(Boolean)`

- `RectTransform <>xLuaBaseProxy_get_positionRect()`

- `Void <>xLuaBaseProxy_RenderStage(StageButtonOnMapHolder, StageViewModel, ZoneViewModel, Boolean)`

- `Boolean <>xLuaBaseProxy_CheckStageLocked(StageViewModel, ZoneViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.Campaign
public class CampaignStageButtonOnMap : StageButtonOnMap, IHotfixable
{
	private EasyInstancePool _breakRewardTogglePool; // 0xd8
	private Button _stageButton; // 0xe0
	private RectTransform _trackPointHolder; // 0xe8
	private GameObject m_trackPoint; // 0xf0
	private static DelegateBridge __Hotfix0_get_positionRect; // 0x0
	private static DelegateBridge __Hotfix0_RenderStage; // 0x8
	private static DelegateBridge __Hotfix0_CheckStageLocked; // 0x10
	private static DelegateBridge __Hotfix0__RenderTrackPoint; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override RectTransform positionRect { get; }

	// RVA: 0x2fe2938 VA: 0x75955fa938
	public override RectTransform get_positionRect() { }
	// RVA: 0x2fe29a4 VA: 0x75955fa9a4
	public override Void RenderStage(StageButtonOnMapHolder holder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x2fe2ec8 VA: 0x75955faec8
	protected override Boolean CheckStageLocked(StageViewModel stageViewModel, ZoneViewModel zoneViewModel) { }
	// RVA: 0x2fe2cc4 VA: 0x75955facc4
	private Void _RenderTrackPoint(Boolean hasUnconfirmed) { }
	// RVA: 0x2fe3028 VA: 0x75955fb028
	public Void .ctor() { }
	// RVA: 0x2fe3098 VA: 0x75955fb098
	private RectTransform <>xLuaBaseProxy_get_positionRect() { }
	// RVA: 0x2fe30a0 VA: 0x75955fb0a0
	private Void <>xLuaBaseProxy_RenderStage(StageButtonOnMapHolder P0, StageViewModel P1, ZoneViewModel P2, Boolean P3) { }
	// RVA: 0x2fe30ac VA: 0x75955fb0ac
	private Boolean <>xLuaBaseProxy_CheckStageLocked(StageViewModel P0, ZoneViewModel P1) { }
}
```