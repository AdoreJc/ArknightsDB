# HomeMailArchiveItemView

**Namespace:** `Torappu.UI.Home`


## Fields

- `GameObject _panelTitle`

- `Text _textYear`

- `GameObject _panelItem`

- `Image _imgAvatar`

- `Text _textTitle`

- `Text _textSender`

- `Text _textReceiveDate`

- `RectTransform _itemCardContainer`

- `Single _itemCardScale`

- `Boolean m_hasInited`

- `UIItemCard m_itemCard`

- `UIStateFinder m_stateFinder`

- `String m_cachedItemId`


## Methods

- `Void Render(HomeMailArchiveItemViewModel)`

- `Void EventOnClicked()`

- `Void _InitIfNot()`

- `Void _OnItemCardClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailArchiveItemView : MonoBehaviour, IHotfixable
{
	private GameObject _panelTitle; // 0x18
	private Text _textYear; // 0x20
	private GameObject _panelItem; // 0x28
	private Image _imgAvatar; // 0x30
	private Text _textTitle; // 0x38
	private Text _textSender; // 0x40
	private Text _textReceiveDate; // 0x48
	private RectTransform _itemCardContainer; // 0x50
	private Single _itemCardScale; // 0x58
	private Boolean m_hasInited; // 0x5c
	private UIItemCard m_itemCard; // 0x60
	private UIStateFinder m_stateFinder; // 0x68
	private String m_cachedItemId; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnItemCardClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x28465b4 VA: 0x7594e5e5b4
	public Void Render(HomeMailArchiveItemViewModel model) { }
	// RVA: 0x28469c4 VA: 0x7594e5e9c4
	public Void EventOnClicked() { }
	// RVA: 0x28467b8 VA: 0x7594e5e7b8
	private Void _InitIfNot() { }
	// RVA: 0x2846ac4 VA: 0x7594e5eac4
	private Void _OnItemCardClick(Int32 _) { }
	// RVA: 0x2846bcc VA: 0x7594e5ebcc
	public Void .ctor() { }
}
```