# Act12D6GameEndStatsView

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Image _imageInitRelic`

- `Text _textNickName`

- `Text _textInitRelicName`

- `Text _textTotalTime`

- `Text _textEndTime`

- `Text _textSuc`

- `Text _textFail`

- `Text _textEndingOrZoneName`

- `Text _textEndingDesc`

- `Text _textRelicCount`

- `Text _textCharCount`

- `SimpleLayoutContent _relicContent`

- `SimpleLayoutContent _charContent`

- `Boolean m_inited`

- `RelicAdapter m_relicAdapter`

- `CharAdapter m_charAdapter`


## Methods

- `Void Render(Act12D6GameEndViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6GameEndStatsView : MonoBehaviour, IHotfixable
{
	private Image _imageInitRelic; // 0x18
	private Text _textNickName; // 0x20
	private Text _textInitRelicName; // 0x28
	private Text _textTotalTime; // 0x30
	private Text _textEndTime; // 0x38
	private Text _textSuc; // 0x40
	private Text _textFail; // 0x48
	private Text _textEndingOrZoneName; // 0x50
	private Text _textEndingDesc; // 0x58
	private Text _textRelicCount; // 0x60
	private Text _textCharCount; // 0x68
	private SimpleLayoutContent _relicContent; // 0x70
	private SimpleLayoutContent _charContent; // 0x78
	private Boolean m_inited; // 0x80
	private RelicAdapter m_relicAdapter; // 0x88
	private CharAdapter m_charAdapter; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3474358 VA: 0x7595a8c358
	public Void Render(Act12D6GameEndViewModel viewModel) { }
	// RVA: 0x3474984 VA: 0x7595a8c984
	private Void _InitIfNot() { }
	// RVA: 0x3474b34 VA: 0x7595a8cb34
	public Void .ctor() { }
}
```