# HomeSecretarySkinItemModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `String charId`

- `String skinId`

- `Boolean isEvolveSkin`

- `EvolvePhase evolveSkinPhase`

- `Boolean isDynSkin`

- `String skinGroupId`

- `String avatarId`

- `String charNickName`

- `String charRealName`

- `String skinName`

- `RarityRank charRarity`


## Methods

- `Int32 CompareTo(HomeSecretarySkinItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretarySkinItemModel : IHotfixable, IComparable`1
{
	public String charId; // 0x10
	public String skinId; // 0x18
	public Boolean isEvolveSkin; // 0x20
	public EvolvePhase evolveSkinPhase; // 0x24
	public Boolean isDynSkin; // 0x28
	public String skinGroupId; // 0x30
	public String avatarId; // 0x38
	public String charNickName; // 0x40
	public String charRealName; // 0x48
	public String skinName; // 0x50
	public RarityRank charRarity; // 0x58
	private static DelegateBridge __Hotfix0_CompareTo; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2819668 VA: 0x7594e31668
	public Int32 CompareTo(HomeSecretarySkinItemModel other) { }
	// RVA: 0x2818c7c VA: 0x7594e30c7c
	public Void .ctor() { }
}
```