# UILifeLostGroup

**Namespace:** `Torappu.Battle.UI`


## Fields

- `GameObject _enemyLostLabel`

- `Text _enemyLostPoint`

- `GameObject _othersLostLabel`

- `Text _othersLostPoint`

- `AnimationClip _moveDownAnimation`

- `Animation m_othersLostLabelAnimator`

- `Int32 m_lifePointLossByEnemy`

- `Int32 m_lifePointLossByOthers`


## Properties

- `Int32 lifePointLossByEnemy`

- `Int32 lifePointLossByOthers`


## Methods

- `Void set_lifePointLossByEnemy(Int32)`

- `Void set_lifePointLossByOthers(Int32)`

- `Void UpdateData(BattleController, Boolean, PlayerSide)`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UILifeLostGroup : MonoBehaviour
{
	private GameObject _enemyLostLabel; // 0x18
	private Text _enemyLostPoint; // 0x20
	private GameObject _othersLostLabel; // 0x28
	private Text _othersLostPoint; // 0x30
	private AnimationClip _moveDownAnimation; // 0x38
	private Animation m_othersLostLabelAnimator; // 0x40
	private Int32 m_lifePointLossByEnemy; // 0x48
	private const String LOST_POINT_FORMAT; // 0x0
	private Int32 m_lifePointLossByOthers; // 0x4c

	private Int32 lifePointLossByEnemy { set; }
	private Int32 lifePointLossByOthers { set; }

	// RVA: 0x2081408 VA: 0x7594699408
	private Void set_lifePointLossByEnemy(Int32 value) { }
	// RVA: 0x2081568 VA: 0x7594699568
	private Void set_lifePointLossByOthers(Int32 value) { }
	// RVA: 0x2077650 VA: 0x759468f650
	public Void UpdateData(BattleController controller, Boolean force, PlayerSide side) { }
	// RVA: 0x2081690 VA: 0x7594699690
	private Void Awake() { }
	// RVA: 0x20816f0 VA: 0x75946996f0
	public Void .ctor() { }
}
```