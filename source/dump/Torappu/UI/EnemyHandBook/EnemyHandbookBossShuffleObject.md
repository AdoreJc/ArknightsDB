# EnemyHandbookBossShuffleObject

**Namespace:** `Torappu.UI.EnemyHandBook`


## Fields

- `Single CHANGE_DURATION`

- `Text _allText`

- `Text _elteText`

- `Text _bossText`

- `Transform _bar`

- `Single _allPos`

- `Single _elitePos`

- `Single _bossPos`

- `UnityEnemyLevelEvent enemyLevelEvent`


## Methods

- `Void OnAllClick()`

- `Void OnBossClick()`

- `Void OnEliteClick()`

- `Void SetEnemyLevelShuffle(EnemyLevelMask)`

- `Void _StopAllTween()`

- `Single _GetAlpha(EnemyLevelMask, EnemyLevelMask)`

- `Single _GetPos(EnemyLevelMask)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyHandBook
public class EnemyHandbookBossShuffleObject : MonoBehaviour, IHotfixable
{
	private Single CHANGE_DURATION; // 0x18
	private Text _allText; // 0x20
	private Text _elteText; // 0x28
	private Text _bossText; // 0x30
	private Transform _bar; // 0x38
	private Single _allPos; // 0x40
	private Single _elitePos; // 0x44
	private Single _bossPos; // 0x48
	public UnityEnemyLevelEvent enemyLevelEvent; // 0x50
	private List`1 m_cacheTweenList; // 0x58
	private static DelegateBridge __Hotfix0_OnAllClick; // 0x0
	private static DelegateBridge __Hotfix0_OnBossClick; // 0x8
	private static DelegateBridge __Hotfix0_OnEliteClick; // 0x10
	private static DelegateBridge __Hotfix0_SetEnemyLevelShuffle; // 0x18
	private static DelegateBridge __Hotfix0__StopAllTween; // 0x20
	private static DelegateBridge __Hotfix0__GetAlpha; // 0x28
	private static DelegateBridge __Hotfix0__GetPos; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x29348e8 VA: 0x7594f4c8e8
	public Void OnAllClick() { }
	// RVA: 0x293497c VA: 0x7594f4c97c
	public Void OnBossClick() { }
	// RVA: 0x2934a10 VA: 0x7594f4ca10
	public Void OnEliteClick() { }
	// RVA: 0x2934aa4 VA: 0x7594f4caa4
	public Void SetEnemyLevelShuffle(EnemyLevelMask lvlType) { }
	// RVA: 0x2934db8 VA: 0x7594f4cdb8
	private Void _StopAllTween() { }
	// RVA: 0x2934edc VA: 0x7594f4cedc
	private Single _GetAlpha(EnemyLevelMask type1, EnemyLevelMask type2) { }
	// RVA: 0x2934f6c VA: 0x7594f4cf6c
	private Single _GetPos(EnemyLevelMask type1) { }
	// RVA: 0x2935008 VA: 0x7594f4d008
	public Void .ctor() { }
}
```