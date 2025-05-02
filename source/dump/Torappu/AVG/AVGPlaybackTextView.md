# AVGPlaybackTextView

**Namespace:** `Torappu.AVG`


## Fields

- `Text _name`

- `Text _content`

- `GameObject _current`

- `GameObject _options`

- `Single _contentPadding`

- `SizeCalculator m_sizeCalculator`


## Methods

- `Void _Render(Options)`

- `Void _RenderDecision(String, Int32)`

- `SizeCalculator _GetSizeCalculator()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGPlaybackTextView : MonoBehaviour, IHotfixable
{
	private Text _name; // 0x18
	private Text _content; // 0x20
	private GameObject _current; // 0x28
	private GameObject _options; // 0x30
	private Image[] _optionsChosen; // 0x38
	private Single _contentPadding; // 0x40
	private SizeCalculator m_sizeCalculator; // 0x48
	private static DelegateBridge __Hotfix0__Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderDecision; // 0x8
	private static DelegateBridge __Hotfix0__GetSizeCalculator; // 0x10
	private static DelegateBridge __Hotfix0__ConvertDialogToDecision; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3ea7bcc VA: 0x75964bfbcc
	private Void _Render(Options options) { }
	// RVA: 0x3ea7cdc VA: 0x75964bfcdc
	private Void _RenderDecision(String content, Int32 optionIdx) { }
	// RVA: 0x3ea7e10 VA: 0x75964bfe10
	private SizeCalculator _GetSizeCalculator() { }
	// RVA: 0x3ea7fb8 VA: 0x75964bffb8
	private static String _ConvertDialogToDecision(String dialogContent, Int32 optIndex) { }
	// RVA: 0x3ea8240 VA: 0x75964c0240
	public Void .ctor() { }
}
```