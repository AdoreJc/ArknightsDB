# RecruitAttainDetailView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Image _starSprite`

- `Text _textTotal`

- `Text _textTitle1`

- `Text _textTitle2`

- `RecruitAttainItemAdapter _adapter`

- `LayoutElement _element`

- `RectTransform _viewPort`

- `Graphic _scrollViewBg`

- `GameObject _panelImgBlack`

- `GridLayoutGroup _attainCharLayout`


## Methods

- `Void Render(String, GachaAvailChar, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitAttainDetailView : MonoBehaviour, IHotfixable
{
	private const Single PREFERED_HEIGHT_1; // 0x0
	private const Single PREFERED_HEIGHT_2; // 0x0
	private const Single VIEW_PORT_Y_1; // 0x0
	private const Single VIEW_PORT_Y_2; // 0x0
	private const Int32 NORMAL_BOTTOM; // 0x0
	private const Int32 MULTILINE_BOTTOM; // 0x0
	private Image _starSprite; // 0x18
	private Text _textTotal; // 0x20
	private Text _textTitle1; // 0x28
	private Text _textTitle2; // 0x30
	private RecruitAttainItemAdapter _adapter; // 0x38
	private LayoutElement _element; // 0x40
	private RectTransform _viewPort; // 0x48
	private Graphic _scrollViewBg; // 0x50
	private GameObject _panelImgBlack; // 0x58
	private GridLayoutGroup _attainCharLayout; // 0x60
	private List`1 m_attainCharList; // 0x68
	private List`1 m_charIdList; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x270eb80 VA: 0x7594d26b80
	public Void Render(String poolId, GachaAvailChar availChar, String param) { }
	// RVA: 0x270f1b0 VA: 0x7594d271b0
	public Void .ctor() { }
}
```