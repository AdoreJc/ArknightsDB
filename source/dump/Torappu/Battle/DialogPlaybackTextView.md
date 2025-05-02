# DialogPlaybackTextView

**Namespace:** `Torappu.Battle`


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
// Namespace : Torappu.Battle
public class DialogPlaybackTextView : MonoBehaviour, IHotfixable
{
	private Text _name; // 0x18
	private Text _content; // 0x20
	private GameObject _current; // 0x28
	private GameObject _options; // 0x30
	private UIAtlasImage[] _optionsChosen; // 0x38
	private Single _contentPadding; // 0x40
	private SizeCalculator m_sizeCalculator; // 0x48
	private static DelegateBridge __Hotfix0__Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderDecision; // 0x8
	private static DelegateBridge __Hotfix0__GetSizeCalculator; // 0x10
	private static DelegateBridge __Hotfix0__ConvertDialogToDecision; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1c45c0c VA: 0x759425dc0c
	private Void _Render(Options options) { }
	// RVA: 0x1c45d1c VA: 0x759425dd1c
	private Void _RenderDecision(String content, Int32 optionIdx) { }
	// RVA: 0x1c45e50 VA: 0x759425de50
	public SizeCalculator _GetSizeCalculator() { }
	// RVA: 0x1c45f98 VA: 0x759425df98
	private static String _ConvertDialogToDecision(String dialogContent, Int32 optIndex) { }
	// RVA: 0x1c46220 VA: 0x759425e220
	public Void .ctor() { }
}
```