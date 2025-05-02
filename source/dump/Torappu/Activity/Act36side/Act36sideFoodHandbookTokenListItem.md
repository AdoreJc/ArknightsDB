# Act36sideFoodHandbookTokenListItem

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `Image _tokenImage`

- `GameObject _selectedPanel`

- `GameObject _newPanel`

- `TwoStateToggle _unlockToggle`

- `Button _hotspot`

- `UIPageFinder m_pageFinder`

- `String m_cachedId`

- `Boolean m_cachedIsSelected`


## Methods

- `Void Render(Act36sideFoodHandbookTokenItemModel, String, String)`

- `Void OnTokenSelected()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideFoodHandbookTokenListItem : MonoBehaviour, IHotfixable
{
	private Image _tokenImage; // 0x18
	private GameObject _selectedPanel; // 0x20
	private GameObject _newPanel; // 0x28
	private TwoStateToggle _unlockToggle; // 0x30
	private Button _hotspot; // 0x38
	private UIPageFinder m_pageFinder; // 0x40
	private String m_cachedId; // 0x50
	private Boolean m_cachedIsSelected; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnTokenSelected; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32480ac VA: 0x75958600ac
	public Void Render(Act36sideFoodHandbookTokenItemModel model, String selectedId, String actId) { }
	// RVA: 0x324821c VA: 0x759586021c
	public Void OnTokenSelected() { }
	// RVA: 0x3248314 VA: 0x7595860314
	public Void .ctor() { }
}
```