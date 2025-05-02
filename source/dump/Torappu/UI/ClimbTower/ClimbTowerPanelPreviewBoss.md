# ClimbTowerPanelPreviewBoss

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textLevelNum`

- `Text _textLevelTotalNum`

- `EnemyHandBookDetailView _bossDetailView`

- `UIAtlasImage _imgBossInfo`

- `UIAtlasObject _atlas`


## Methods

- `Void Render(ClimbTowerLevelModel, ClimbTowerLevelPreviewViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerPanelPreviewBoss : MonoBehaviour, IHotfixable
{
	private const String MAX_LAYER_FORMAT; // 0x0
	private Text _textLevelNum; // 0x18
	private Text _textLevelTotalNum; // 0x20
	private EnemyHandBookDetailView _bossDetailView; // 0x28
	private UIAtlasImage _imgBossInfo; // 0x30
	private UIAtlasObject _atlas; // 0x38
	private const String BOSS_INFO_PREFIX; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2c74368 VA: 0x759528c368
	public Void Render(ClimbTowerLevelModel levelModel, ClimbTowerLevelPreviewViewModel model) { }
	// RVA: 0x2c74e04 VA: 0x759528ce04
	public Void .ctor() { }
}
```