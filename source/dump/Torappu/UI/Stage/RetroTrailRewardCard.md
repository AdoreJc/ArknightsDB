# RetroTrailRewardCard

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _backImgAbleToGet`

- `GameObject _backImgHaveEnoughStar`

- `GameObject _backImgNormal`

- `GameObject _backImgAlreadyGet`

- `GameObject _clickAblePart`

- `Text _coloredText1`

- `Text _coloredText2`

- `UIColorGraphic _colorGraphic`

- `Text _starCount`

- `Transform _itemContainer`

- `Single _scalePercent`

- `Text _itemName`

- `Image _coloredImg1`

- `Image _coloredImg2`

- `Image _coloredImg3`

- `Image _nameBack`

- `CanvasGroup _canvasGroup`

- `UIStringEvent onClickEvent`

- `SideStoryTrailViewModel m_viewModel`

- `UIItemCard m_itemCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnClick()`

- `Void _OnItemClicked(Int32)`

- `Void Render(SideStoryTrailViewModel, Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class RetroTrailRewardCard : MonoBehaviour, IHotfixable
{
	private GameObject _backImgAbleToGet; // 0x18
	private GameObject _backImgHaveEnoughStar; // 0x20
	private GameObject _backImgNormal; // 0x28
	private GameObject _backImgAlreadyGet; // 0x30
	private GameObject _clickAblePart; // 0x38
	private Text _coloredText1; // 0x40
	private Text _coloredText2; // 0x48
	private UIColorGraphic _colorGraphic; // 0x50
	private Text _starCount; // 0x58
	private Transform _itemContainer; // 0x60
	private Single _scalePercent; // 0x68
	private Text _itemName; // 0x70
	private Image _coloredImg1; // 0x78
	private Image _coloredImg2; // 0x80
	private Image _coloredImg3; // 0x88
	private Image _nameBack; // 0x90
	private CanvasGroup _canvasGroup; // 0x98
	public UIStringEvent onClickEvent; // 0xa0
	private SideStoryTrailViewModel m_viewModel; // 0xa8
	private UIItemCard m_itemCard; // 0xb0
	private Boolean m_isInited; // 0xb8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f140d4 VA: 0x759552c0d4
	public Void _InitIfNot() { }
	// RVA: 0x2f142dc VA: 0x759552c2dc
	public Void OnClick() { }
	// RVA: 0x2f143a4 VA: 0x759552c3a4
	private Void _OnItemClicked(Int32 index) { }
	// RVA: 0x2f144ac VA: 0x759552c4ac
	public Void Render(SideStoryTrailViewModel viewModel, Color themeColor) { }
	// RVA: 0x2f14930 VA: 0x759552c930
	public Void .ctor() { }
}
```