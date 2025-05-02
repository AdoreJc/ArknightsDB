# EnemyHandbookLinkEnemyItem

**Namespace:** `Torappu.UI.EnemyHandBook`


## Fields

- `GameObject _lockedState`

- `GameObject _availState`

- `Text _enemyName`

- `Image _enemyImg`

- `UIStringEvent onJumpToLinkEnemy`

- `LinkEnemy m_cacheViewModel`


## Methods

- `Void Render(LinkEnemy)`

- `Void OnJumpToLinkEnemy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyHandBook
public class EnemyHandbookLinkEnemyItem : MonoBehaviour, IHotfixable
{
	private GameObject _lockedState; // 0x18
	private GameObject _availState; // 0x20
	private Text _enemyName; // 0x28
	private Image _enemyImg; // 0x30
	public UIStringEvent onJumpToLinkEnemy; // 0x38
	private LinkEnemy m_cacheViewModel; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnJumpToLinkEnemy; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2936944 VA: 0x7594f4e944
	public Void Render(LinkEnemy linkEnemy) { }
	// RVA: 0x2936a4c VA: 0x7594f4ea4c
	public Void OnJumpToLinkEnemy() { }
	// RVA: 0x2936ae8 VA: 0x7594f4eae8
	public Void .ctor() { }
}
```