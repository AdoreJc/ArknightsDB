# Act1ArcadeStageDetailView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `RectTransform _stageInfoPrefabHolder`

- `Text _textRecommendLevel`

- `Text _textStageName`

- `Text _textStageSubName`

- `Text _textStageDesc`

- `Text _textStageMechDesc`

- `ScrollRect _scrollStageDesc`

- `Act1ArcadeGameObjectSwitchComp _stageIndexSwitch`

- `Image _imgMaxRank`

- `Text _textMaxScore`

- `Button _btnScoreDetail`

- `TwoStateToggle _scoreStateToggle`

- `UIAnimationLocation _stageChangeAnim`

- `Button _btnEnemyHandBook`

- `Button _btnMap`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`

- `String m_curShowZoneInfoZoneId`

- `Boolean m_isZoneIdChange`

- `String m_curShowStageId`

- `Boolean m_isStageIdChange`

- `Tween m_stageChangeAnimTween`

- `GameObject m_curShowZoneInfoGO`


## Methods

- `Void _RenderStageBasicInfo(Act1ArcadeSingleStageModel)`

- `Void _ShowStageInfoPrefab(String, Act1ArcadeSingleZoneModel)`

- `Void _RenderScoreInfo(Act1ArcadeSingleStageModel)`

- `Void EventOnClickEnemyHandBook()`

- `Void EventOnClickMap()`

- `Void EventOnClickScoreInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeStageDetailView : DataBinder`1
{
	private RectTransform _stageInfoPrefabHolder; // 0x20
	private Text _textRecommendLevel; // 0x28
	private Text _textStageName; // 0x30
	private Text _textStageSubName; // 0x38
	private Text _textStageDesc; // 0x40
	private Text _textStageMechDesc; // 0x48
	private ScrollRect _scrollStageDesc; // 0x50
	private Act1ArcadeGameObjectSwitchComp _stageIndexSwitch; // 0x58
	private Image _imgMaxRank; // 0x60
	private Text _textMaxScore; // 0x68
	private Button _btnScoreDetail; // 0x70
	private TwoStateToggle _scoreStateToggle; // 0x78
	private UIAnimationLocation _stageChangeAnim; // 0x80
	private Button _btnEnemyHandBook; // 0x90
	private Button _btnMap; // 0x98
	private UIStateFinder m_stateFinder; // 0xa0
	private UIPageFinder m_pageFinder; // 0xb0
	private Dictionary`2 m_catchedZoneInfoDict; // 0xc0
	private String m_curShowZoneInfoZoneId; // 0xc8
	private Boolean m_isZoneIdChange; // 0xd0
	private String m_curShowStageId; // 0xd8
	private Boolean m_isStageIdChange; // 0xe0
	private Tween m_stageChangeAnimTween; // 0xe8
	private GameObject m_curShowZoneInfoGO; // 0xf0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderStageBasicInfo; // 0x8
	private static DelegateBridge __Hotfix0__ShowStageInfoPrefab; // 0x10
	private static DelegateBridge __Hotfix0__RenderScoreInfo; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClickEnemyHandBook; // 0x20
	private static DelegateBridge __Hotfix0_EventOnClickMap; // 0x28
	private static DelegateBridge __Hotfix0_EventOnClickScoreInfo; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x34133a8 VA: 0x7595a2b3a8
	public override Void OnValueChanged(Act1ArcadeStageSelectProperty property) { }
	// RVA: 0x3413600 VA: 0x7595a2b600
	private Void _RenderStageBasicInfo(Act1ArcadeSingleStageModel stageModel) { }
	// RVA: 0x3413778 VA: 0x7595a2b778
	private Void _ShowStageInfoPrefab(String actId, Act1ArcadeSingleZoneModel zoneModel) { }
	// RVA: 0x341399c VA: 0x7595a2b99c
	private Void _RenderScoreInfo(Act1ArcadeSingleStageModel stageModel) { }
	// RVA: 0x3413c44 VA: 0x7595a2bc44
	public Void EventOnClickEnemyHandBook() { }
	// RVA: 0x3413cf8 VA: 0x7595a2bcf8
	public Void EventOnClickMap() { }
	// RVA: 0x3413dac VA: 0x7595a2bdac
	public Void EventOnClickScoreInfo() { }
	// RVA: 0x3413e60 VA: 0x7595a2be60
	public Void .ctor() { }
}
```