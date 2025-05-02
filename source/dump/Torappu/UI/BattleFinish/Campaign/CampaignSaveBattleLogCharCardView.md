# CampaignSaveBattleLogCharCardView

**Namespace:** `Torappu.UI.BattleFinish.Campaign`


## Fields

- `Image _avatarImage`

- `Image _professionIcon`

- `Image _professionMark`

- `Image _rarityMark`

- `Text _costLabel`


## Methods

- `Boolean Render(CharInfo)`

- `Void _SetAvatar(String, String)`

- `Void _SetProfession(ProfessionCategory)`

- `Void _SetRarityRank(RarityRank)`

- `Void _SetCostValue(CharacterData, CharInfo, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish.Campaign
public class CampaignSaveBattleLogCharCardView : MonoBehaviour
{
	private Image _avatarImage; // 0x18
	private Image _professionIcon; // 0x20
	private Image _professionMark; // 0x28
	private Image _rarityMark; // 0x30
	private Text _costLabel; // 0x38
	private ProfessionData[] _professionData; // 0x40
	private Sprite[] _rarityColors; // 0x48


	// RVA: 0x2e96d44 VA: 0x75954aed44
	public Boolean Render(CharInfo charInfo) { }
	// RVA: 0x2e96fb4 VA: 0x75954aefb4
	private Void _SetAvatar(String charId, String skinId) { }
	// RVA: 0x2e97098 VA: 0x75954af098
	private Void _SetProfession(ProfessionCategory profession) { }
	// RVA: 0x2e9715c VA: 0x75954af15c
	private Void _SetRarityRank(RarityRank rarity) { }
	// RVA: 0x2e97198 VA: 0x75954af198
	private Void _SetCostValue(CharacterData charData, CharInfo charInfo, String charId) { }
	// RVA: 0x2e97400 VA: 0x75954af400
	public Void .ctor() { }
}
```