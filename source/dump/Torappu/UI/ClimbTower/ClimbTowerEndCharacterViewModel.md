# ClimbTowerEndCharacterViewModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `CharacterCardViewModel cardModel`

- `Boolean isNpc`

- `Boolean isAssist`


## Methods

- `Void LoadCharacter(GameCard)`

- `Void LoadCharacter(CharacterCardViewModel)`

- `Int32 CompareTo(ClimbTowerEndCharacterViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEndCharacterViewModel : IHotfixable
{
	public CharacterCardViewModel cardModel; // 0x10
	public Boolean isNpc; // 0x18
	public Boolean isAssist; // 0x19
	private static DelegateBridge __Hotfix0_LoadCharacter; // 0x0
	private static DelegateBridge __Hotfix1_LoadCharacter; // 0x8
	private static DelegateBridge __Hotfix0_CompareTo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2c9e448 VA: 0x75952b6448
	public Void LoadCharacter(GameCard card) { }
	// RVA: 0x2c9e53c VA: 0x75952b653c
	public Void LoadCharacter(CharacterCardViewModel charCardModel) { }
	// RVA: 0x2c9e5c8 VA: 0x75952b65c8
	public Int32 CompareTo(ClimbTowerEndCharacterViewModel r) { }
	// RVA: 0x2c9e6ec VA: 0x75952b66ec
	public Void .ctor() { }
}
```