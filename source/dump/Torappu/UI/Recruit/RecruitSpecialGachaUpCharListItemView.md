# RecruitSpecialGachaUpCharListItemView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelSelected`

- `UIAtlasImage _imgCharPortrait`

- `Image _imgCharProfession`

- `Image _imgCharRarity`

- `Text _textCharName`

- `UICompDialogFinder m_dialogFinder`

- `RarityRank m_cachedRarityRank`


## Methods

- `Void Render(RecruitSpecialGachaUpCharCardViewModel)`

- `Void EventOnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialGachaUpCharListItemView : MonoBehaviour, IHotfixable
{
	private GameObject _panelEmpty; // 0x18
	private GameObject _panelSelected; // 0x20
	private UIAtlasImage _imgCharPortrait; // 0x28
	private Image _imgCharProfession; // 0x30
	private Image _imgCharRarity; // 0x38
	private Text _textCharName; // 0x40
	private UICompDialogFinder m_dialogFinder; // 0x48
	private RarityRank m_cachedRarityRank; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBtnClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2704504 VA: 0x7594d1c504
	public Void Render(RecruitSpecialGachaUpCharCardViewModel viewModel) { }
	// RVA: 0x27046b0 VA: 0x7594d1c6b0
	public Void EventOnBtnClicked() { }
	// RVA: 0x27047a0 VA: 0x7594d1c7a0
	public Void .ctor() { }
}
```