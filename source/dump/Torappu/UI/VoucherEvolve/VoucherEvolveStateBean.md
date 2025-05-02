# VoucherEvolveStateBean

**Namespace:** `Torappu.UI.VoucherEvolve`


## Fields

- `CharacterCardViewModel charViewModel`

- `UIItemViewModel itemViewModel`

- `EvolvePhase targetEvolvePhase`

- `Int32 chrInstId`

- `String charId`

- `CharUISkinStruct oldSkinStruct`

- `CharUISkinStruct newSkinStruct`

- `RarityRank rarity`

- `String nickName`

- `String realName`


## Methods

- `Void LoadData(CharacterCardViewModel, UIItemViewModel, EvolvePhase)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoucherEvolve
public class VoucherEvolveStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public CharacterCardViewModel charViewModel; // 0x18
	public UIItemViewModel itemViewModel; // 0x20
	public EvolvePhase targetEvolvePhase; // 0x28
	public Int32 chrInstId; // 0x2c
	public String charId; // 0x30
	public CharUISkinStruct oldSkinStruct; // 0x38
	public CharUISkinStruct newSkinStruct; // 0x48
	public RarityRank rarity; // 0x58
	public String nickName; // 0x60
	public String realName; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x229460c VA: 0x75948ac60c
	public Void LoadData(CharacterCardViewModel cardViewModel, UIItemViewModel itemViewModel, EvolvePhase targetEvolve) { }
	// RVA: 0x22959c8 VA: 0x75948ad9c8
	public Void .ctor() { }
}
```