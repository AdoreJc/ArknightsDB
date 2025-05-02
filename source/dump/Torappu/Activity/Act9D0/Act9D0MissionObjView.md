# Act9D0MissionObjView

**Namespace:** `Torappu.Activity.Act9D0`


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

- `GameObject _imageOutline`

- `GameObject _imageRewardGot`

- `Button _buttonSelf`

- `Boolean _hideSlideProgressWhenAbleToGet`

- `String m_missionId`

- `Boolean m_useAnimationWrapper`

- `Boolean m_isInited`

- `UIStringEvent <onClicked>k__BackingField`


## Properties

- `UIStringEvent onClicked`


## Methods

- `UIStringEvent get_onClicked()`

- `Void set_onClicked(UIStringEvent)`

- `Void OnDestroy()`

- `Void Render(MissionViewModel)`

- `Void _RenderItemList(MissionViewModel)`

- `Void EventOnClicked()`

- `Void _EventOnItemClicked(Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0MissionObjView : MonoBehaviour, IHotfixable
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
	private GameObject _imageOutline; // 0x88
	private GameObject _imageRewardGot; // 0x90
	private Button _buttonSelf; // 0x98
	private List`1 _notHaveImgList; // 0xa0
	private List`1 _itemContainerList; // 0xa8
	private List`1 _replicateContainerList; // 0xb0
	private List`1 _replicateIconList; // 0xb8
	private List`1 _replicateAnimationList; // 0xc0
	private Boolean _hideSlideProgressWhenAbleToGet; // 0xc8
	private const String SHINING_ANIM; // 0x0
	private String m_missionId; // 0xd0
	private List`1 m_itemCardList; // 0xd8
	private List`1 m_replicateItemCardList; // 0xe0
	private List`1 m_tweens; // 0xe8
	private Boolean m_useAnimationWrapper; // 0xf0
	private Boolean m_isInited; // 0xf1
	private UIStringEvent <onClicked>k__BackingField; // 0xf8
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__RenderItemList; // 0x20
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x28
	private static DelegateBridge __Hotfix0__EventOnItemClicked; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public UIStringEvent onClicked { get; set; }

	// RVA: 0x31a68c0 VA: 0x75957be8c0
	public UIStringEvent get_onClicked() { }
	// RVA: 0x31a6184 VA: 0x75957be184
	public Void set_onClicked(UIStringEvent value) { }
	// RVA: 0x31a6928 VA: 0x75957be928
	private Void OnDestroy() { }
	// RVA: 0x31a6208 VA: 0x75957be208
	public Void Render(MissionViewModel model) { }
	// RVA: 0x31a71b0 VA: 0x75957bf1b0
	private Void _RenderItemList(MissionViewModel model) { }
	// RVA: 0x31a7dc8 VA: 0x75957bfdc8
	public Void EventOnClicked() { }
	// RVA: 0x31a7e70 VA: 0x75957bfe70
	private Void _EventOnItemClicked(Int32 index) { }
	// RVA: 0x31a6ac0 VA: 0x75957beac0
	private Void _InitIfNot() { }
	// RVA: 0x31a8058 VA: 0x75957c0058
	public Void .ctor() { }
}
```