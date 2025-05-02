# ActMultiV3CharCardView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Text _textName`

- `Image _imgRarity`

- `GameObject _iconPriGO`

- `GameObject _iconPriHighGO`

- `GameObject _iconPriLowGO`

- `GameObject _skillEquipPanelGO`

- `GameObject _emptySkillPanelGO`

- `GameObject _normalSkillPanelGO`

- `Image _imgSkillIcon`

- `Image _imgSkillSpecLv`

- `Text _textSkillLv`

- `GameObject _emptyEquipPanelGO`

- `GameObject _normalEquipPanelGO`

- `Image _imgEquipIcon`

- `GameObject _equipLvGO`

- `Text _textEquipLv`

- `String m_cacheSkillId`

- `String m_cacheEquipId`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _RenderSkillAndEquipIfNeed(Param)`

- `Void _RenderSkillInfo(SkillInfo)`

- `Void _RenderEquipInfo(EquipInfo)`

- `Void <>xLuaBaseProxy_OnRenderView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3CharCardView : ActMultiV3CharCardBase
{
	private Text _textName; // 0x80
	private Image _imgRarity; // 0x88
	private GameObject _iconPriGO; // 0x90
	private GameObject _iconPriHighGO; // 0x98
	private GameObject _iconPriLowGO; // 0xa0
	private GameObject _skillEquipPanelGO; // 0xa8
	private GameObject _emptySkillPanelGO; // 0xb0
	private GameObject _normalSkillPanelGO; // 0xb8
	private Image _imgSkillIcon; // 0xc0
	private Image _imgSkillSpecLv; // 0xc8
	private Text _textSkillLv; // 0xd0
	private GameObject _emptyEquipPanelGO; // 0xd8
	private GameObject _normalEquipPanelGO; // 0xe0
	private Image _imgEquipIcon; // 0xe8
	private GameObject _equipLvGO; // 0xf0
	private Text _textEquipLv; // 0xf8
	private String m_cacheSkillId; // 0x100
	private String m_cacheEquipId; // 0x108
	private UIPageFinder m_pageFinder; // 0x110
	private static DelegateBridge __Hotfix0_OnRenderView; // 0x0
	private static DelegateBridge __Hotfix0__RenderSkillAndEquipIfNeed; // 0x8
	private static DelegateBridge __Hotfix0__RenderSkillInfo; // 0x10
	private static DelegateBridge __Hotfix0__RenderEquipInfo; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30e2ee4 VA: 0x75956faee4
	protected override Void OnRenderView() { }
	// RVA: 0x30e302c VA: 0x75956fb02c
	private Void _RenderSkillAndEquipIfNeed(Param param) { }
	// RVA: 0x30e30e8 VA: 0x75956fb0e8
	private Void _RenderSkillInfo(SkillInfo skillInfo) { }
	// RVA: 0x30e3298 VA: 0x75956fb298
	private Void _RenderEquipInfo(EquipInfo equipInfo) { }
	// RVA: 0x30e34ac VA: 0x75956fb4ac
	public Void .ctor() { }
	// RVA: 0x30e3518 VA: 0x75956fb518
	private Void <>xLuaBaseProxy_OnRenderView() { }
}
```