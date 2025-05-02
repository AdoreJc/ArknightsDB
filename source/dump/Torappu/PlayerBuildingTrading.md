# PlayerBuildingTrading

**Namespace:** `Torappu`


## Fields

- `PlayerBuildingTradingBuff buff`

- `PlayerRoomState state`

- `DateTime lastUpdateTime`

- `OrderType strategy`

- `Int32 stockLimit`

- `Int32 apCost`

- `PlayerBuildingTradingNext next`

- `BuildingBuffDisplay display`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerBuildingTrading
{
	public PlayerBuildingTradingBuff buff; // 0x10
	public PlayerRoomState state; // 0x18
	public DateTime lastUpdateTime; // 0x20
	public OrderType strategy; // 0x28
	public Int32 stockLimit; // 0x2c
	public Int32 apCost; // 0x30
	public List`1 stock; // 0x38
	public PlayerBuildingTradingNext next; // 0x40
	public BuildingBuffDisplay display; // 0x48
	public List`1 presetQueue; // 0x50


	// RVA: 0x32d724c VA: 0x75958ef24c
	public Void .ctor() { }
}
```