# BasicStatus

**Namespace:** ` `


## Fields

- `GameObject container`

- `UILifePoint lifePoint`

- `Text monsterInfoText`

- `Text killCntText`

- `Transform practiceHint`

- `UILifeLostGroup lifeLostContainer`

- `Int32 m_cachedFinishedEnemiesCnt`

- `Int32 m_cachedTotalEnemiesCnt`


## Methods

- `Void InitData(BattleController)`

- `Void UpdateData(BattleController, Boolean)`

- `Void _UpdateMonsterInfo(BattleController, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BasicStatus
{
	public GameObject container; // 0x10
	public UILifePoint lifePoint; // 0x18
	public Text monsterInfoText; // 0x20
	public Text killCntText; // 0x28
	public Transform practiceHint; // 0x30
	public UILifeLostGroup lifeLostContainer; // 0x38
	private Int32 m_cachedFinishedEnemiesCnt; // 0x40
	private Int32 m_cachedTotalEnemiesCnt; // 0x44


	// RVA: 0x2051444 VA: 0x7594669444
	public Void InitData(BattleController controller) { }
	// RVA: 0x2050b98 VA: 0x7594668b98
	public Void UpdateData(BattleController controller, Boolean force) { }
	// RVA: 0x2051db4 VA: 0x7594669db4
	private Void _UpdateMonsterInfo(BattleController controller, Boolean force) { }
	// RVA: 0x2051f3c VA: 0x7594669f3c
	public Void .ctor() { }
}
```