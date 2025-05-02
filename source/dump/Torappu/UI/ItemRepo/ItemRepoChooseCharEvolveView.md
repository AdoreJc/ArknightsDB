# ItemRepoChooseCharEvolveView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Image _charProtrait`

- `Image _professionImg`

- `Image _eliteImg`

- `Text _levelTxt`

- `GameObject _skillCoverImg`

- `GameObject _hotspot`

- `CharClickEvent onClickEvent`

- `CharacterCardViewModel m_cacheCharViewModel`


## Methods

- `Void OnClick()`

- `Void Render(CharacterCardViewModel, Boolean, CharCardType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoChooseCharEvolveView : MonoBehaviour, IHotfixable
{
	private Image _charProtrait; // 0x18
	private Image _professionImg; // 0x20
	private Image _eliteImg; // 0x28
	private Text _levelTxt; // 0x30
	private GameObject _skillCoverImg; // 0x38
	private ItemRepoChooseCharSkillView[] _skillItems; // 0x40
	private GameObject _hotspot; // 0x48
	public CharClickEvent onClickEvent; // 0x50
	private CharacterCardViewModel m_cacheCharViewModel; // 0x58
	private static DelegateBridge __Hotfix0_OnClick; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d33394 VA: 0x759534b394
	public Void OnClick() { }
	// RVA: 0x2d32ee4 VA: 0x759534aee4
	public Void Render(CharacterCardViewModel charViewModel, Boolean clickable, CharCardType cardType) { }
	// RVA: 0x2d33558 VA: 0x759534b558
	public Void .ctor() { }
}
```