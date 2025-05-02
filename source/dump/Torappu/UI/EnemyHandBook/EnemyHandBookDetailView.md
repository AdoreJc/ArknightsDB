# EnemyHandBookDetailView

**Namespace:** `Torappu.UI.EnemyHandBook`


## Fields

- `Image _enemyImage`

- `GameObject _bossImage`

- `GameObject _eliteImage`

- `Text _enemyName`

- `Text _enemyRace`

- `Text _enemyDescrption`

- `Text _enemyIndex`

- `Text _hp`

- `Text _attack`

- `Text _defence`

- `Text _magDef`

- `Text _atkSpeed`

- `Text _moveSpeed`

- `Text _weightRate`

- `Text _atkType`

- `Text _enemyDamageRes`

- `Text _enemyRes`

- `GameObject _frozenImmune`

- `GameObject _levitateImmune`

- `GameObject _sleepImmune`

- `GameObject _stunImmune`

- `GameObject _disarmImmune`

- `GameObject _fearedImmune`

- `SimpleLayoutContent _detailTextGroup`

- `GameObject _abilityTitlePart`

- `GameObject _immunePart`

- `GameObject _spPart`

- `SimpleLayoutContent _linkContent`

- `UIStringEvent _linkClick`

- `GameObject _moreCountPart`

- `GameObject _moreCountIcon`

- `GameObject _noCountIcon`

- `Text _moreCountText`

- `ScrollRect _scrollRect`

- `Adapter m_adapter`

- `EnemyHandbookLinkEnemyAdapter m_linkAdapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Init(EnemyHandBookEverViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyHandBook
public class EnemyHandBookDetailView : MonoBehaviour, IHotfixable
{
	public const String WARNING_COLOR_PARAM; // 0x0
	private Image _enemyImage; // 0x18
	private GameObject _bossImage; // 0x20
	private GameObject _eliteImage; // 0x28
	private Text _enemyName; // 0x30
	private Text _enemyRace; // 0x38
	private Text _enemyDescrption; // 0x40
	private Text _enemyIndex; // 0x48
	private Text _hp; // 0x50
	private Text _attack; // 0x58
	private Text _defence; // 0x60
	private Text _magDef; // 0x68
	private Text _atkSpeed; // 0x70
	private Text _moveSpeed; // 0x78
	private Text _weightRate; // 0x80
	private Text _atkType; // 0x88
	private Text _enemyDamageRes; // 0x90
	private Text _enemyRes; // 0x98
	private GameObject _frozenImmune; // 0xa0
	private GameObject _levitateImmune; // 0xa8
	private GameObject _sleepImmune; // 0xb0
	private GameObject _stunImmune; // 0xb8
	private GameObject _disarmImmune; // 0xc0
	private GameObject _fearedImmune; // 0xc8
	private SimpleLayoutContent _detailTextGroup; // 0xd0
	private GameObject _abilityTitlePart; // 0xd8
	private GameObject _immunePart; // 0xe0
	private GameObject _spPart; // 0xe8
	private SimpleLayoutContent _linkContent; // 0xf0
	private UIStringEvent _linkClick; // 0xf8
	private GameObject _moreCountPart; // 0x100
	private GameObject _moreCountIcon; // 0x108
	private GameObject _noCountIcon; // 0x110
	private Text _moreCountText; // 0x118
	private ScrollRect _scrollRect; // 0x120
	private Adapter m_adapter; // 0x128
	private EnemyHandbookLinkEnemyAdapter m_linkAdapter; // 0x130
	private Boolean m_isInited; // 0x138
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x29352c4 VA: 0x7594f4d2c4
	private Void _InitIfNot() { }
	// RVA: 0x2935514 VA: 0x7594f4d514
	public Void Init(EnemyHandBookEverViewModel viewModel) { }
	// RVA: 0x2935ed8 VA: 0x7594f4ded8
	public Void .ctor() { }
}
```