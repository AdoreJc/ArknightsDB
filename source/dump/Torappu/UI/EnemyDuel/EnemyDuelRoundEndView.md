# EnemyDuelRoundEndView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `ThreeStateToggle _bkgToggle`

- `ThreeStateToggle _toggle`

- `GameObject _panelOptWin`

- `Text _moneyTextWin`

- `TwoStateToggle _winTextToggle`

- `TwoStateToggle _winSpineToggle`

- `GameObject _allInDeco`

- `TwoStateToggle _loseToggle`

- `Text _moneyTextLose`

- `TwoStateToggle _loseTextToggleAllIn`

- `TwoStateToggle _loseTextToggleOut`

- `GameObject _panelShield`

- `UIAnimationLocation _anim`

- `UISpineLocation _spineWin`

- `UISpineLocation _spineWinAllIn`

- `UISpineLocation _spineLose`

- `UISpineLocation _spineShield`

- `UISpineLocation _spineSkip`

- `EnemyDuelRoundEndPlayerInfoView _playerInfoLeft`

- `EnemyDuelRoundEndPlayerInfoView _playerInfoRight`

- `Tween m_tween`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _PlayAnim()`

- `Void _PlayMoneyTween(Text, Int32)`

- `Void _PlayAudio(Boolean, Boolean, Boolean, Boolean, Boolean)`

- `Void <_PlayAnim>b__25_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoundEndView : DataBinder`1
{
	private const Single MONEY_TWEEN_START_TIME; // 0x0
	private const Single MONEY_TWEEN_DURATION; // 0x0
	private ThreeStateToggle _bkgToggle; // 0x20
	private ThreeStateToggle _toggle; // 0x28
	private GameObject _panelOptWin; // 0x30
	private Text _moneyTextWin; // 0x38
	private TwoStateToggle _winTextToggle; // 0x40
	private TwoStateToggle _winSpineToggle; // 0x48
	private GameObject _allInDeco; // 0x50
	private TwoStateToggle _loseToggle; // 0x58
	private Text _moneyTextLose; // 0x60
	private TwoStateToggle _loseTextToggleAllIn; // 0x68
	private TwoStateToggle _loseTextToggleOut; // 0x70
	private GameObject _panelShield; // 0x78
	private UIAnimationLocation _anim; // 0x80
	private UISpineLocation _spineWin; // 0x90
	private UISpineLocation _spineWinAllIn; // 0xa0
	private UISpineLocation _spineLose; // 0xb0
	private UISpineLocation _spineShield; // 0xc0
	private UISpineLocation _spineSkip; // 0xd0
	private EnemyDuelRoundEndPlayerInfoView _playerInfoLeft; // 0xe0
	private EnemyDuelRoundEndPlayerInfoView _playerInfoRight; // 0xe8
	private Tween m_tween; // 0xf0
	private UIStateFinder m_stateFinder; // 0xf8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x8
	private static DelegateBridge __Hotfix0__PlayMoneyTween; // 0x10
	private static DelegateBridge __Hotfix0__PlayAudio; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2991af4 VA: 0x7594fa9af4
	public override Void OnValueChanged(EnemyDuelRoundEndProperty property) { }
	// RVA: 0x29921c8 VA: 0x7594faa1c8
	private Void _PlayAnim() { }
	// RVA: 0x2991ea4 VA: 0x7594fa9ea4
	private Void _PlayMoneyTween(Text moneyText, Int32 moneyChange) { }
	// RVA: 0x2992354 VA: 0x7594faa354
	private Void _PlayAudio(Boolean isMid, Boolean isWin, Boolean isAllin, Boolean isStand, Boolean useShield) { }
	// RVA: 0x2992514 VA: 0x7594faa514
	public Void .ctor() { }
	// RVA: 0x29925a4 VA: 0x7594faa5a4
	private Void <_PlayAnim>b__25_0() { }
}
```