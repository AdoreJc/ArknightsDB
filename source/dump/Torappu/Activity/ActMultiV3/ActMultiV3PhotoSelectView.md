# ActMultiV3PhotoSelectView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `UIStyleProvider _styleProvider`

- `Text _photoLimitText`

- `ActMultiV3PhotoAvatarListAdapter _adapter`

- `ActMultiV3PhotoSelectNameCardView _nameCardView`

- `ActMultiV3PhotoView _contentView`

- `CanvasGroup _contentCanvasGroup`

- `Single _contentFadeDuration`

- `TwoStateToggle _detailToggle`

- `Text _photoDescText`

- `Text _photoTimeText`

- `CanvasGroup _detailCanvasGroup`

- `RectTransform _detailTransform`

- `Vector2 _detailHidePos`

- `Vector2 _detailShowPos`

- `Text _numberText`

- `Text _photoTypeNameText`

- `GameObject _submitPhotoPart`

- `GameObject _committedPhotoPart`

- `Boolean m_inited`

- `UIStateFinder m_stateFinder`

- `String m_cachedInstId`

- `String m_cachedTemplateId`

- `Int32 m_cachedInitSeqNum`

- `Sequence m_switchPhotoTween`

- `FadeTranslationSwitchTween m_detailTween`


## Methods

- `Void OnClickShowHideDetail()`

- `Void OnSubmitPhoto()`

- `Void OnClickComittedPhoto()`

- `Void _SwitchPhoto(ActMultiV3ManualPhotoSelectViewModel, Boolean)`

- `Void _RenderPhoto(ActMultiV3ManualPhotoSelectViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3PhotoSelectView : DataBinder`1, IHotfixable
{
	private UIStyleProvider _styleProvider; // 0x20
	private Text _photoLimitText; // 0x28
	private ActMultiV3PhotoAvatarListAdapter _adapter; // 0x30
	private ActMultiV3PhotoSelectNameCardView _nameCardView; // 0x38
	private ActMultiV3PhotoView _contentView; // 0x40
	private CanvasGroup _contentCanvasGroup; // 0x48
	private Single _contentFadeDuration; // 0x50
	private TwoStateToggle _detailToggle; // 0x58
	private Text _photoDescText; // 0x60
	private Text _photoTimeText; // 0x68
	private CanvasGroup _detailCanvasGroup; // 0x70
	private RectTransform _detailTransform; // 0x78
	private Vector2 _detailHidePos; // 0x80
	private Vector2 _detailShowPos; // 0x88
	private Text _numberText; // 0x90
	private Text _photoTypeNameText; // 0x98
	private GameObject _submitPhotoPart; // 0xa0
	private GameObject _committedPhotoPart; // 0xa8
	private Boolean m_inited; // 0xb0
	private UIStateFinder m_stateFinder; // 0xb8
	private String m_cachedInstId; // 0xc8
	private String m_cachedTemplateId; // 0xd0
	private Int32 m_cachedInitSeqNum; // 0xd8
	private Sequence m_switchPhotoTween; // 0xe0
	private FadeTranslationSwitchTween m_detailTween; // 0xe8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnClickShowHideDetail; // 0x8
	private static DelegateBridge __Hotfix0_OnSubmitPhoto; // 0x10
	private static DelegateBridge __Hotfix0_OnClickComittedPhoto; // 0x18
	private static DelegateBridge __Hotfix0__SwitchPhoto; // 0x20
	private static DelegateBridge __Hotfix0__RenderPhoto; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x311c6bc VA: 0x75957346bc
	public override Void OnValueChanged(ActMultiV3ManualPhotoSelectProperty property) { }
	// RVA: 0x311ce84 VA: 0x7595734e84
	public Void OnClickShowHideDetail() { }
	// RVA: 0x311cf28 VA: 0x7595734f28
	public Void OnSubmitPhoto() { }
	// RVA: 0x311cfcc VA: 0x7595734fcc
	public Void OnClickComittedPhoto() { }
	// RVA: 0x311cbf0 VA: 0x7595734bf0
	private Void _SwitchPhoto(ActMultiV3ManualPhotoSelectViewModel model, Boolean fastMode) { }
	// RVA: 0x311d078 VA: 0x7595735078
	private Void _RenderPhoto(ActMultiV3ManualPhotoSelectViewModel model) { }
	// RVA: 0x311ca34 VA: 0x7595734a34
	private Void _InitIfNot() { }
	// RVA: 0x311d3d0 VA: 0x75957353d0
	public Void .ctor() { }
}
```