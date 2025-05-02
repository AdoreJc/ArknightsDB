# Act1VAutoChessHUDBattleView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `RectTransform _numPanel`

- `Text _numFront`

- `Text _numMid`

- `Text _numBack`

- `Single _changeDistance`

- `Single _perDefDuration`

- `Single _maxDefDuration`

- `UIAnimationLocation _defBrokenAnim`

- `Text _defDamage`

- `UIAnimationLocation _damageAnim`

- `Text _enemyCount`

- `Text _round`

- `Boolean m_isInited`

- `Single m_cachedDef`

- `Tween m_showTween`

- `Tween m_damageTween`

- `AnimationSwitchTween m_defBrokenTween`

- `HUDSeqNumChecker m_enemyEnemyEscapeChecker`

- `HUDSeqNumChecker m_stateSeqChecker`

- `HUDSeqNumChecker m_shiedSeqChecker`


## Methods

- `Void _InitIfNot()`

- `Void Render(Act1VAutoChessHUDViewModel)`

- `Void _ResetDamageAnim()`

- `Void _PlayDefTween(Int32)`

- `Void _RenderDefNum(Int32)`

- `Void _CancelDefTweenIfNeeded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDBattleView : MonoBehaviour, IHotfixable
{
	private RectTransform _numPanel; // 0x18
	private Text _numFront; // 0x20
	private Text _numMid; // 0x28
	private Text _numBack; // 0x30
	private Single _changeDistance; // 0x38
	private Single _perDefDuration; // 0x3c
	private Single _maxDefDuration; // 0x40
	private UIAnimationLocation _defBrokenAnim; // 0x48
	private Text _defDamage; // 0x58
	private UIAnimationLocation _damageAnim; // 0x60
	private Text _enemyCount; // 0x70
	private Text _round; // 0x78
	private Boolean m_isInited; // 0x80
	private Single m_cachedDef; // 0x84
	private Tween m_showTween; // 0x88
	private Tween m_damageTween; // 0x90
	private AnimationSwitchTween m_defBrokenTween; // 0x98
	private HUDSeqNumChecker m_enemyEnemyEscapeChecker; // 0xa0
	private HUDSeqNumChecker m_stateSeqChecker; // 0xa8
	private HUDSeqNumChecker m_shiedSeqChecker; // 0xb0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__ResetDamageAnim; // 0x10
	private static DelegateBridge __Hotfix0__PlayDefTween; // 0x18
	private static DelegateBridge __Hotfix0__RenderDefNum; // 0x20
	private static DelegateBridge __Hotfix0__CancelDefTweenIfNeeded; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3370b88 VA: 0x7595988b88
	private Void _InitIfNot() { }
	// RVA: 0x3370c78 VA: 0x7595988c78
	public Void Render(Act1VAutoChessHUDViewModel viewModel) { }
	// RVA: 0x33714e0 VA: 0x75959894e0
	private Void _ResetDamageAnim() { }
	// RVA: 0x33712a4 VA: 0x75959892a4
	private Void _PlayDefTween(Int32 toDef) { }
	// RVA: 0x337115c VA: 0x759598915c
	private Void _RenderDefNum(Int32 def) { }
	// RVA: 0x33710cc VA: 0x75959890cc
	private Void _CancelDefTweenIfNeeded() { }
	// RVA: 0x33715a8 VA: 0x75959895a8
	public Void .ctor() { }
}
```