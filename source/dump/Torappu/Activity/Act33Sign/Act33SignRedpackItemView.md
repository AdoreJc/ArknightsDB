# Act33SignRedpackItemView

**Namespace:** `Torappu.Activity.Act33Sign`


## Fields

- `Text _textTips`

- `Image _imgNumber`

- `Image _imgTitle`

- `Image _imgDesc`

- `GameObject _panelGot`

- `Button _redpackBtn`

- `GameObject _itemPanel`

- `Text _textCount`


## Methods

- `Void Render(Act33SignRedpackItemViewModel)`

- `Void _RenderRewards(ItemBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act33Sign
public class Act33SignRedpackItemView : MonoBehaviour, IHotfixable
{
	private Text _textTips; // 0x18
	private Image _imgNumber; // 0x20
	private Image _imgTitle; // 0x28
	private Image _imgDesc; // 0x30
	private GameObject _panelGot; // 0x38
	private Button _redpackBtn; // 0x40
	private GameObject _itemPanel; // 0x48
	private Text _textCount; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderRewards; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3255cfc VA: 0x759586dcfc
	public Void Render(Act33SignRedpackItemViewModel viewModel) { }
	// RVA: 0x32563a0 VA: 0x759586e3a0
	private Void _RenderRewards(ItemBundle item) { }
	// RVA: 0x325650c VA: 0x759586e50c
	public Void .ctor() { }
}
```