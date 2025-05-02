# HomeCharRotationPresetListItemView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Text _textIndex`

- `Text _textName`

- `Text _textBackgroundName`

- `Text _textThemeName`

- `Image _imgBackground`

- `Image _imgTheme`

- `SimpleLayoutContent _charSkinList`

- `GameObject _pnlApply`

- `GameObject _pnlDisabled`

- `GameObject _pnlMoreSkin`

- `Text _textSkinNum`

- `GameObject _pnlDeleteBtn`

- `Boolean m_inited`

- `Adapter m_adapter`

- `String m_cachedProfileSkinId`

- `UIPageFinder m_pageFinder`

- `String m_cachedInstId`


## Methods

- `Void set_onBtnNameClick(Action`1)`

- `Void set_onBtnDeleteClick(Action`1)`

- `Void set_onBtnEditClick(Action`1)`

- `Void set_onBtnApplyClick(Action`1)`

- `Void _InitIfNot()`

- `Void Render(HomeCharRotationPresetItemViewModel, Int32, String)`

- `Void OnBtnNameClick()`

- `Void OnBtnDeleteClick()`

- `Void OnBtnEditClick()`

- `Void OnBtnApplyClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCharRotationPresetListItemView : MonoBehaviour, IHotfixable
{
	private const Int32 MAX_SHOW_SKIN_NUM; // 0x0
	private Text _textIndex; // 0x18
	private Text _textName; // 0x20
	private Text _textBackgroundName; // 0x28
	private Text _textThemeName; // 0x30
	private Image _imgBackground; // 0x38
	private Image _imgTheme; // 0x40
	private SimpleLayoutContent _charSkinList; // 0x48
	private GameObject _pnlApply; // 0x50
	private GameObject _pnlDisabled; // 0x58
	private GameObject _pnlMoreSkin; // 0x60
	private Text _textSkinNum; // 0x68
	private GameObject _pnlDeleteBtn; // 0x70
	private Action`1 <onBtnNameClick>k__BackingField; // 0x78
	private Action`1 <onBtnDeleteClick>k__BackingField; // 0x80
	private Action`1 <onBtnEditClick>k__BackingField; // 0x88
	private Action`1 <onBtnApplyClick>k__BackingField; // 0x90
	private Boolean m_inited; // 0x98
	private Adapter m_adapter; // 0xa0
	private List`1 m_cachedSkinList; // 0xa8
	private String m_cachedProfileSkinId; // 0xb0
	private UIPageFinder m_pageFinder; // 0xb8
	private String m_cachedInstId; // 0xc8
	private static DelegateBridge __Hotfix0_get_onBtnNameClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onBtnNameClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onBtnDeleteClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onBtnDeleteClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onBtnEditClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onBtnEditClick; // 0x28
	private static DelegateBridge __Hotfix0_get_onBtnApplyClick; // 0x30
	private static DelegateBridge __Hotfix0_set_onBtnApplyClick; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x48
	private static DelegateBridge __Hotfix0_OnBtnNameClick; // 0x50
	private static DelegateBridge __Hotfix0_OnBtnDeleteClick; // 0x58
	private static DelegateBridge __Hotfix0_OnBtnEditClick; // 0x60
	private static DelegateBridge __Hotfix0_OnBtnApplyClick; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Action`1 onBtnNameClick { get; set; }
	public Action`1 onBtnDeleteClick { get; set; }
	public Action`1 onBtnEditClick { get; set; }
	public Action`1 onBtnApplyClick { get; set; }

	// RVA: 0x27defec VA: 0x7594df6fec
	public Action`1 get_onBtnNameClick() { }
	// RVA: 0x27df054 VA: 0x7594df7054
	public Void set_onBtnNameClick(Action`1 value) { }
	// RVA: 0x27df0d8 VA: 0x7594df70d8
	public Action`1 get_onBtnDeleteClick() { }
	// RVA: 0x27df140 VA: 0x7594df7140
	public Void set_onBtnDeleteClick(Action`1 value) { }
	// RVA: 0x27df1c4 VA: 0x7594df71c4
	public Action`1 get_onBtnEditClick() { }
	// RVA: 0x27df22c VA: 0x7594df722c
	public Void set_onBtnEditClick(Action`1 value) { }
	// RVA: 0x27df2b0 VA: 0x7594df72b0
	public Action`1 get_onBtnApplyClick() { }
	// RVA: 0x27df318 VA: 0x7594df7318
	public Void set_onBtnApplyClick(Action`1 value) { }
	// RVA: 0x27df39c VA: 0x7594df739c
	private Void _InitIfNot() { }
	// RVA: 0x27df500 VA: 0x7594df7500
	public Void Render(HomeCharRotationPresetItemViewModel viewModel, Int32 index, String currPresetInstId) { }
	// RVA: 0x27df7d0 VA: 0x7594df77d0
	public Void OnBtnNameClick() { }
	// RVA: 0x27df880 VA: 0x7594df7880
	public Void OnBtnDeleteClick() { }
	// RVA: 0x27df930 VA: 0x7594df7930
	public Void OnBtnEditClick() { }
	// RVA: 0x27df9e0 VA: 0x7594df79e0
	public Void OnBtnApplyClick() { }
	// RVA: 0x27dfa90 VA: 0x7594df7a90
	public Void .ctor() { }
}
```