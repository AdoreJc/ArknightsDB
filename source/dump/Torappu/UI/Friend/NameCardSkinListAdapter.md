# NameCardSkinListAdapter

**Namespace:** `Torappu.UI.Friend`


## Fields

- `NameCardSkinListItemView m_itemViewPrefab`

- `UIPageFinder m_pageFinder`

- `Boolean m_isSkinTmplList`

- `String m_selectSkinId`

- `Int32 m_selectSkinTmpl`

- `Boolean m_subSkinFastMode`


## Methods

- `Void SetParam(Boolean, String, Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardSkinListAdapter : LoopScrollAdapter`2, IHotfixable
{
	private NameCardSkinListItemView m_itemViewPrefab; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private Boolean m_isSkinTmplList; // 0x70
	private String m_selectSkinId; // 0x78
	private Int32 m_selectSkinTmpl; // 0x80
	private Boolean m_subSkinFastMode; // 0x84
	private static DelegateBridge __Hotfix0_SetParam; // 0x0
	private static DelegateBridge __Hotfix0_CreateView; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x28dd17c VA: 0x7594ef517c
	public Void SetParam(Boolean isSkinTmplList, String selectSkinId, Int32 selectSkinTmpl, Boolean subSkinFastMode) { }
	// RVA: 0x28dd33c VA: 0x7594ef533c
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x28dd4c0 VA: 0x7594ef54c0
	public override Void UpdateView(Int32 position, GameObject view, NameCardSkinListItemViewHolder holder, NameCardSkinListItemViewModel data) { }
	// RVA: 0x28dd8c0 VA: 0x7594ef58c0
	public Void .ctor() { }
}
```