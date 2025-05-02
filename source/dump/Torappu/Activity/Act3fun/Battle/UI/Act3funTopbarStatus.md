# Act3funTopbarStatus

**Namespace:** `Torappu.Activity.Act3fun.Battle.UI`


## Fields

- `GameObject container`

- `Animation killCntIconAnimation`

- `Text killCntText`

- `Text battleTimeText`

- `Int32 m_killCnt`

- `Int32 m_playTime`


## Methods

- `Void Init(Transform)`

- `Void UpdateData(BattleController, Boolean)`

- `Void _UpdateBattleTimeInfo(BattleController)`

- `Void _UpdateKillCntInfo(BattleController)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3fun.Battle.UI
public class Act3funTopbarStatus
{
	public GameObject container; // 0x10
	public Animation killCntIconAnimation; // 0x18
	public Text killCntText; // 0x20
	public Text battleTimeText; // 0x28
	private Int32 m_killCnt; // 0x30
	private Int32 m_playTime; // 0x34


	// RVA: 0x32229b8 VA: 0x759583a9b8
	public Void Init(Transform parent) { }
	// RVA: 0x3222bb8 VA: 0x759583abb8
	public Void UpdateData(BattleController controller, Boolean force) { }
	// RVA: 0x3222fe8 VA: 0x759583afe8
	private Void _UpdateBattleTimeInfo(BattleController controller) { }
	// RVA: 0x3222f00 VA: 0x759583af00
	private Void _UpdateKillCntInfo(BattleController controller) { }
	// RVA: 0x3223150 VA: 0x759583b150
	public Void .ctor() { }
}
```