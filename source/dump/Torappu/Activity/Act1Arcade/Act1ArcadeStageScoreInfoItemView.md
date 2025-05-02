# Act1ArcadeStageScoreInfoItemView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `TwoStateToggle _rewardStateToggle`

- `Image _imgRank`

- `Text _textScoreLimit`

- `Text _textReward`

- `Image _imgToken`

- `UIItemViewModel m_itemViewModel`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot(Act1ArcadeStageSelectViewModel, ArcadeStageRankRewardLevelData, ILoadAsset)`

- `Void Render(Act1ArcadeStageSelectViewModel, ArcadeStageRankRewardLevelData, ILoadAsset)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeStageScoreInfoItemView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _rewardStateToggle; // 0x18
	private Image _imgRank; // 0x20
	private Text _textScoreLimit; // 0x28
	private Text _textReward; // 0x30
	private Image _imgToken; // 0x38
	private UIItemViewModel m_itemViewModel; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3414a54 VA: 0x7595a2ca54
	private Void _InitIfNot(Act1ArcadeStageSelectViewModel stageSelectModel, ArcadeStageRankRewardLevelData curLevelReward, ILoadAsset assetLoader) { }
	// RVA: 0x341446c VA: 0x7595a2c46c
	public Void Render(Act1ArcadeStageSelectViewModel stageSelectModel, ArcadeStageRankRewardLevelData curLevelReward, ILoadAsset assetLoader) { }
	// RVA: 0x3414bd8 VA: 0x7595a2cbd8
	public Void .ctor() { }
}
```