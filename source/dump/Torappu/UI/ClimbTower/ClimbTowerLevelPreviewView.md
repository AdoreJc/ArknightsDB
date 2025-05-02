# ClimbTowerLevelPreviewView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `RectTransform _transLayerHolder`

- `ClimbTowerTowerLayerStack _towerLayerPrefab`

- `ClimbTowerPanelPreviewLevel _panelLevelPrefab`

- `ClimbTowerPanelPreviewBoss _panelBossPrefab`

- `GameObject _panelBtnUp`

- `GameObject _panelBtnDown`

- `CanvasGroup _canvasBossInfoSelected`

- `Image _imgBoss`

- `RectTransform _panelHolder`

- `ClimbTowerTowerLayerSelectArrowSimple _selectArrowPrefab`

- `ClimbTowerTowerLayerGodCardTipsSimple _godCardTipsPrefab`

- `Boolean m_inited`

- `String m_cachedTowerId`

- `Adapter m_adapter`

- `ClimbTowerLevelPreviewViewModel m_cachedModel`

- `FadeSwitchTween m_bossInfoBtnSelectedSwitchTween`

- `ClimbTowerPanelPreviewLevel m_panelPreviewLevel`

- `ClimbTowerPanelPreviewBoss m_panelPreviewBoss`

- `ClimbTowerTowerLayerStack m_towerLayerView`

- `Boolean m_cachedIsHardMode`

- `Action m_rewardDetailBtnCallback`


## Properties

- `Action rewardDetailBtnCallback`


## Methods

- `Void set_enemyHandbookBtnCallback(Action`2)`

- `Void set_rewardDetailBtnCallback(Action)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerLevelPreviewView : DataBinder`1
{
	private RectTransform _transLayerHolder; // 0x20
	private ClimbTowerTowerLayerStack _towerLayerPrefab; // 0x28
	private ClimbTowerPanelPreviewLevel _panelLevelPrefab; // 0x30
	private ClimbTowerPanelPreviewBoss _panelBossPrefab; // 0x38
	private GameObject _panelBtnUp; // 0x40
	private GameObject _panelBtnDown; // 0x48
	private CanvasGroup _canvasBossInfoSelected; // 0x50
	private Image _imgBoss; // 0x58
	private RectTransform _panelHolder; // 0x60
	private ClimbTowerTowerLayerSelectArrowSimple _selectArrowPrefab; // 0x68
	private ClimbTowerTowerLayerGodCardTipsSimple _godCardTipsPrefab; // 0x70
	private Boolean m_inited; // 0x78
	private String m_cachedTowerId; // 0x80
	private Adapter m_adapter; // 0x88
	private ClimbTowerLevelPreviewViewModel m_cachedModel; // 0x90
	private FadeSwitchTween m_bossInfoBtnSelectedSwitchTween; // 0x98
	private ClimbTowerPanelPreviewLevel m_panelPreviewLevel; // 0xa0
	private ClimbTowerPanelPreviewBoss m_panelPreviewBoss; // 0xa8
	private ClimbTowerTowerLayerStack m_towerLayerView; // 0xb0
	private Boolean m_cachedIsHardMode; // 0xb8
	private Action`2 m_enemyHandbookBtnCallback; // 0xc0
	private Action m_rewardDetailBtnCallback; // 0xc8
	private static DelegateBridge __Hotfix0_set_enemyHandbookBtnCallback; // 0x0
	private static DelegateBridge __Hotfix0_set_rewardDetailBtnCallback; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Action`2 enemyHandbookBtnCallback { set; }
	public Action rewardDetailBtnCallback { set; }

	// RVA: 0x2c739a8 VA: 0x759528b9a8
	public Void set_enemyHandbookBtnCallback(Action`2 value) { }
	// RVA: 0x2c73a2c VA: 0x759528ba2c
	public Void set_rewardDetailBtnCallback(Action value) { }
	// RVA: 0x2c73ab0 VA: 0x759528bab0
	private Void _InitIfNot() { }
	// RVA: 0x2c73fe4 VA: 0x759528bfe4
	public override Void OnValueChanged(ClimbTowerLevelPreviewProperty property) { }
	// RVA: 0x2c74820 VA: 0x759528c820
	public Void .ctor() { }
}
```