# ClimbTowerPanelPreviewLevel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textLevelNum`

- `Text _textLevelTotalNum`

- `Text _textLevelDesc`

- `Image _imgLevelPreview`

- `SimpleLayoutContent _rewardList`

- `SimpleLayoutContent _enemyInfoList`

- `Single _cardScaleFactor`

- `GameObject _panelList`

- `GameObject _panelEmpty`

- `GameObject _panelMore`

- `String m_cachedLevelId`

- `Boolean m_inited`

- `RewardAdapter m_rewardAdapter`

- `EnemyInfoAdapter m_enemyInfoAdapter`

- `Action m_rewardDetailBtnCallback`


## Properties

- `Action rewardDetailBtnCallback`


## Methods

- `Void set_enemyHandbookBtnCallback(Action`2)`

- `Void set_rewardDetailBtnCallback(Action)`

- `Void _InitIfNot()`

- `Void _LoadPreviewMap(String)`

- `Void _UnloadPreviewMap()`

- `Void Render(ClimbTowerLevelModel, Int32)`

- `Void OnJumpToEnemyHandbook(Int32)`

- `Void OnJumpToRewardDetailView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerPanelPreviewLevel : MonoBehaviour, IHotfixable
{
	private const String MAX_LAYER_FORMAT; // 0x0
	private const Int32 REWARD_PREVIEW_COUNT; // 0x0
	private const Int32 ENEMY_HANDBOOK_COUNT; // 0x0
	private Text _textLevelNum; // 0x18
	private Text _textLevelTotalNum; // 0x20
	private Text _textLevelDesc; // 0x28
	private Image _imgLevelPreview; // 0x30
	private SimpleLayoutContent _rewardList; // 0x38
	private SimpleLayoutContent _enemyInfoList; // 0x40
	private Single _cardScaleFactor; // 0x48
	private GameObject _panelList; // 0x50
	private GameObject _panelEmpty; // 0x58
	private GameObject _panelMore; // 0x60
	private String m_cachedLevelId; // 0x68
	private Boolean m_inited; // 0x70
	private List`1 m_cachedReward; // 0x78
	private List`1 m_cachedEnemyList; // 0x80
	private RewardAdapter m_rewardAdapter; // 0x88
	private EnemyInfoAdapter m_enemyInfoAdapter; // 0x90
	private Action`2 m_enemyHandbookBtnCallback; // 0x98
	private Action m_rewardDetailBtnCallback; // 0xa0
	private static DelegateBridge __Hotfix0_set_enemyHandbookBtnCallback; // 0x0
	private static DelegateBridge __Hotfix0_set_rewardDetailBtnCallback; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__LoadPreviewMap; // 0x18
	private static DelegateBridge __Hotfix0__UnloadPreviewMap; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0_OnJumpToEnemyHandbook; // 0x30
	private static DelegateBridge __Hotfix0_OnJumpToRewardDetailView; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Action`2 enemyHandbookBtnCallback { set; }
	public Action rewardDetailBtnCallback { set; }

	// RVA: 0x2c73edc VA: 0x759528bedc
	public Void set_enemyHandbookBtnCallback(Action`2 value) { }
	// RVA: 0x2c73f60 VA: 0x759528bf60
	public Void set_rewardDetailBtnCallback(Action value) { }
	// RVA: 0x2c74e74 VA: 0x759528ce74
	private Void _InitIfNot() { }
	// RVA: 0x2c750c0 VA: 0x759528d0c0
	private Void _LoadPreviewMap(String mapPreviewId) { }
	// RVA: 0x2c75228 VA: 0x759528d228
	private Void _UnloadPreviewMap() { }
	// RVA: 0x2c74588 VA: 0x759528c588
	public Void Render(ClimbTowerLevelModel levelModel, Int32 maxLayer) { }
	// RVA: 0x2c75334 VA: 0x759528d334
	public Void OnJumpToEnemyHandbook(Int32 enemyListIdx) { }
	// RVA: 0x2c75410 VA: 0x759528d410
	public Void OnJumpToRewardDetailView() { }
	// RVA: 0x2c754b8 VA: 0x759528d4b8
	public Void .ctor() { }
}
```