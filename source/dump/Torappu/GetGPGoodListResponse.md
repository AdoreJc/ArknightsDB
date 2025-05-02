# GetGPGoodListResponse

**Namespace:** `Torappu`


## Fields

- `PeriodicityGroup weeklyGroup`

- `PeriodicityGroup monthlyGroup`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GetGPGoodListResponse : PlayerDeltaResponse, IShopGetResposne
{
	public PeriodicityGroup weeklyGroup; // 0x28
	public PeriodicityGroup monthlyGroup; // 0x30
	public List`1 monthlySub; // 0x38
	public List`1 levelGP; // 0x40
	public List`1 oneTimeGP; // 0x48
	public List`1 chooseGroup; // 0x50
	public List`1 condtionTriggerGroup; // 0x58


	// RVA: 0x32cd0ec VA: 0x75958e50ec
	public Void .ctor() { }
}
```