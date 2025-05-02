# SandboxV2NodeDropItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAtlasImage _imgBkg`

- `Image _imageItem`

- `GameObject _pnlEmpty`

- `UIColorGraphic _colorGraphic`

- `Single _alphaEmpty`

- `Single _alphaNormal`

- `String m_cachedItemId`

- `UIPageFinder m_pageFinder`


## Properties

- `UIColorGraphic colorGraphic`


## Methods

- `UIColorGraphic get_colorGraphic()`

- `Void Render(String, String, SandboxV2DropDetail, SandboxV2DungeonViewConfig)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodeDropItemView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imgBkg; // 0x18
	private Image _imageItem; // 0x20
	private GameObject _pnlEmpty; // 0x28
	private UIColorGraphic _colorGraphic; // 0x30
	private Single _alphaEmpty; // 0x38
	private Single _alphaNormal; // 0x3c
	private String m_cachedItemId; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private static DelegateBridge __Hotfix0_get_colorGraphic; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public UIColorGraphic colorGraphic { get; }

	// RVA: 0x25675d4 VA: 0x7594b7f5d4
	public UIColorGraphic get_colorGraphic() { }
	// RVA: 0x256763c VA: 0x7594b7f63c
	public Void Render(String topicId, String itemId, SandboxV2DropDetail dropDetail, SandboxV2DungeonViewConfig dungeonViewConfig) { }
	// RVA: 0x2567848 VA: 0x7594b7f848
	public Void .ctor() { }
}
```