# ExpeditionReturnSingleModel

**Namespace:** ` `


## Fields

- `String topicId`

- `String instId`

- `String charId`

- `String charName`

- `Boolean isUpgrade`


## Methods

- `Void LoadData(String, Troop, Char)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ExpeditionReturnSingleModel : IHotfixable
{
	public String topicId; // 0x10
	public String instId; // 0x18
	public String charId; // 0x20
	public String charName; // 0x28
	public Boolean isUpgrade; // 0x30
	public List`1 rewards; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2bb35ec VA: 0x75951cb5ec
	public Void LoadData(String topicId, Troop playerTroop, Char returnChar) { }
	// RVA: 0x2bb37d0 VA: 0x75951cb7d0
	public Void .ctor() { }
}
```