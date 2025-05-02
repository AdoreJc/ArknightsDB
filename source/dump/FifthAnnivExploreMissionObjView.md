# FifthAnnivExploreMissionObjView

**Namespace:** ` `


## Fields

- `Single _itemCardScale`

- `Color _textDescCompletedColor`

- `Color _textDescInprogressColor`

- `Color _textProgressValueColor`

- `Color _textProgressTargetColor`

- `Text _textDesc`

- `Text _textProgress`

- `Slider _sliderProgress`

- `GameObject _panelCompleted`

- `GameObject _panelInprogress`

- `GameObject _imageRewardGot`

- `Button _buttonSelf`

- `String m_missionId`

- `Boolean m_isInited`

- `UIStringEvent <onClicked>k__BackingField`


## Properties

- `UIStringEvent onClicked`


## Methods

- `UIStringEvent get_onClicked()`

- `Void set_onClicked(UIStringEvent)`

- `Void Render(MissionViewModel)`

- `Void _RenderItemList(MissionViewModel)`

- `Void EventOnClicked()`

- `Void _EventOnItemClicked(Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FifthAnnivExploreMissionObjView : MonoBehaviour, IHotfixable
{
	private Single _itemCardScale; // 0x18
	private Color _textDescCompletedColor; // 0x1c
	private Color _textDescInprogressColor; // 0x2c
	private Color _textProgressValueColor; // 0x3c
	private Color _textProgressTargetColor; // 0x4c
	private Text _textDesc; // 0x60
	private Text _textProgress; // 0x68
	private Slider _sliderProgress; // 0x70
	private GameObject _panelCompleted; // 0x78
	private GameObject _panelInprogress; // 0x80
	private GameObject _imageRewardGot; // 0x88
	private Button _buttonSelf; // 0x90
	private List`1 _notHaveImgList; // 0x98
	private List`1 _itemContainerList; // 0xa0
	private String m_missionId; // 0xa8
	private List`1 m_itemCardList; // 0xb0
	private Boolean m_isInited; // 0xb8
	private const String COLORED_PROGRESS_TEXT_FORMAT; // 0x0
	private UIStringEvent <onClicked>k__BackingField; // 0xc0
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__RenderItemList; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x20
	private static DelegateBridge __Hotfix0__EventOnItemClicked; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private UIStringEvent onClicked { get; set; }

	// RVA: 0x1b3a154 VA: 0x7594152154
	private UIStringEvent get_onClicked() { }
	// RVA: 0x1b3a1bc VA: 0x75941521bc
	public Void set_onClicked(UIStringEvent value) { }
	// RVA: 0x1b3a240 VA: 0x7594152240
	public Void Render(MissionViewModel model) { }
	// RVA: 0x1b3a918 VA: 0x7594152918
	private Void _RenderItemList(MissionViewModel model) { }
	// RVA: 0x1b3ac4c VA: 0x7594152c4c
	public Void EventOnClicked() { }
	// RVA: 0x1b3acf4 VA: 0x7594152cf4
	private Void _EventOnItemClicked(Int32 index) { }
	// RVA: 0x1b3a5e8 VA: 0x75941525e8
	private Void _InitIfNot() { }
	// RVA: 0x1b3add0 VA: 0x7594152dd0
	public Void .ctor() { }
}
```