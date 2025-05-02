# Act36sideFoodHandbookTokenPanel

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `Image _selectedTokenName`

- `Image _selectedTokenBigIcon`

- `Image _selectedTokenDesc`

- `Text _selectedTokenAbility`

- `Text _selectedTokenObtain`

- `TwoStateToggle _unlockToggle`

- `SimpleLayoutContent _gridContent`

- `UIPageFinder m_pageFinder`

- `String m_cachedActId`

- `String m_cachedSelectedItemId`

- `ItemAdater m_adapter`

- `Boolean m_hasInited`


## Methods

- `Void Render(Act36sideFoodHandbookViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideFoodHandbookTokenPanel : MonoBehaviour, IHotfixable
{
	private Image _selectedTokenName; // 0x18
	private Image _selectedTokenBigIcon; // 0x20
	private Image _selectedTokenDesc; // 0x28
	private Text _selectedTokenAbility; // 0x30
	private Text _selectedTokenObtain; // 0x38
	private TwoStateToggle _unlockToggle; // 0x40
	private SimpleLayoutContent _gridContent; // 0x48
	private UIPageFinder m_pageFinder; // 0x50
	private List`1 m_cachedItemModels; // 0x60
	private String m_cachedActId; // 0x68
	private String m_cachedSelectedItemId; // 0x70
	private ItemAdater m_adapter; // 0x78
	private Boolean m_hasInited; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3248384 VA: 0x7595860384
	public Void Render(Act36sideFoodHandbookViewModel model) { }
	// RVA: 0x3248628 VA: 0x7595860628
	private Void _InitIfNot() { }
	// RVA: 0x324878c VA: 0x759586078c
	public Void .ctor() { }
}
```