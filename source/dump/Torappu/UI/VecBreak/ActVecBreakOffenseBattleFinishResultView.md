# ActVecBreakOffenseBattleFinishResultView

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `Text _resultLevelText`

- `Text _levelNameText`

- `Text _levelStatusText`

- `Text _playerNameText`

- `Text _timeText`

- `ActVecBreakOffenseBattleFinishCharCardView _cardViewPrefab`

- `ActVecBreakOffenseBattleFinishResultBuffView _buffView`

- `ActVecBreakOffenseBattleFinishCharCardHolder _assistCharacterCardHolder`

- `Transform _illustRoot`

- `ActVecBreakOffenseBattleFinishMileStoneView _mileStoneView`

- `ActVecBreakOffenseBattleFinishViewModel m_viewModel`

- `CharUISkinStruct m_randomIllust`

- `UICharacterIllust m_cacheIllust`


## Methods

- `Void OnRender(ActVecBreakOffenseBattleFinishViewModel)`

- `Void OnNotificationShow()`

- `Void OnMileStoneTweenShow()`

- `Void PlayIllustVoice()`

- `Void _LoadCharCards()`

- `Void _LoadRandomIllust()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class ActVecBreakOffenseBattleFinishResultView : MonoBehaviour, IHotfixable
{
	private Text _resultLevelText; // 0x18
	private Text _levelNameText; // 0x20
	private Text _levelStatusText; // 0x28
	private Text _playerNameText; // 0x30
	private Text _timeText; // 0x38
	private ActVecBreakOffenseBattleFinishCharCardView _cardViewPrefab; // 0x40
	private ActVecBreakOffenseBattleFinishResultBuffView _buffView; // 0x48
	private List`1 _characterCardHolders; // 0x50
	private ActVecBreakOffenseBattleFinishCharCardHolder _assistCharacterCardHolder; // 0x58
	private Transform _illustRoot; // 0x60
	private ActVecBreakOffenseBattleFinishMileStoneView _mileStoneView; // 0x68
	private ActVecBreakOffenseBattleFinishViewModel m_viewModel; // 0x70
	private CharUISkinStruct m_randomIllust; // 0x78
	private UICharacterIllust m_cacheIllust; // 0x88
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_OnNotificationShow; // 0x8
	private static DelegateBridge __Hotfix0_OnMileStoneTweenShow; // 0x10
	private static DelegateBridge __Hotfix0_PlayIllustVoice; // 0x18
	private static DelegateBridge __Hotfix0__LoadCharCards; // 0x20
	private static DelegateBridge __Hotfix0__LoadRandomIllust; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x22c5cf0 VA: 0x75948ddcf0
	public Void OnRender(ActVecBreakOffenseBattleFinishViewModel viewModel) { }
	// RVA: 0x22c6434 VA: 0x75948de434
	public Void OnNotificationShow() { }
	// RVA: 0x22c64f0 VA: 0x75948de4f0
	public Void OnMileStoneTweenShow() { }
	// RVA: 0x22c65a8 VA: 0x75948de5a8
	public Void PlayIllustVoice() { }
	// RVA: 0x22c6074 VA: 0x75948de074
	private Void _LoadCharCards() { }
	// RVA: 0x22c624c VA: 0x75948de24c
	private Void _LoadRandomIllust() { }
	// RVA: 0x22c68e0 VA: 0x75948de8e0
	public Void .ctor() { }
}
```