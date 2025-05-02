# Dropdown

**Namespace:** `UnityEngine.UI`


## Fields

- `RectTransform m_Template`

- `Text m_CaptionText`

- `Image m_CaptionImage`

- `Text m_ItemText`

- `Image m_ItemImage`

- `Int32 m_Value`

- `OptionDataList m_Options`

- `DropdownEvent m_OnValueChanged`

- `Single m_AlphaFadeSpeed`

- `GameObject m_Dropdown`

- `GameObject m_Blocker`

- `Boolean validTemplate`


## Properties

- `RectTransform template`

- `Text captionText`

- `Image captionImage`

- `Text itemText`

- `Image itemImage`

- `DropdownEvent onValueChanged`

- `Single alphaFadeSpeed`

- `Int32 value`


## Methods

- `RectTransform get_template()`

- `Void set_template(RectTransform)`

- `Text get_captionText()`

- `Void set_captionText(Text)`

- `Image get_captionImage()`

- `Void set_captionImage(Image)`

- `Text get_itemText()`

- `Void set_itemText(Text)`

- `Image get_itemImage()`

- `Void set_itemImage(Image)`

- `Void set_options(List`1)`

- `DropdownEvent get_onValueChanged()`

- `Void set_onValueChanged(DropdownEvent)`

- `Single get_alphaFadeSpeed()`

- `Void set_alphaFadeSpeed(Single)`

- `Int32 get_value()`

- `Void set_value(Int32)`

- `Void SetValueWithoutNotify(Int32)`

- `Void Set(Int32, Boolean)`

- `Void RefreshShownValue()`

- `Void AddOptions(List`1)`

- `Void AddOptions(List`1)`

- `Void AddOptions(List`1)`

- `Void ClearOptions()`

- `Void SetupTemplate(Canvas)`

- `Void Show()`

- `DropdownItem AddItem(OptionData, Boolean, DropdownItem, List`1)`

- `Void AlphaFadeList(Single, Single)`

- `Void AlphaFadeList(Single, Single, Single)`

- `Void SetAlpha(Single)`

- `Void Hide()`

- `IEnumerator DelayedDestroyDropdownList(Single)`

- `Void ImmediateDestroyDropdownList()`

- `Void OnSelectItem(Toggle)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class Dropdown : Selectable, IPointerClickHandler, IEventSystemHandler, ISubmitHandler, ICancelHandler
{
	private RectTransform m_Template; // 0xf8
	private Text m_CaptionText; // 0x100
	private Image m_CaptionImage; // 0x108
	private Text m_ItemText; // 0x110
	private Image m_ItemImage; // 0x118
	private Int32 m_Value; // 0x120
	private OptionDataList m_Options; // 0x128
	private DropdownEvent m_OnValueChanged; // 0x130
	private Single m_AlphaFadeSpeed; // 0x138
	private GameObject m_Dropdown; // 0x140
	private GameObject m_Blocker; // 0x148
	private List`1 m_Items; // 0x150
	private TweenRunner`1 m_AlphaTweenRunner; // 0x158
	private Boolean validTemplate; // 0x160
	private const Int32 kHighSortingLayer; // 0x0
	private static OptionData s_NoOptionData; // 0x0

	public RectTransform template { get; set; }
	public Text captionText { get; set; }
	public Image captionImage { get; set; }
	public Text itemText { get; set; }
	public Image itemImage { get; set; }
	public List`1 options { get; set; }
	public DropdownEvent onValueChanged { get; set; }
	public Single alphaFadeSpeed { get; set; }
	public Int32 value { get; set; }

	// RVA: 0x691a3c4 VA: 0x7598f323c4
	public RectTransform get_template() { }
	// RVA: 0x6919660 VA: 0x7598f31660
	public Void set_template(RectTransform value) { }
	// RVA: 0x691a3cc VA: 0x7598f323cc
	public Text get_captionText() { }
	// RVA: 0x691967c VA: 0x7598f3167c
	public Void set_captionText(Text value) { }
	// RVA: 0x691a3d4 VA: 0x7598f323d4
	public Image get_captionImage() { }
	// RVA: 0x691a3dc VA: 0x7598f323dc
	public Void set_captionImage(Image value) { }
	// RVA: 0x691a3fc VA: 0x7598f323fc
	public Text get_itemText() { }
	// RVA: 0x691969c VA: 0x7598f3169c
	public Void set_itemText(Text value) { }
	// RVA: 0x691a404 VA: 0x7598f32404
	public Image get_itemImage() { }
	// RVA: 0x691a40c VA: 0x7598f3240c
	public Void set_itemImage(Image value) { }
	// RVA: 0x69196bc VA: 0x7598f316bc
	public List`1 get_options() { }
	// RVA: 0x691a42c VA: 0x7598f3242c
	public Void set_options(List`1 value) { }
	// RVA: 0x691a454 VA: 0x7598f32454
	public DropdownEvent get_onValueChanged() { }
	// RVA: 0x691a45c VA: 0x7598f3245c
	public Void set_onValueChanged(DropdownEvent value) { }
	// RVA: 0x691a46c VA: 0x7598f3246c
	public Single get_alphaFadeSpeed() { }
	// RVA: 0x691a474 VA: 0x7598f32474
	public Void set_alphaFadeSpeed(Single value) { }
	// RVA: 0x691a47c VA: 0x7598f3247c
	public Int32 get_value() { }
	// RVA: 0x691a484 VA: 0x7598f32484
	public Void set_value(Int32 value) { }
	// RVA: 0x691a59c VA: 0x7598f3259c
	public Void SetValueWithoutNotify(Int32 input) { }
	// RVA: 0x691a48c VA: 0x7598f3248c
	private Void Set(Int32 value, Boolean sendCallback) { }
	// RVA: 0x691a5a4 VA: 0x7598f325a4
	protected Void .ctor() { }
	// RVA: 0x691a79c VA: 0x7598f3279c
	protected override Void Awake() { }
	// RVA: 0x691a898 VA: 0x7598f32898
	protected override Void Start() { }
	// RVA: 0x691a948 VA: 0x7598f32948
	protected override Void OnDisable() { }
	// RVA: 0x69196e0 VA: 0x7598f316e0
	public Void RefreshShownValue() { }
	// RVA: 0x691ab68 VA: 0x7598f32b68
	public Void AddOptions(List`1 options) { }
	// RVA: 0x691abd0 VA: 0x7598f32bd0
	public Void AddOptions(List`1 options) { }
	// RVA: 0x691ad70 VA: 0x7598f32d70
	public Void AddOptions(List`1 options) { }
	// RVA: 0x691af10 VA: 0x7598f32f10
	public Void ClearOptions() { }
	// RVA: 0x691af88 VA: 0x7598f32f88
	private Void SetupTemplate(Canvas rootCanvas) { }
	// RVA: 0x VA: 0x0
	private static T GetOrAddComponent(GameObject go) { }
	// RVA: 0x691b634 VA: 0x7598f33634
	public virtual Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x691c308 VA: 0x7598f34308
	public virtual Void OnSubmit(BaseEventData eventData) { }
	// RVA: 0x691c30c VA: 0x7598f3430c
	public virtual Void OnCancel(BaseEventData eventData) { }
	// RVA: 0x691b638 VA: 0x7598f33638
	public Void Show() { }
	// RVA: 0x691c840 VA: 0x7598f34840
	protected virtual GameObject CreateBlocker(Canvas rootCanvas) { }
	// RVA: 0x691cd3c VA: 0x7598f34d3c
	protected virtual Void DestroyBlocker(GameObject blocker) { }
	// RVA: 0x691cd94 VA: 0x7598f34d94
	protected virtual GameObject CreateDropdownList(GameObject template) { }
	// RVA: 0x691ce00 VA: 0x7598f34e00
	protected virtual Void DestroyDropdownList(GameObject dropdownList) { }
	// RVA: 0x691ce58 VA: 0x7598f34e58
	protected virtual DropdownItem CreateItem(DropdownItem itemTemplate) { }
	// RVA: 0x691cec4 VA: 0x7598f34ec4
	protected virtual Void DestroyItem(DropdownItem item) { }
	// RVA: 0x691c424 VA: 0x7598f34424
	private DropdownItem AddItem(OptionData data, Boolean selected, DropdownItem itemTemplate, List`1 items) { }
	// RVA: 0x691cec8 VA: 0x7598f34ec8
	private Void AlphaFadeList(Single duration, Single alpha) { }
	// RVA: 0x691c718 VA: 0x7598f34718
	private Void AlphaFadeList(Single duration, Single start, Single end) { }
	// RVA: 0x691cf48 VA: 0x7598f34f48
	private Void SetAlpha(Single alpha) { }
	// RVA: 0x691c310 VA: 0x7598f34310
	public Void Hide() { }
	// RVA: 0x691cffc VA: 0x7598f34ffc
	private IEnumerator DelayedDestroyDropdownList(Single delay) { }
	// RVA: 0x691a9ec VA: 0x7598f329ec
	private Void ImmediateDestroyDropdownList() { }
	// RVA: 0x691d0a8 VA: 0x7598f350a8
	private Void OnSelectItem(Toggle toggle) { }
	// RVA: 0x691d1dc VA: 0x7598f351dc
	private static Void .cctor() { }
}
```