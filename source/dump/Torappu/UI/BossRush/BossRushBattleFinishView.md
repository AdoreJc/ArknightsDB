# BossRushBattleFinishView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `Text _textCode`

- `Text _textStageName`

- `Text _textStatus`

- `UIFullScreenImage _blurBackground`

- `RectTransform _illustContainer`

- `RectTransform _illustTextContainer`

- `AVGTypeWriterText _illustText`

- `SimpleLayoutContent _waveList`

- `Text _textCurrentExp`

- `Text _textTotalExp`

- `Slider _sliderExp`

- `Text _textMilestoneLv`

- `GameObject _tagMaxGo`

- `GameObject _tagLevelUpGo`

- `BossRushBattleFinishRewardItemView _milestoneReward`

- `BossRushBattleFinishRewardItemView _tokenReward`

- `GameObject _successInfoGo`

- `Text _textSuccessInfo`

- `BossRushBattleFinishViewModel m_viewModel`

- `Action <onClose>k__BackingField`


## Properties

- `Action onClose`


## Methods

- `Action get_onClose()`

- `Void set_onClose(Action)`

- `Void _Render()`

- `Void _RenderIllustView()`

- `CharWordData _FetchProperCharWord(CharUISkinStruct)`

- `Void JumpToBossRush()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushBattleFinishView : DynBattleFinishView
{
	private Text _textCode; // 0x20
	private Text _textStageName; // 0x28
	private Text _textStatus; // 0x30
	private UIFullScreenImage _blurBackground; // 0x38
	private RectTransform _illustContainer; // 0x40
	private RectTransform _illustTextContainer; // 0x48
	private AVGTypeWriterText _illustText; // 0x50
	private SimpleLayoutContent _waveList; // 0x58
	private Text _textCurrentExp; // 0x60
	private Text _textTotalExp; // 0x68
	private Slider _sliderExp; // 0x70
	private Text _textMilestoneLv; // 0x78
	private GameObject _tagMaxGo; // 0x80
	private GameObject _tagLevelUpGo; // 0x88
	private BossRushBattleFinishRewardItemView _milestoneReward; // 0x90
	private BossRushBattleFinishRewardItemView _tokenReward; // 0x98
	private GameObject _successInfoGo; // 0xa0
	private Text _textSuccessInfo; // 0xa8
	private BossRushBattleFinishViewModel m_viewModel; // 0xb0
	private Action <onClose>k__BackingField; // 0xb8
	private static DelegateBridge __Hotfix0_get_onClose; // 0x0
	private static DelegateBridge __Hotfix0_set_onClose; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0__Render; // 0x18
	private static DelegateBridge __Hotfix0__RenderIllustView; // 0x20
	private static DelegateBridge __Hotfix0__FetchProperCharWord; // 0x28
	private static DelegateBridge __Hotfix0_JumpToBossRush; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action onClose { get; set; }

	// RVA: 0x2e54b28 VA: 0x759546cb28
	private Action get_onClose() { }
	// RVA: 0x2e54b90 VA: 0x759546cb90
	public Void set_onClose(Action value) { }
	// RVA: 0x2e54c14 VA: 0x759546cc14
	protected override Void OnInit() { }
	// RVA: 0x2e55208 VA: 0x759546d208
	private Void _Render() { }
	// RVA: 0x2e55850 VA: 0x759546d850
	private Void _RenderIllustView() { }
	// RVA: 0x2e5632c VA: 0x759546e32c
	private CharWordData _FetchProperCharWord(CharUISkinStruct targetSkin) { }
	// RVA: 0x2e565ac VA: 0x759546e5ac
	public Void JumpToBossRush() { }
	// RVA: 0x2e56610 VA: 0x759546e610
	public Void .ctor() { }
}
```