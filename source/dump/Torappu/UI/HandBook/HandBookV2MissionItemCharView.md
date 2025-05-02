# HandBookV2MissionItemCharView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `GameObject _normalGo`

- `Text _textName`

- `Text _textDisplayNumber`

- `Image _imgChar`

- `GameObject _greyGo`

- `Text _textUnknown`

- `GameObject _sliderGo`

- `RectTransform _rtSlider`

- `Single _sliderMin`

- `Single _sliderMax`


## Methods

- `Void Render(Int32, CharacterFavorData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MissionItemCharView : MonoBehaviour, IHotfixable
{
	private GameObject _normalGo; // 0x18
	private Text _textName; // 0x20
	private Text _textDisplayNumber; // 0x28
	private Image _imgChar; // 0x30
	private GameObject _greyGo; // 0x38
	private Text _textUnknown; // 0x40
	private GameObject _sliderGo; // 0x48
	private RectTransform _rtSlider; // 0x50
	private Single _sliderMin; // 0x58
	private Single _sliderMax; // 0x5c
	private const Int32 FAVOR_MAX; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2ed89f0 VA: 0x75954f09f0
	public Void Render(Int32 favorAvg, CharacterFavorData characterFavorData) { }
	// RVA: 0x2ed8bd4 VA: 0x75954f0bd4
	public Void .ctor() { }
}
```