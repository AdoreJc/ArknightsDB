# NameCardV2ModuleContainerView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `GameObject _listEmptyItem`

- `UIRecycleLayoutGroup _content`

- `UIStyleProvider _styleProvider`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `UIPageFinder m_pageFinder`

- `Int32 m_cachedEditSeqNum`

- `PanelRightAdpter m_adapter`


## Methods

- `Void Update()`

- `Void _InitIfNot()`

- `Void _RenderAndSortUnselectedModules(ListDict`2)`

- `Void _RenderAndSortUnselectedModulesWithTween(ListDict`2)`

- `Int32 _SortUnselectedVirtualViews(KeyValuePair`2, KeyValuePair`2)`

- `Void _OnModuleHidden(String)`

- `IVirtualView _GetRightPanelModuleVirtualView(NameCardV2RemovableModuleBaseModel)`

- `Void CloseSelectPanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2ModuleContainerView : DataBinder`1
{
	private const String DEFAULT_NAME_CARD_SKIN_ID; // 0x0
	private const Int32 DEFAULT_NAME_CARD_SKIN_TMPL; // 0x0
	private GameObject _listEmptyItem; // 0x20
	private UIRecycleLayoutGroup _content; // 0x28
	private UIStyleProvider _styleProvider; // 0x30
	private Boolean m_hasInited; // 0x38
	private UIStateFinder m_stateFinder; // 0x40
	private UIPageFinder m_pageFinder; // 0x50
	private Int32 m_cachedEditSeqNum; // 0x60
	private ListDict`2 m_unselectedViews; // 0x68
	private PanelRightAdpter m_adapter; // 0x70
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__RenderAndSortUnselectedModules; // 0x18
	private static DelegateBridge __Hotfix0__RenderAndSortUnselectedModulesWithTween; // 0x20
	private static DelegateBridge __Hotfix0__SortUnselectedVirtualViews; // 0x28
	private static DelegateBridge __Hotfix0__OnModuleHidden; // 0x30
	private static DelegateBridge __Hotfix0__GetRightPanelModuleVirtualView; // 0x38
	private static DelegateBridge __Hotfix0_CloseSelectPanel; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x28e5918 VA: 0x7594efd918
	public Void Update() { }
	// RVA: 0x28e5a78 VA: 0x7594efda78
	public override Void OnValueChanged(NameCardV2Property property) { }
	// RVA: 0x28e5b8c VA: 0x7594efdb8c
	private Void _InitIfNot() { }
	// RVA: 0x28e5cf4 VA: 0x7594efdcf4
	private Void _RenderAndSortUnselectedModules(ListDict`2 listDict) { }
	// RVA: 0x28e5e88 VA: 0x7594efde88
	private Void _RenderAndSortUnselectedModulesWithTween(ListDict`2 listDict) { }
	// RVA: 0x28e6d8c VA: 0x7594efed8c
	private Int32 _SortUnselectedVirtualViews(KeyValuePair`2 a, KeyValuePair`2 b) { }
	// RVA: 0x28e6f2c VA: 0x7594efef2c
	private Void _OnModuleHidden(String moduleId) { }
	// RVA: 0x28e652c VA: 0x7594efe52c
	private IVirtualView _GetRightPanelModuleVirtualView(NameCardV2RemovableModuleBaseModel moduleModel) { }
	// RVA: 0x28e71c0 VA: 0x7594eff1c0
	public Void CloseSelectPanel() { }
	// RVA: 0x28e7264 VA: 0x7594eff264
	public Void .ctor() { }
}
```