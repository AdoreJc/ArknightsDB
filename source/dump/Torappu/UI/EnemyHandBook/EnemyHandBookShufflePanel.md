# EnemyHandBookShufflePanel

**Namespace:** `Torappu.UI.EnemyHandBook`


## Fields

- `EnemyHandbookBossShuffleObject _bossShuffle`

- `EnemyHandbookBossShuffleObject _bossShuffle2`

- `SimpleLayoutContent _raceShuffleContent`

- `SimpleLayoutContent _attackTypeShuffleContent`

- `SimpleLayoutContent _damageTypeShuffleContent`

- `SimpleLayoutContent _motionTypeShuffleContent`

- `TwoStateToggle _ascendingButton`

- `TwoStateToggle _haveShuffleState`

- `UnityEvent _onCleanShuffle`

- `UIIntEvent _damageTypeEvent`

- `UIIntEvent _attackTypeEvent`

- `UIIntEvent _motionTypeEvent`

- `UIIntEvent _raceTypeEvent`

- `UIAnimationLocation _enterAnim`

- `GameObject _content`

- `UnityEnemyLevelEvent _enemyLevelEvent`

- `RaceAdatper m_raceAdapter`

- `AttackTypeAdatper m_atAdapter`

- `DamageTypeAdatper m_dtAdapter`

- `MotionTypeAdatper m_mtAdapter`

- `AnimationSwitchTween m_fadeSwitchTween`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void OnCleanShuffle()`

- `Void OnShow()`

- `Void OnHide()`

- `Boolean IsShow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyHandBook
public class EnemyHandBookShufflePanel : DataBinder`1
{
	private EnemyHandbookBossShuffleObject _bossShuffle; // 0x20
	private EnemyHandbookBossShuffleObject _bossShuffle2; // 0x28
	private SimpleLayoutContent _raceShuffleContent; // 0x30
	private SimpleLayoutContent _attackTypeShuffleContent; // 0x38
	private SimpleLayoutContent _damageTypeShuffleContent; // 0x40
	private SimpleLayoutContent _motionTypeShuffleContent; // 0x48
	private TwoStateToggle _ascendingButton; // 0x50
	private TwoStateToggle _haveShuffleState; // 0x58
	private UnityEvent _onCleanShuffle; // 0x60
	private UIIntEvent _damageTypeEvent; // 0x68
	private UIIntEvent _attackTypeEvent; // 0x70
	private UIIntEvent _motionTypeEvent; // 0x78
	private UIIntEvent _raceTypeEvent; // 0x80
	private UIAnimationLocation _enterAnim; // 0x88
	private GameObject _content; // 0x98
	private UnityEnemyLevelEvent _enemyLevelEvent; // 0xa0
	private RaceAdatper m_raceAdapter; // 0xa8
	private AttackTypeAdatper m_atAdapter; // 0xb0
	private DamageTypeAdatper m_dtAdapter; // 0xb8
	private MotionTypeAdatper m_mtAdapter; // 0xc0
	private AnimationSwitchTween m_fadeSwitchTween; // 0xc8
	private Boolean m_hasInited; // 0xd0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnCleanShuffle; // 0x8
	private static DelegateBridge __Hotfix0_OnShow; // 0x10
	private static DelegateBridge __Hotfix0_OnHide; // 0x18
	private static DelegateBridge __Hotfix0_IsShow; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x293b6b4 VA: 0x7594f536b4
	private Void _InitIfNot() { }
	// RVA: 0x293b948 VA: 0x7594f53948
	public Void OnCleanShuffle() { }
	// RVA: 0x293b9c4 VA: 0x7594f539c4
	public Void OnShow() { }
	// RVA: 0x293ba40 VA: 0x7594f53a40
	public Void OnHide() { }
	// RVA: 0x293babc VA: 0x7594f53abc
	public Boolean IsShow() { }
	// RVA: 0x293bb30 VA: 0x7594f53b30
	public override Void OnValueChanged(EnemyHandBookShowProperty property) { }
	// RVA: 0x293bd58 VA: 0x7594f53d58
	public Void .ctor() { }
}
```