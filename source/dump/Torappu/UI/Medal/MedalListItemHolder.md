# MedalListItemHolder

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalListAbleToGetItemView _ableItemView`

- `MedalListAlreadyGetItemView _getItemView`

- `MedalListNotGetItemView _notGetItemView`

- `MedalListTitleView _titleView`

- `Transform _container`

- `UIMedalEvent clickMedalEvent`

- `UIStringEvent clickToGroupEvent`

- `UIStringEvent clickToMedalEvent`

- `MedalCommonViewModel m_cacheviewModel`

- `MedalListAbleToGetItemView m_ableItemView`

- `MedalListAlreadyGetItemView m_getItemView`

- `MedalListNotGetItemView m_notGetItemView`

- `MedalListTitleView m_titleView`


## Properties

- `String originMedalId`


## Methods

- `String get_originMedalId()`

- `Void RenderTitle(MedalGroupViewModel)`

- `Void RenderView(MedalCommonViewModel)`

- `Void OnOpenDetail()`

- `Void _RenderListItems(ViewStatus, MedalCommonViewModel)`

- `Void _RenderItemView(RenderViewOptions`1, ref)`

- `Void _UpdateAbleItemView(ViewStatus, MedalCommonViewModel)`

- `Void _UpdateAlreadyGetView(ViewStatus, MedalCommonViewModel)`

- `Void _UpdateNotGetView(ViewStatus, MedalCommonViewModel)`

- `Void _RenderTitleView(ViewStatus, MedalGroupViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalListItemHolder : MonoBehaviour, IHotfixable
{
	private MedalListAbleToGetItemView _ableItemView; // 0x18
	private MedalListAlreadyGetItemView _getItemView; // 0x20
	private MedalListNotGetItemView _notGetItemView; // 0x28
	private MedalListTitleView _titleView; // 0x30
	private Transform _container; // 0x38
	public UIMedalEvent clickMedalEvent; // 0x40
	public UIStringEvent clickToGroupEvent; // 0x48
	public UIStringEvent clickToMedalEvent; // 0x50
	private MedalCommonViewModel m_cacheviewModel; // 0x58
	private MedalListAbleToGetItemView m_ableItemView; // 0x60
	private MedalListAlreadyGetItemView m_getItemView; // 0x68
	private MedalListNotGetItemView m_notGetItemView; // 0x70
	private MedalListTitleView m_titleView; // 0x78
	private static DelegateBridge __Hotfix0_get_originMedalId; // 0x0
	private static DelegateBridge __Hotfix0_RenderTitle; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0_OnOpenDetail; // 0x18
	private static DelegateBridge __Hotfix0__ConvertToViewStatus; // 0x20
	private static DelegateBridge __Hotfix0__RenderListItems; // 0x28
	private static DelegateBridge __Hotfix0__RenderItemView; // 0x30
	private static DelegateBridge __Hotfix0__UpdateAbleItemView; // 0x38
	private static DelegateBridge __Hotfix0__UpdateAlreadyGetView; // 0x40
	private static DelegateBridge __Hotfix0__UpdateNotGetView; // 0x48
	private static DelegateBridge __Hotfix0__RenderTitleView; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String originMedalId { get; }

	// RVA: 0x279ebd4 VA: 0x7594db6bd4
	public String get_originMedalId() { }
	// RVA: 0x279e860 VA: 0x7594db6860
	public Void RenderTitle(MedalGroupViewModel groupViewModel) { }
	// RVA: 0x279e8f4 VA: 0x7594db68f4
	public Void RenderView(MedalCommonViewModel viewModel) { }
	// RVA: 0x279ec78 VA: 0x7594db6c78
	public Void OnOpenDetail() { }
	// RVA: 0x27a1290 VA: 0x7594db9290
	private static ViewStatus _ConvertToViewStatus(MedalCommonViewModel viewModel) { }
	// RVA: 0x27a1158 VA: 0x7594db9158
	private Void _RenderListItems(ViewStatus status, MedalCommonViewModel viewModel) { }
	// RVA: 0x VA: 0x0
	private Void _RenderItemView(RenderViewOptions`1 options, ref T viewInst) { }
	// RVA: 0x27a1380 VA: 0x7594db9380
	private Void _UpdateAbleItemView(ViewStatus status, MedalCommonViewModel viewModel) { }
	// RVA: 0x27a1550 VA: 0x7594db9550
	private Void _UpdateAlreadyGetView(ViewStatus status, MedalCommonViewModel viewModel) { }
	// RVA: 0x27a1720 VA: 0x7594db9720
	private Void _UpdateNotGetView(ViewStatus status, MedalCommonViewModel viewModel) { }
	// RVA: 0x27a0f1c VA: 0x7594db8f1c
	private Void _RenderTitleView(ViewStatus status, MedalGroupViewModel groupViewModel) { }
	// RVA: 0x27a18f0 VA: 0x7594db98f0
	public Void .ctor() { }
}
```