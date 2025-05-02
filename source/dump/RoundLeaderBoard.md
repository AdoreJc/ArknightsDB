# RoundLeaderBoard

**Namespace:** ` `


## Fields

- `String id`

- `Int32 oldMoney`

- `Int32 newMoney`

- `Int32 maxRound`

- `Int32 streak`

- `EnemyDuelRoundResult result`

- `EnemyDuelChoiceSide bet`

- `EnemyDuelShieldState shieldState`


## Methods

- `Void Read(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoundLeaderBoard : IStreamDeserialize
{
	public String id; // 0x10
	public Int32 oldMoney; // 0x18
	public Int32 newMoney; // 0x1c
	public Int32 maxRound; // 0x20
	public Int32 streak; // 0x24
	public EnemyDuelRoundResult result; // 0x28
	public EnemyDuelChoiceSide bet; // 0x2c
	public EnemyDuelShieldState shieldState; // 0x30


	// RVA: 0x29aaa70 VA: 0x7594fc2a70
	public Void Read(IStreamReader from) { }
	// RVA: 0x29aaddc VA: 0x7594fc2ddc
	public Void .ctor() { }
}
```