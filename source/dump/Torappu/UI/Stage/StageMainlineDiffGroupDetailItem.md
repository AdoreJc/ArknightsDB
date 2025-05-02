# StageMainlineDiffGroupDetailItem

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIAtlasImage _startButton`

- `String _normalStartButton`

- `String _toughStartButton`

- `Color _normalBackShiningColor`

- `Color _toughBackShiningColor`

- `Image _selectColor`

- `Text _detailText`

- `Text _buttonState`

- `UIColorGraphic _lockColorMask`

- `Color _lockedColor`

- `GameObject _lockState`

- `Button _clickBtn`

- `Image _diffIcon`

- `Text _diffName`

- `UIAtlasImage _backImage`

- `UIAtlasObject _atlasHub`

- `String _commonBack`

- `String _toughBack`

- `DiffInfo m_cacheDiffInfo`


## Methods

- `Void OnClick()`

- `Void Render(ZoneViewModel, DiffInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageMainlineDiffGroupDetailItem : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _startButton; // 0x18
	private String _normalStartButton; // 0x20
	private String _toughStartButton; // 0x28
	private Color _normalBackShiningColor; // 0x30
	private Color _toughBackShiningColor; // 0x40
	private Image _selectColor; // 0x50
	private Text _detailText; // 0x58
	private Text _buttonState; // 0x60
	private UIColorGraphic _lockColorMask; // 0x68
	private Color _lockedColor; // 0x70
	private GameObject _lockState; // 0x80
	private Button _clickBtn; // 0x88
	private Image _diffIcon; // 0x90
	private Text _diffName; // 0x98
	private UIAtlasImage _backImage; // 0xa0
	private UIAtlasObject _atlasHub; // 0xa8
	private String _commonBack; // 0xb0
	private String _toughBack; // 0xb8
	public Action`1 diffGroupEvent; // 0xc0
	private DiffInfo m_cacheDiffInfo; // 0xc8
	private static DelegateBridge __Hotfix0_OnClick; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2f8d378 VA: 0x75955a5378
	public Void OnClick() { }
	// RVA: 0x2f8d408 VA: 0x75955a5408
	public Void Render(ZoneViewModel zoneViewModel, DiffInfo diffInfo) { }
	// RVA: 0x2f8d840 VA: 0x75955a5840
	public Void .ctor() { }
}
```