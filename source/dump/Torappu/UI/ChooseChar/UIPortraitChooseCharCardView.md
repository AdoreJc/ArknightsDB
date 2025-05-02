# UIPortraitChooseCharCardView

**Namespace:** `Torappu.UI.ChooseChar`


## Fields

- `GameObject _panelOwned`

- `Image _imgPotential`

- `GameObject _panelSelected`

- `UIAtlasImage _imgCharPortrait`

- `Image _imgProfessor`

- `Image _imgRarityRank`

- `Text _textName`

- `UICompDialogFinder m_dialogFinder`

- `String m_cachedCharId`


## Methods

- `Void Render(UIPortraitChooseCharCardViewModel, Boolean)`

- `Void EventOnCardClicked()`

- `Void EventOnCardDetailClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChooseChar
public class UIPortraitChooseCharCardView : MonoBehaviour, IHotfixable
{
	private GameObject _panelOwned; // 0x18
	private Image _imgPotential; // 0x20
	private GameObject _panelSelected; // 0x28
	private UIAtlasImage _imgCharPortrait; // 0x30
	private Image _imgProfessor; // 0x38
	private Image _imgRarityRank; // 0x40
	private Text _textName; // 0x48
	private UICompDialogFinder m_dialogFinder; // 0x50
	private String m_cachedCharId; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnCardClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnCardDetailClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2c3dbc4 VA: 0x7595255bc4
	public Void Render(UIPortraitChooseCharCardViewModel model, Boolean isSelected) { }
	// RVA: 0x2c3e234 VA: 0x7595256234
	public Void EventOnCardClicked() { }
	// RVA: 0x2c3e334 VA: 0x7595256334
	public Void EventOnCardDetailClicked() { }
	// RVA: 0x2c3e434 VA: 0x7595256434
	public Void .ctor() { }
}
```