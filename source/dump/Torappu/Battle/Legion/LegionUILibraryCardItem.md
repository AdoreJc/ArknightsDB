# LegionUILibraryCardItem

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `Image _avatarImage`

- `Image _professionIcon`

- `Image _professionMark`

- `Image _rarityMark`

- `Text _costLabel`

- `Image _eliteIcon`


## Methods

- `Void ApplyData(Card)`

- `Void _SetProfession(ProfessionCategory)`

- `Void _SetRarityRank(RarityRank)`

- `Void _SetEvolvePhase(EvolvePhase)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Legion
public class LegionUILibraryCardItem : MonoBehaviour, IHotfixable
{
	private Image _avatarImage; // 0x18
	private Image _professionIcon; // 0x20
	private Image _professionMark; // 0x28
	private Image _rarityMark; // 0x30
	private Text _costLabel; // 0x38
	private Image _eliteIcon; // 0x40
	private ProfessionData[] _professionData; // 0x48
	private Sprite[] _rarityColors; // 0x50
	private Sprite[] _evolveIcons; // 0x58
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__SetProfession; // 0x8
	private static DelegateBridge __Hotfix0__SetRarityRank; // 0x10
	private static DelegateBridge __Hotfix0__SetEvolvePhase; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1dbfe54 VA: 0x75943d7e54
	public Void ApplyData(Card card) { }
	// RVA: 0x1dbffd4 VA: 0x75943d7fd4
	private Void _SetProfession(ProfessionCategory profession) { }
	// RVA: 0x1dc00f8 VA: 0x75943d80f8
	private Void _SetRarityRank(RarityRank rarity) { }
	// RVA: 0x1dc01a0 VA: 0x75943d81a0
	private Void _SetEvolvePhase(EvolvePhase evolvePhase) { }
	// RVA: 0x1dc0310 VA: 0x75943d8310
	public Void .ctor() { }
}
```