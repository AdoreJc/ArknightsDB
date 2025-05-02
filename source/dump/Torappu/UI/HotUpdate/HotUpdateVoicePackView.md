# HotUpdateVoicePackView

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `GameObject _objCancelBtn`

- `Text _textConfirmBtn`

- `Image _imgNormalConfirm`

- `Image _imgNoticeConfirm`

- `RectTransform _itemContainer`

- `HotUpdateVoicePackItem _itemPrefab`

- `GameObject _linePrefab`

- `Action m_onNextStep`

- `HotUpdateVoicePackViewModel m_viewModel`

- `Boolean m_isInited`


## Methods

- `Void _GeneItemView()`

- `Void _UpdateView()`

- `Void _OnItemClicked(Int32)`

- `Void _DoHotUpdateTrace()`

- `Boolean _ConfirmVoicePackChoice()`

- `Void EventOnBackClicked()`

- `Void EventOnConfirmClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdateVoicePackView : UICustomDialog`1
{
	private GameObject _objCancelBtn; // 0x50
	private Text _textConfirmBtn; // 0x58
	private Image _imgNormalConfirm; // 0x60
	private Image _imgNoticeConfirm; // 0x68
	private RectTransform _itemContainer; // 0x70
	private HotUpdateVoicePackItem _itemPrefab; // 0x78
	private GameObject _linePrefab; // 0x80
	private Action m_onNextStep; // 0x88
	private HotUpdateVoicePackViewModel m_viewModel; // 0x90
	private Boolean m_isInited; // 0x98
	private List`1 m_cachedItems; // 0xa0
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0__GeneItemView; // 0x8
	private static DelegateBridge __Hotfix0__UpdateView; // 0x10
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x18
	private static DelegateBridge __Hotfix0__DoHotUpdateTrace; // 0x20
	private static DelegateBridge __Hotfix0__ConfirmVoicePackChoice; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x27cf35c VA: 0x7594de735c
	protected override Void OnRender(Options options) { }
	// RVA: 0x27cf780 VA: 0x7594de7780
	private Void _GeneItemView() { }
	// RVA: 0x27cfa4c VA: 0x7594de7a4c
	private Void _UpdateView() { }
	// RVA: 0x27cfef8 VA: 0x7594de7ef8
	private Void _OnItemClicked(Int32 index) { }
	// RVA: 0x27d0108 VA: 0x7594de8108
	private Void _DoHotUpdateTrace() { }
	// RVA: 0x27d04cc VA: 0x7594de84cc
	private Boolean _ConfirmVoicePackChoice() { }
	// RVA: 0x27d05fc VA: 0x7594de85fc
	public Void EventOnBackClicked() { }
	// RVA: 0x27d0680 VA: 0x7594de8680
	public Void EventOnConfirmClicked() { }
	// RVA: 0x27d0724 VA: 0x7594de8724
	public Void .ctor() { }
}
```