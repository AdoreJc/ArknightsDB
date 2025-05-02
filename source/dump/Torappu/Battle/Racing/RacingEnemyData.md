# RacingEnemyData

**Namespace:** `Torappu.Battle.Racing`


## Fields

- `String instId`

- `Boolean isMine`

- `String enemyKey`

- `Single maxRacingSpeed`

- `Single racingAcceleration`

- `Single maxRacingHp`

- `Single endurance`

- `Int32 massLevel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Racing
public class RacingEnemyData : IHotfixable
{
	public String instId; // 0x10
	public Boolean isMine; // 0x18
	public String enemyKey; // 0x20
	public Single maxRacingSpeed; // 0x28
	public Single racingAcceleration; // 0x2c
	public Single maxRacingHp; // 0x30
	public Single endurance; // 0x34
	public Int32 massLevel; // 0x38
	public List`1 talentBlackboards; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x1d57e30 VA: 0x759436fe30
	public Void .ctor() { }
}
```