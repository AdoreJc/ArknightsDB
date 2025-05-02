# DefaultStartBattleRequest

**Namespace:** `Torappu`


## Fields

- `Boolean isRetro`

- `Int32 pry`

- `BattleType battleType`

- `ContinuousBattleModel continuous`

- `StartBattleExtraData extra`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class DefaultStartBattleRequest : CommonStartBattleRequest
{
	public Boolean isRetro; // 0x40
	public Int32 pry; // 0x44
	public BattleType battleType; // 0x48
	public ContinuousBattleModel continuous; // 0x50
	public StartBattleExtraData extra; // 0x58


	// RVA: 0x32cdc88 VA: 0x75958e5c88
	public Void .ctor() { }
}
```