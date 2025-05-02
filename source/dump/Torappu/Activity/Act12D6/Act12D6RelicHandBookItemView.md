# Act12D6RelicHandBookItemView

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Image _imgRelicIcon`

- `Image _imageChosen`

- `Text _textName`

- `GameObject _imageNew`

- `GameObject _imageLock`

- `Image _imgRelicBg`

- `Color _lockedBgColor`

- `Color _unlockedBgColor`

- `String m_relicId`

- `UIStringEvent <onRelicClicked>k__BackingField`


## Properties

- `UIStringEvent onRelicClicked`


## Methods

- `UIStringEvent get_onRelicClicked()`

- `Void set_onRelicClicked(UIStringEvent)`

- `Void Render(PlayerRelicHandBookData, Boolean)`

- `Void EventOnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6RelicHandBookItemView : MonoBehaviour, IHotfixable
{
	private Image _imgRelicIcon; // 0x18
	private Image _imageChosen; // 0x20
	private Text _textName; // 0x28
	private GameObject _imageNew; // 0x30
	private GameObject _imageLock; // 0x38
	private Image _imgRelicBg; // 0x40
	private Color _lockedBgColor; // 0x48
	private Color _unlockedBgColor; // 0x58
	private String m_relicId; // 0x68
	private UIStringEvent <onRelicClicked>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_onRelicClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onRelicClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public UIStringEvent onRelicClicked { get; set; }

	// RVA: 0x347dc98 VA: 0x7595a95c98
	public UIStringEvent get_onRelicClicked() { }
	// RVA: 0x3478384 VA: 0x7595a90384
	public Void set_onRelicClicked(UIStringEvent value) { }
	// RVA: 0x347817c VA: 0x7595a9017c
	public Void Render(PlayerRelicHandBookData relicData, Boolean chosen) { }
	// RVA: 0x347dd00 VA: 0x7595a95d00
	public Void EventOnClicked() { }
	// RVA: 0x347dda8 VA: 0x7595a95da8
	public Void .ctor() { }
}
```