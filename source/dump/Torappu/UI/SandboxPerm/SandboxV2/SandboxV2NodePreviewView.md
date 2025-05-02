# SandboxV2NodePreviewView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _pnlAp`

- `Color _apToUseColor`

- `Color _apUsedColor`

- `GameObject _tutorialApPanel`

- `GameObject _titlePanel`

- `GameObject _tutorialTitlePanel`

- `Text _nodeTypeText`

- `Text _nodeStageText`

- `Image _nodeSprite`

- `Transform _weatherContainer`

- `SandboxV2NodePreviewWeatherView _weatherViewPrefab`

- `Text _nodeInfoText`

- `SandboxV2NodePreviewSupplyView _supplyView`

- `SandboxV2NodePreviewUpgradeView _upgradeView`

- `SandboxV2NodePreviewEnemyView _enemyView`

- `SandboxV2NodePreviewDropNpcView _dropNpcView`

- `SandboxV2NodePreviewNodeBuffView _nodeBuffView`

- `SandboxV2NodePreviewStartBattleView _startBattleView`

- `Button _btnStartBattle`

- `GameObject _tutorialApCostPnl`

- `Button _tutorialUpgradeBtn`

- `UIAtlasImage _imgGlow`

- `Color _colorEnemyRush`

- `GameObject _pnlApBkg`

- `String m_cachedNodeId`

- `SandboxV2NodeType m_cachedNodeType`

- `SandboxV2NodeStartBattleFuncType m_cachedStartBattleFuncType`

- `UIPageFinder m_pageFinder`

- `SandboxV2NodePreviewWeatherView m_weatherView`


## Methods

- `Void Render(SandboxV2DungeonNodeViewModel, SandboxV2DungeonViewModel)`

- `Void _InitIfNot()`

- `Void CloseWeatherAndZoneBuffDetail()`

- `Void OnSupplyBtnClicked()`

- `Void OnUpgradeBtnClicked()`

- `Void OnMapBtnClicked()`

- `Void OnEnemyDetailBtnClicked()`

- `Void OnDropDetailBtnClicked()`

- `Void OnStartBattleBtnClicked()`

- `GameObject TutorialOnly_GetStartBattleGo()`

- `GameObject TutorialOnly_GetWeatherPreviewBtnGo()`

- `GameObject TutorialOnly_GetNodeNamePnl()`

- `GameObject TutorialOnly_GetNodeApCostPnl()`

- `GameObject TutorialOnly_GetNodeCurrApPnl()`

- `GameObject TutorialOnly_GetNodeUpgradeBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodePreviewView : MonoBehaviour, IHotfixable
{
	private const Int32 MAX_AP_POINT; // 0x0
	private GameObject _pnlAp; // 0x18
	private UIAtlasImage[] _apPoints; // 0x20
	private Color _apToUseColor; // 0x28
	private Color _apUsedColor; // 0x38
	private GameObject _tutorialApPanel; // 0x48
	private GameObject _titlePanel; // 0x50
	private GameObject _tutorialTitlePanel; // 0x58
	private Text _nodeTypeText; // 0x60
	private Text _nodeStageText; // 0x68
	private Image _nodeSprite; // 0x70
	private Transform _weatherContainer; // 0x78
	private SandboxV2NodePreviewWeatherView _weatherViewPrefab; // 0x80
	private Text _nodeInfoText; // 0x88
	private SandboxV2NodePreviewSupplyView _supplyView; // 0x90
	private SandboxV2NodePreviewUpgradeView _upgradeView; // 0x98
	private SandboxV2NodePreviewEnemyView _enemyView; // 0xa0
	private SandboxV2NodePreviewDropNpcView _dropNpcView; // 0xa8
	private SandboxV2NodePreviewNodeBuffView _nodeBuffView; // 0xb0
	private SandboxV2NodePreviewStartBattleView _startBattleView; // 0xb8
	private Button _btnStartBattle; // 0xc0
	private GameObject _tutorialApCostPnl; // 0xc8
	private Button _tutorialUpgradeBtn; // 0xd0
	private UIAtlasImage _imgGlow; // 0xd8
	private Color _colorEnemyRush; // 0xe0
	private GameObject _pnlApBkg; // 0xf0
	private String m_cachedNodeId; // 0xf8
	private SandboxV2NodeType m_cachedNodeType; // 0x100
	private SandboxV2NodeStartBattleFuncType m_cachedStartBattleFuncType; // 0x104
	private UIPageFinder m_pageFinder; // 0x108
	private SandboxV2NodePreviewWeatherView m_weatherView; // 0x118
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_CloseWeatherAndZoneBuffDetail; // 0x10
	private static DelegateBridge __Hotfix0_OnSupplyBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnUpgradeBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0_OnMapBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0_OnEnemyDetailBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0_OnDropDetailBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0_OnStartBattleBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0_TutorialOnly_GetStartBattleGo; // 0x48
	private static DelegateBridge __Hotfix0_TutorialOnly_GetWeatherPreviewBtnGo; // 0x50
	private static DelegateBridge __Hotfix0_TutorialOnly_GetNodeNamePnl; // 0x58
	private static DelegateBridge __Hotfix0_TutorialOnly_GetNodeApCostPnl; // 0x60
	private static DelegateBridge __Hotfix0_TutorialOnly_GetNodeCurrApPnl; // 0x68
	private static DelegateBridge __Hotfix0_TutorialOnly_GetNodeUpgradeBtn; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x256ec60 VA: 0x7594b86c60
	public Void Render(SandboxV2DungeonNodeViewModel nodeViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x256f0fc VA: 0x7594b870fc
	private Void _InitIfNot() { }
	// RVA: 0x256f294 VA: 0x7594b87294
	public Void CloseWeatherAndZoneBuffDetail() { }
	// RVA: 0x256f388 VA: 0x7594b87388
	public Void OnSupplyBtnClicked() { }
	// RVA: 0x256f490 VA: 0x7594b87490
	public Void OnUpgradeBtnClicked() { }
	// RVA: 0x256f598 VA: 0x7594b87598
	public Void OnMapBtnClicked() { }
	// RVA: 0x256f6a0 VA: 0x7594b876a0
	public Void OnEnemyDetailBtnClicked() { }
	// RVA: 0x256f7a8 VA: 0x7594b877a8
	public Void OnDropDetailBtnClicked() { }
	// RVA: 0x256f8b0 VA: 0x7594b878b0
	public Void OnStartBattleBtnClicked() { }
	// RVA: 0x256fa88 VA: 0x7594b87a88
	public GameObject TutorialOnly_GetStartBattleGo() { }
	// RVA: 0x256fafc VA: 0x7594b87afc
	public GameObject TutorialOnly_GetWeatherPreviewBtnGo() { }
	// RVA: 0x256fbe8 VA: 0x7594b87be8
	public GameObject TutorialOnly_GetNodeNamePnl() { }
	// RVA: 0x256fc50 VA: 0x7594b87c50
	public GameObject TutorialOnly_GetNodeApCostPnl() { }
	// RVA: 0x256fcb8 VA: 0x7594b87cb8
	public GameObject TutorialOnly_GetNodeCurrApPnl() { }
	// RVA: 0x256fd20 VA: 0x7594b87d20
	public GameObject TutorialOnly_GetNodeUpgradeBtn() { }
	// RVA: 0x256fd94 VA: 0x7594b87d94
	public Void .ctor() { }
}
```