# Act1LockInterlockDetailView

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Text _textType`

- `Text _textCode`

- `Text _textName`

- `Text _textDifficulty`

- `Text _textDesc`

- `Text _textApCost`

- `Text _textLockCount`

- `GameObject _btnCancelLockGo`

- `Image _imgMapPreview`

- `SimpleLayoutContent _rewardList`

- `SimpleLayoutContent _charList`

- `StagePreviewRankView _rankView`

- `UIAnimationLocation _animation`

- `Image _imgLockBg`

- `Image _imgLockIcon`

- `Sprite _spriteUnlock`

- `Sprite _spriteLock`

- `Color _colorUnlock`

- `Color _colorLock`

- `GameObject _unlockHintGo`

- `Image _imgEnemyIcon`

- `Action <onBtnEnemy>k__BackingField`

- `Action <onBtnBattle>k__BackingField`

- `Action <onBtnReward>k__BackingField`

- `Action <onBtnJumpFinal>k__BackingField`

- `Action <onInterlockUpdate>k__BackingField`

- `Act1LockDetailProperty m_property`

- `Act1LockInterlockDetailModel m_detailModel`

- `Boolean m_hasInited`

- `RewardPreviewAdapter m_rewardAdapter`

- `InterlockCharAdapter m_charAdapter`

- `DirectAssetLoader m_stagePreviewMapLoader`

- `Sprite m_stagePreviewMap`

- `String m_stageId`

- `Tween m_expandTween`

- `Boolean m_isAniming`


## Properties

- `Action onBtnEnemy`

- `Action onBtnBattle`

- `Action onBtnReward`

- `Action onBtnJumpFinal`

- `Action onInterlockUpdate`


## Methods

- `Action get_onBtnEnemy()`

- `Void set_onBtnEnemy(Action)`

- `Action get_onBtnBattle()`

- `Void set_onBtnBattle(Action)`

- `Action get_onBtnReward()`

- `Void set_onBtnReward(Action)`

- `Action get_onBtnJumpFinal()`

- `Void set_onBtnJumpFinal(Action)`

- `Action get_onInterlockUpdate()`

- `Void set_onInterlockUpdate(Action)`

- `Void _UpdateInterlock(Act1LockInterlockDetailModel)`

- `Void _InitIfNot()`

- `Void _UpdateView(Act1LockInterlockDetailModel)`

- `Void _CleanAnimTween()`

- `Void _LoadMapPreview(String)`

- `Void _UnloadStagePreviewMap()`

- `Void _UpdateRewardList(StageViewModel)`

- `Void _UpdateCharList(Act1LockInterlockDetailModel)`

- `Void _SwitchExpandStatus()`

- `Void OnBtnEnemyClick()`

- `Void OnBtnStartBattleClick()`

- `Void OnBtnExpandClick()`

- `Void OnBtnRewardClick()`

- `Void OnJumpToFinalDetailView()`

- `Void OnBtnCancel()`

- `Void <OnBtnCancel>b__66_0()`

- `Void <OnBtnCancel>b__66_1(Act1LockSetDefendResponse)`

- `Void <>xLuaBaseProxy_OnDataUpdated(Act1LockDetailProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockInterlockDetailView : Act1LockDetailViewBase
{
	private Text _textType; // 0x48
	private Text _textCode; // 0x50
	private Text _textName; // 0x58
	private Text _textDifficulty; // 0x60
	private Text _textDesc; // 0x68
	private Text _textApCost; // 0x70
	private Text _textLockCount; // 0x78
	private GameObject _btnCancelLockGo; // 0x80
	private Image _imgMapPreview; // 0x88
	private SimpleLayoutContent _rewardList; // 0x90
	private SimpleLayoutContent _charList; // 0x98
	private StagePreviewRankView _rankView; // 0xa0
	private UIAnimationLocation _animation; // 0xa8
	private Image _imgLockBg; // 0xb8
	private Image _imgLockIcon; // 0xc0
	private Sprite _spriteUnlock; // 0xc8
	private Sprite _spriteLock; // 0xd0
	private Color _colorUnlock; // 0xd8
	private Color _colorLock; // 0xe8
	private GameObject _unlockHintGo; // 0xf8
	private Image _imgEnemyIcon; // 0x100
	private Action <onBtnEnemy>k__BackingField; // 0x108
	private Action <onBtnBattle>k__BackingField; // 0x110
	private Action <onBtnReward>k__BackingField; // 0x118
	private Action <onBtnJumpFinal>k__BackingField; // 0x120
	private Action <onInterlockUpdate>k__BackingField; // 0x128
	private Act1LockDetailProperty m_property; // 0x130
	private Act1LockInterlockDetailModel m_detailModel; // 0x138
	private Boolean m_hasInited; // 0x140
	private RewardPreviewAdapter m_rewardAdapter; // 0x148
	private InterlockCharAdapter m_charAdapter; // 0x150
	private DirectAssetLoader m_stagePreviewMapLoader; // 0x158
	private Sprite m_stagePreviewMap; // 0x160
	private String m_stageId; // 0x168
	private Tween m_expandTween; // 0x170
	private Boolean m_isAniming; // 0x178
	private static DelegateBridge __Hotfix0_get_onBtnEnemy; // 0x0
	private static DelegateBridge __Hotfix0_set_onBtnEnemy; // 0x8
	private static DelegateBridge __Hotfix0_get_onBtnBattle; // 0x10
	private static DelegateBridge __Hotfix0_set_onBtnBattle; // 0x18
	private static DelegateBridge __Hotfix0_get_onBtnReward; // 0x20
	private static DelegateBridge __Hotfix0_set_onBtnReward; // 0x28
	private static DelegateBridge __Hotfix0_get_onBtnJumpFinal; // 0x30
	private static DelegateBridge __Hotfix0_set_onBtnJumpFinal; // 0x38
	private static DelegateBridge __Hotfix0_get_onInterlockUpdate; // 0x40
	private static DelegateBridge __Hotfix0_set_onInterlockUpdate; // 0x48
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x50
	private static DelegateBridge __Hotfix0__UpdateInterlock; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x60
	private static DelegateBridge __Hotfix0__UpdateView; // 0x68
	private static DelegateBridge __Hotfix0__CleanAnimTween; // 0x70
	private static DelegateBridge __Hotfix0__LoadMapPreview; // 0x78
	private static DelegateBridge __Hotfix0__UnloadStagePreviewMap; // 0x80
	private static DelegateBridge __Hotfix0__UpdateRewardList; // 0x88
	private static DelegateBridge __Hotfix0__UpdateCharList; // 0x90
	private static DelegateBridge __Hotfix0__SwitchExpandStatus; // 0x98
	private static DelegateBridge __Hotfix0_OnBtnEnemyClick; // 0xa0
	private static DelegateBridge __Hotfix0_OnBtnStartBattleClick; // 0xa8
	private static DelegateBridge __Hotfix0_OnBtnExpandClick; // 0xb0
	private static DelegateBridge __Hotfix0_OnBtnRewardClick; // 0xb8
	private static DelegateBridge __Hotfix0_OnJumpToFinalDetailView; // 0xc0
	private static DelegateBridge __Hotfix0_OnBtnCancel; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	private Action onBtnEnemy { get; set; }
	private Action onBtnBattle { get; set; }
	private Action onBtnReward { get; set; }
	private Action onBtnJumpFinal { get; set; }
	private Action onInterlockUpdate { get; set; }

	// RVA: 0x33cb2cc VA: 0x75959e32cc
	private Action get_onBtnEnemy() { }
	// RVA: 0x33cb334 VA: 0x75959e3334
	public Void set_onBtnEnemy(Action value) { }
	// RVA: 0x33cb3b8 VA: 0x75959e33b8
	private Action get_onBtnBattle() { }
	// RVA: 0x33cb420 VA: 0x75959e3420
	public Void set_onBtnBattle(Action value) { }
	// RVA: 0x33cb4a4 VA: 0x75959e34a4
	private Action get_onBtnReward() { }
	// RVA: 0x33cb50c VA: 0x75959e350c
	public Void set_onBtnReward(Action value) { }
	// RVA: 0x33cb590 VA: 0x75959e3590
	private Action get_onBtnJumpFinal() { }
	// RVA: 0x33cb5f8 VA: 0x75959e35f8
	public Void set_onBtnJumpFinal(Action value) { }
	// RVA: 0x33cb67c VA: 0x75959e367c
	private Action get_onInterlockUpdate() { }
	// RVA: 0x33cb6e4 VA: 0x75959e36e4
	public Void set_onInterlockUpdate(Action value) { }
	// RVA: 0x33cb768 VA: 0x75959e3768
	protected override Void OnDataUpdated(Act1LockDetailProperty property) { }
	// RVA: 0x33cbb70 VA: 0x75959e3b70
	private Void _UpdateInterlock(Act1LockInterlockDetailModel detailModel) { }
	// RVA: 0x33cb8e0 VA: 0x75959e38e0
	private Void _InitIfNot() { }
	// RVA: 0x33cbd88 VA: 0x75959e3d88
	private Void _UpdateView(Act1LockInterlockDetailModel detailModel) { }
	// RVA: 0x33cba00 VA: 0x75959e3a00
	private Void _CleanAnimTween() { }
	// RVA: 0x33cc5e4 VA: 0x75959e45e4
	private Void _LoadMapPreview(String stageId) { }
	// RVA: 0x33cc69c VA: 0x75959e469c
	private Void _UnloadStagePreviewMap() { }
	// RVA: 0x33cc3bc VA: 0x75959e43bc
	private Void _UpdateRewardList(StageViewModel selectedStageModel) { }
	// RVA: 0x33cc1c4 VA: 0x75959e41c4
	private Void _UpdateCharList(Act1LockInterlockDetailModel detailModel) { }
	// RVA: 0x33cc8b4 VA: 0x75959e48b4
	private Void _SwitchExpandStatus() { }
	// RVA: 0x33ccb04 VA: 0x75959e4b04
	public Void OnBtnEnemyClick() { }
	// RVA: 0x33ccba0 VA: 0x75959e4ba0
	public Void OnBtnStartBattleClick() { }
	// RVA: 0x33ccc3c VA: 0x75959e4c3c
	public Void OnBtnExpandClick() { }
	// RVA: 0x33ccca4 VA: 0x75959e4ca4
	public Void OnBtnRewardClick() { }
	// RVA: 0x33ccd40 VA: 0x75959e4d40
	public Void OnJumpToFinalDetailView() { }
	// RVA: 0x33ccddc VA: 0x75959e4ddc
	public Void OnBtnCancel() { }
	// RVA: 0x33cd004 VA: 0x75959e5004
	public Void .ctor() { }
	// RVA: 0x33cd0b4 VA: 0x75959e50b4
	private Void <OnBtnCancel>b__66_0() { }
	// RVA: 0x33cd150 VA: 0x75959e5150
	private Void <OnBtnCancel>b__66_1(Act1LockSetDefendResponse response) { }
	// RVA: 0x33cd2ac VA: 0x75959e52ac
	private Void <>xLuaBaseProxy_OnDataUpdated(Act1LockDetailProperty P0) { }
}
```