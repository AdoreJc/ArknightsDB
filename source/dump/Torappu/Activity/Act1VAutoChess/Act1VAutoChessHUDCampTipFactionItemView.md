# Act1VAutoChessHUDCampTipFactionItemView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Image _icon`

- `Text _name`

- `Text _count`

- `GameObject _panelEnable`

- `GameObject _panelDisable`

- `Single _disableIconAlpha`

- `Single _disableTextAlpha`

- `UIPageFinder m_pageFinder`

- `String m_factionId`


## Methods

- `Void Render(String, String, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDCampTipFactionItemView : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private Text _name; // 0x20
	private Text _count; // 0x28
	private GameObject _panelEnable; // 0x30
	private GameObject _panelDisable; // 0x38
	private Single _disableIconAlpha; // 0x40
	private Single _disableTextAlpha; // 0x44
	private UIPageFinder m_pageFinder; // 0x48
	private String m_factionId; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3369cec VA: 0x7595981cec
	public Void Render(String factionId, String name, Int32 count) { }
	// RVA: 0x3369f2c VA: 0x7595981f2c
	public Void .ctor() { }
}
```