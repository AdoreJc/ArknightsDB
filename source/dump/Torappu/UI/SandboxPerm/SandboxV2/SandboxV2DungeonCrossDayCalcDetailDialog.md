# SandboxV2DungeonCrossDayCalcDetailDialog

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIRenderTextureImage _blurBackground`

- `Text _txtSurviveTitle`

- `Text _txtSurviveDay`

- `SimpleLayoutContent _baseInfoContent`

- `SimpleLayoutContent _enemyRushInfoContent`

- `SimpleLayoutContent _homeInfoContent`

- `Text _txtRatioTitle`

- `Text _txtRatio`

- `Text _txtRatioInfo`

- `Text _txtRatioScore`

- `GameObject _objExploreAll`

- `Text _txtExploreAllTips`

- `GameObject _objExploring`

- `Text _txtExploringTitle`

- `Text _txtExploringScore`

- `GameObject _objRift`

- `GameObject _objRiftNotGoingTips`

- `Text _txtRiftNotGoingTips`

- `GameObject _objRiftGoing`

- `Text _txtRiftGoingTitle`

- `Text _txtRiftGoingScore`

- `Text _txtSurvivalTotalScoreTitle`

- `Text _txtSurvivalTotalScore`

- `RectTransform _backRect`

- `Options m_options`

- `String m_dayRewardScoreTitle`

- `Int32 m_dayRewardScore`

- `String m_actionRewardTitle`

- `Int32 m_actionRewardScore`

- `String m_tacticalTitle`

- `Int32 m_tacticalScore`

- `String m_foodTitle`

- `Int32 m_foodScore`

- `Adapter m_baseInfoAdapter`

- `Adapter m_enemyRushInfoAdapter`

- `Adapter m_homeInfoAdapter`

- `String m_ratioTitle`

- `String m_ratioCount`

- `String m_ratioTips`

- `Int32 m_ratioScore`

- `Int32 m_exploreNodeScore`

- `Boolean m_exploreNodeComplete`

- `String m_exploreNodeCompleteTips`

- `String m_exploreNodeTips`

- `Boolean m_isRiftUnlocked`

- `Boolean m_hasRift`

- `String m_noRiftTips`

- `String m_riftTitle`

- `Int32 m_riftTotalScore`

- `String m_survivalTotalTitle`

- `Int32 m_survivalTotalScore`


## Methods

- `Void _LoadData(String, SandboxV2DungeonCrossDaySettleCalcModel)`

- `Void _RefreshBaseInfoList()`

- `Void _RefreshEnemyInfoList(SandboxV2Data, ReportSettle)`

- `Void _RefreshHomeInfoList(Dungeon, SandboxV2Data, ReportSettle)`

- `Void _RefreshEnemyRush(SandboxV2EnemyRushTypeData, String, Int32, Int32)`

- `Void _RefreshEnemyRushData(SandboxV2DungeonCrossDayEnemyRushType, String, Int32, Int32)`

- `Void OnBackEvent()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCrossDayCalcDetailDialog : UICompDialog`1
{
	private UIRenderTextureImage _blurBackground; // 0x48
	private Text _txtSurviveTitle; // 0x50
	private Text _txtSurviveDay; // 0x58
	private SimpleLayoutContent _baseInfoContent; // 0x60
	private SimpleLayoutContent _enemyRushInfoContent; // 0x68
	private SimpleLayoutContent _homeInfoContent; // 0x70
	private Text _txtRatioTitle; // 0x78
	private Text _txtRatio; // 0x80
	private Text _txtRatioInfo; // 0x88
	private Text _txtRatioScore; // 0x90
	private GameObject _objExploreAll; // 0x98
	private Text _txtExploreAllTips; // 0xa0
	private GameObject _objExploring; // 0xa8
	private Text _txtExploringTitle; // 0xb0
	private Text _txtExploringScore; // 0xb8
	private GameObject _objRift; // 0xc0
	private GameObject _objRiftNotGoingTips; // 0xc8
	private Text _txtRiftNotGoingTips; // 0xd0
	private GameObject _objRiftGoing; // 0xd8
	private Text _txtRiftGoingTitle; // 0xe0
	private Text _txtRiftGoingScore; // 0xe8
	private Text _txtSurvivalTotalScoreTitle; // 0xf0
	private Text _txtSurvivalTotalScore; // 0xf8
	private RectTransform _backRect; // 0x100
	private Options m_options; // 0x108
	private String m_dayRewardScoreTitle; // 0x110
	private Int32 m_dayRewardScore; // 0x118
	private String m_actionRewardTitle; // 0x120
	private Int32 m_actionRewardScore; // 0x128
	private String m_tacticalTitle; // 0x130
	private Int32 m_tacticalScore; // 0x138
	private String m_foodTitle; // 0x140
	private Int32 m_foodScore; // 0x148
	private Adapter m_baseInfoAdapter; // 0x150
	private Adapter m_enemyRushInfoAdapter; // 0x158
	private Adapter m_homeInfoAdapter; // 0x160
	private String m_ratioTitle; // 0x168
	private String m_ratioCount; // 0x170
	private String m_ratioTips; // 0x178
	private Int32 m_ratioScore; // 0x180
	private Int32 m_exploreNodeScore; // 0x184
	private Boolean m_exploreNodeComplete; // 0x188
	private String m_exploreNodeCompleteTips; // 0x190
	private String m_exploreNodeTips; // 0x198
	private Boolean m_isRiftUnlocked; // 0x1a0
	private Boolean m_hasRift; // 0x1a1
	private String m_noRiftTips; // 0x1a8
	private String m_riftTitle; // 0x1b0
	private Int32 m_riftTotalScore; // 0x1b8
	private String m_survivalTotalTitle; // 0x1c0
	private Int32 m_survivalTotalScore; // 0x1c8
	private ListDict`2 m_enemyRushInfoData; // 0x1d0
	private List`1 m_homeInfoData; // 0x1d8
	private List`1 m_enemyRushItemList; // 0x1e0
	private List`1 m_homeItemList; // 0x1e8
	private List`1 m_baseItemList; // 0x1f0
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0__LoadData; // 0x18
	private static DelegateBridge __Hotfix0__RefreshBaseInfoList; // 0x20
	private static DelegateBridge __Hotfix0__RefreshEnemyInfoList; // 0x28
	private static DelegateBridge __Hotfix0__RefreshHomeInfoList; // 0x30
	private static DelegateBridge __Hotfix0__RefreshEnemyRush; // 0x38
	private static DelegateBridge __Hotfix0__RefreshEnemyRushData; // 0x40
	private static DelegateBridge __Hotfix0_OnBackEvent; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x251dfb0 VA: 0x7594b35fb0
	protected override Void OnRender(Options options) { }
	// RVA: 0x251e770 VA: 0x7594b36770
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x251e7d8 VA: 0x7594b367d8
	protected override Void OnInit() { }
	// RVA: 0x251e2fc VA: 0x7594b362fc
	private Void _LoadData(String topicId, SandboxV2DungeonCrossDaySettleCalcModel baseData) { }
	// RVA: 0x251ea50 VA: 0x7594b36a50
	private Void _RefreshBaseInfoList() { }
	// RVA: 0x251ee5c VA: 0x7594b36e5c
	private Void _RefreshEnemyInfoList(SandboxV2Data topicDetailData, ReportSettle settle) { }
	// RVA: 0x251f3c4 VA: 0x7594b373c4
	private Void _RefreshHomeInfoList(Dungeon playerDungeonData, SandboxV2Data topicDetailData, ReportSettle settle) { }
	// RVA: 0x251fb1c VA: 0x7594b37b1c
	private Void _RefreshEnemyRush(SandboxV2EnemyRushTypeData data, String otherName, Int32 killCount, Int32 score) { }
	// RVA: 0x251fc90 VA: 0x7594b37c90
	private Void _RefreshEnemyRushData(SandboxV2DungeonCrossDayEnemyRushType type, String name, Int32 killCount, Int32 score) { }
	// RVA: 0x251fea0 VA: 0x7594b37ea0
	public Void OnBackEvent() { }
	// RVA: 0x251ff74 VA: 0x7594b37f74
	public Void .ctor() { }
	// RVA: 0x2520148 VA: 0x7594b38148
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
	// RVA: 0x2520150 VA: 0x7594b38150
	private Void <>xLuaBaseProxy_OnInit() { }
}
```