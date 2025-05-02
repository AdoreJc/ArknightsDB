# TemplateActivityMapPreviewView

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `Transform _normalContainer`

- `Transform _hardContainer`

- `GameObject _mapTips`

- `Image _imageMapTips`

- `Image _backTips`

- `TemplateActivityResourceBar _resBar`

- `PreviewConfigViewProperty previewConfigProperty`

- `Config config`

- `StagePreviewNormalView m_normalPanel`

- `StagePreviewHardView m_hardPanel`

- `StageViewModel m_selectStage`

- `StageViewModel m_selectStageHard`

- `StageViewModel m_selectStageNormal`

- `SpecialStageType m_stageSelectType`

- `BattleMeta m_battleMeta`

- `UIPageFinder m_pageFinder`


## Properties

- `StagePreviewNormalView normalPanel`

- `StagePreviewHardView hardPanel`


## Methods

- `Void SetConfig(Config)`

- `Void Render(IStageSelectHandler, BattleMeta)`

- `StagePreviewEventHolder _GenEventHolder()`

- `StagePreviewNormalView get_normalPanel()`

- `StagePreviewHardView get_hardPanel()`

- `T _InstInfoPanel(Transform, String)`

- `Void _ClearBlurSprite()`

- `Void CloseTips()`

- `Void OnStartBattleClick()`

- `Void OnOpenEnemyClick()`

- `Void OnOpenRewardClick()`

- `Void OnBeSpecial()`

- `Void OnBeNormal()`

- `Void OnOpenRewardHolder()`

- `Void OnStartPractiseClick()`

- `Void OnAutoBattleSwitchClick()`

- `Void OnLockedHardBattleClick()`

- `StageViewModel _GetCurrentSelectedStageViewModel()`

- `Boolean _CheckCostBeforeStartBattle()`

- `Boolean _CheckApBeforeStartBattle(Int32)`

- `Boolean _CheckEtBeforeStartBattle(String, Int32)`

- `Void _GoToSquad(Boolean)`

- `Boolean _CheckNeedToLoadBattleLog(out)`

- `Void _OnGoToSquad(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityMapPreviewView : MonoBehaviour, IHotfixable
{
	private Transform _normalContainer; // 0x18
	private Transform _hardContainer; // 0x20
	private GameObject _mapTips; // 0x28
	private Image _imageMapTips; // 0x30
	private Image _backTips; // 0x38
	private TemplateActivityResourceBar _resBar; // 0x40
	public PreviewConfigViewProperty previewConfigProperty; // 0x48
	public Config config; // 0x50
	private StagePreviewNormalView m_normalPanel; // 0x58
	private StagePreviewHardView m_hardPanel; // 0x60
	private StageViewModel m_selectStage; // 0x68
	private StageViewModel m_selectStageHard; // 0x70
	private StageViewModel m_selectStageNormal; // 0x78
	private SpecialStageType m_stageSelectType; // 0x80
	private BattleMeta m_battleMeta; // 0x88
	private UIPageFinder m_pageFinder; // 0x90
	private static DelegateBridge __Hotfix0_SetConfig; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__GenEventHolder; // 0x10
	private static DelegateBridge __Hotfix0_get_normalPanel; // 0x18
	private static DelegateBridge __Hotfix0_get_hardPanel; // 0x20
	private static DelegateBridge __Hotfix0__InstInfoPanel; // 0x28
	private static DelegateBridge __Hotfix0__ClearBlurSprite; // 0x30
	private static DelegateBridge __Hotfix0_CloseTips; // 0x38
	private static DelegateBridge __Hotfix0_OnStartBattleClick; // 0x40
	private static DelegateBridge __Hotfix0_OnOpenEnemyClick; // 0x48
	private static DelegateBridge __Hotfix0_OnOpenRewardClick; // 0x50
	private static DelegateBridge __Hotfix0_OnBeSpecial; // 0x58
	private static DelegateBridge __Hotfix0_OnBeNormal; // 0x60
	private static DelegateBridge __Hotfix0_OnOpenRewardHolder; // 0x68
	private static DelegateBridge __Hotfix0_OnStartPractiseClick; // 0x70
	private static DelegateBridge __Hotfix0_OnAutoBattleSwitchClick; // 0x78
	private static DelegateBridge __Hotfix0_OnLockedHardBattleClick; // 0x80
	private static DelegateBridge __Hotfix0__GetCurrentSelectedStageViewModel; // 0x88
	private static DelegateBridge __Hotfix0__CheckCostBeforeStartBattle; // 0x90
	private static DelegateBridge __Hotfix0__CheckApBeforeStartBattle; // 0x98
	private static DelegateBridge __Hotfix0__CheckEtBeforeStartBattle; // 0xa0
	private static DelegateBridge __Hotfix0__GoToSquad; // 0xa8
	private static DelegateBridge __Hotfix0__CheckNeedToLoadBattleLog; // 0xb0
	private static DelegateBridge __Hotfix0__OnGoToSquad; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public StagePreviewNormalView normalPanel { get; }
	public StagePreviewHardView hardPanel { get; }

	// RVA: 0x3097d54 VA: 0x75956afd54
	public Void SetConfig(Config config) { }
	// RVA: 0x3097dd8 VA: 0x75956afdd8
	public Void Render(IStageSelectHandler selectHandler, BattleMeta battleMeta) { }
	// RVA: 0x30984d8 VA: 0x75956b04d8
	private StagePreviewEventHolder _GenEventHolder() { }
	// RVA: 0x3098380 VA: 0x75956b0380
	public StagePreviewNormalView get_normalPanel() { }
	// RVA: 0x3098228 VA: 0x75956b0228
	public StagePreviewHardView get_hardPanel() { }
	// RVA: 0x VA: 0x0
	private T _InstInfoPanel(Transform container, String path) { }
	// RVA: 0x30987f4 VA: 0x75956b07f4
	private Void _ClearBlurSprite() { }
	// RVA: 0x30988f8 VA: 0x75956b08f8
	public Void CloseTips() { }
	// RVA: 0x3098990 VA: 0x75956b0990
	public Void OnStartBattleClick() { }
	// RVA: 0x3098f64 VA: 0x75956b0f64
	public Void OnOpenEnemyClick() { }
	// RVA: 0x3099104 VA: 0x75956b1104
	public Void OnOpenRewardClick() { }
	// RVA: 0x30991b8 VA: 0x75956b11b8
	public Void OnBeSpecial() { }
	// RVA: 0x309925c VA: 0x75956b125c
	public Void OnBeNormal() { }
	// RVA: 0x3099300 VA: 0x75956b1300
	public Void OnOpenRewardHolder() { }
	// RVA: 0x30993fc VA: 0x75956b13fc
	public Void OnStartPractiseClick() { }
	// RVA: 0x3099608 VA: 0x75956b1608
	public Void OnAutoBattleSwitchClick() { }
	// RVA: 0x30996d8 VA: 0x75956b16d8
	public Void OnLockedHardBattleClick() { }
	// RVA: 0x30995a0 VA: 0x75956b15a0
	private StageViewModel _GetCurrentSelectedStageViewModel() { }
	// RVA: 0x3098a20 VA: 0x75956b0a20
	private Boolean _CheckCostBeforeStartBattle() { }
	// RVA: 0x30998dc VA: 0x75956b18dc
	private Boolean _CheckApBeforeStartBattle(Int32 apCost) { }
	// RVA: 0x30997a4 VA: 0x75956b17a4
	private Boolean _CheckEtBeforeStartBattle(String etItemId, Int32 etCost) { }
	// RVA: 0x3098aec VA: 0x75956b0aec
	private Void _GoToSquad(Boolean isPractice) { }
	// RVA: 0x3099a64 VA: 0x75956b1a64
	private Boolean _CheckNeedToLoadBattleLog(out Boolean allowNoBattleLog) { }
	// RVA: 0x3099b88 VA: 0x75956b1b88
	private Void _OnGoToSquad(Boolean isPractice) { }
	// RVA: 0x3099ee8 VA: 0x75956b1ee8
	public Void .ctor() { }
}
```