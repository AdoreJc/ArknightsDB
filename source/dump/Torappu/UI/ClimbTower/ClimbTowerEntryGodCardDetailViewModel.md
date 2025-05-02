# ClimbTowerEntryGodCardDetailViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String seasonId`

- `String selectedCardId`

- `Int32 seasonNum`


## Methods

- `Void LoadData()`

- `Void SetSelectId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryGodCardDetailViewModel : IHotfixable
{
	public String seasonId; // 0x10
	public String selectedCardId; // 0x18
	public ListDict`2 cardModelMap; // 0x20
	public Int32 seasonNum; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectId; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2cd6284 VA: 0x75952ee284
	public Void LoadData() { }
	// RVA: 0x2cd666c VA: 0x75952ee66c
	public Void SetSelectId(String selectId) { }
	// RVA: 0x2cd6758 VA: 0x75952ee758
	public Void .ctor() { }
}
```