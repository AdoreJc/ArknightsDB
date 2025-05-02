# PanelCharacterInfo

**Namespace:** `Torappu.Gacha`


## Fields

- `Text _nameCn`

- `Text _nameEn`

- `Image _newImage`

- `Image _professionImage`

- `PanelItemInfo _itemInfo`

- `Transform _gridContainer`


## Methods

- `Void SetData(CharacterData, EvolvePhase, ItemBundle[], Boolean, ProfessionSpriteHub)`

- `Sprite _GetProfessionSprite(ProfessionCategory, ProfessionSpriteHub)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gacha
public class PanelCharacterInfo : MonoBehaviour
{
	private Text _nameCn; // 0x18
	private Text _nameEn; // 0x20
	private Image _newImage; // 0x28
	private Image _professionImage; // 0x30
	private PanelItemInfo _itemInfo; // 0x38
	private Transform _gridContainer; // 0x40


	// RVA: 0x35cb598 VA: 0x7595be3598
	public Void SetData(CharacterData character, EvolvePhase evolvePhase, ItemBundle[] itemList, Boolean isNew, ProfessionSpriteHub professionHub) { }
	// RVA: 0x35cb888 VA: 0x7595be3888
	private Sprite _GetProfessionSprite(ProfessionCategory profession, ProfessionSpriteHub professionHub) { }
	// RVA: 0x35cb92c VA: 0x7595be392c
	public Void .ctor() { }
}
```