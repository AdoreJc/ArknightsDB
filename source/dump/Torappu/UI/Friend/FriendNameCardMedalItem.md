# FriendNameCardMedalItem

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Transform _container`

- `Transform _diyContainer`

- `Text _name`

- `GameObject _selectPart`

- `TwoStateToggle _toggleState`

- `Boolean _ableToChoose`

- `GameObject _emptyIcon`

- `UIColorGraphic _btnGraphic`

- `CrossAppShareStartDynAssetContent _crossAppShareNormalMedalContent`

- `CrossAppShareStartDynAssetContent _crossAppShareDiyMedalContent`

- `UINameCardEvent onClickEvent`

- `NameCardMedalType m_type`

- `MedalGroupViewModel m_groupViewModel`

- `UIMedalGroupView m_medalGroup`

- `UIMedalGroupView m_diyMedalGroup`

- `UIPageFinder m_pageFinder`

- `PlayerMedalCustomLayout m_viewModelTempCache`


## Methods

- `Void _InitIfNot()`

- `Void RenderSelfDIY(Options)`

- `Boolean _CheckMedalAvail(String)`

- `Void RenderOtherDIY(PlayerMedalCustomLayout, Options)`

- `Void RenderNo(Options)`

- `Void RenderInfo(MedalGroupViewModel, Options)`

- `Void _SetBoolFlag(Boolean, Boolean)`

- `Void _UpdateBtnGraphic(UIMedalGroupView)`

- `Void OnClick()`

- `Void _SetCrossAppShareMedalOption(MedalStatus, GroupOptions, DIYOptions)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendNameCardMedalItem : MonoBehaviour, IHotfixable
{
	private const String GRAPHIC_GROUP_ID; // 0x0
	private Transform _container; // 0x18
	private Transform _diyContainer; // 0x20
	private Text _name; // 0x28
	private GameObject _selectPart; // 0x30
	private TwoStateToggle _toggleState; // 0x38
	private Boolean _ableToChoose; // 0x40
	private GameObject _emptyIcon; // 0x48
	private UIColorGraphic _btnGraphic; // 0x50
	private CrossAppShareStartDynAssetContent _crossAppShareNormalMedalContent; // 0x58
	private CrossAppShareStartDynAssetContent _crossAppShareDiyMedalContent; // 0x60
	public UINameCardEvent onClickEvent; // 0x68
	private NameCardMedalType m_type; // 0x70
	private MedalGroupViewModel m_groupViewModel; // 0x78
	private UIMedalGroupView m_medalGroup; // 0x80
	private UIMedalGroupView m_diyMedalGroup; // 0x88
	private UIPageFinder m_pageFinder; // 0x90
	private PlayerMedalCustomLayout m_viewModelTempCache; // 0xa0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderSelfDIY; // 0x8
	private static DelegateBridge __Hotfix0__CheckMedalAvail; // 0x10
	private static DelegateBridge __Hotfix0_RenderOtherDIY; // 0x18
	private static DelegateBridge __Hotfix0_RenderNo; // 0x20
	private static DelegateBridge __Hotfix0_RenderInfo; // 0x28
	private static DelegateBridge __Hotfix0__SetBoolFlag; // 0x30
	private static DelegateBridge __Hotfix0__UpdateBtnGraphic; // 0x38
	private static DelegateBridge __Hotfix0_OnClick; // 0x40
	private static DelegateBridge __Hotfix0__SetCrossAppShareMedalOption; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x28db3a8 VA: 0x7594ef33a8
	private Void _InitIfNot() { }
	// RVA: 0x28db568 VA: 0x7594ef3568
	public Void RenderSelfDIY(Options options) { }
	// RVA: 0x28dbcf0 VA: 0x7594ef3cf0
	private Boolean _CheckMedalAvail(String medalId) { }
	// RVA: 0x28dbde8 VA: 0x7594ef3de8
	public Void RenderOtherDIY(PlayerMedalCustomLayout viewModel, Options options) { }
	// RVA: 0x28dc13c VA: 0x7594ef413c
	public Void RenderNo(Options options) { }
	// RVA: 0x28dc34c VA: 0x7594ef434c
	public Void RenderInfo(MedalGroupViewModel viewModel, Options options) { }
	// RVA: 0x28dbb0c VA: 0x7594ef3b0c
	private Void _SetBoolFlag(Boolean isSelect, Boolean currentSelect) { }
	// RVA: 0x28dbbc8 VA: 0x7594ef3bc8
	private Void _UpdateBtnGraphic(UIMedalGroupView groupView) { }
	// RVA: 0x28dc5f4 VA: 0x7594ef45f4
	public Void OnClick() { }
	// RVA: 0x28db83c VA: 0x7594ef383c
	private Void _SetCrossAppShareMedalOption(MedalStatus medalStatus, GroupOptions groupOptions, DIYOptions diyOptions) { }
	// RVA: 0x28dc6d8 VA: 0x7594ef46d8
	public Void .ctor() { }
}
```