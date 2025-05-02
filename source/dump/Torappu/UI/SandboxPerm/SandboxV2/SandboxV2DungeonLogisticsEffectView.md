# SandboxV2DungeonLogisticsEffectView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _content`

- `Text _title`

- `Text _charCount`

- `Text _drinkCost`

- `Text _drinkObtained`

- `Color _noDrink`

- `Color _enoughDrink`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `UIPageFinder m_pageFinder`

- `SandboxV2DungeonMiscLogisticsEffectViewModel m_cachedViewModel`


## Methods

- `Void Render(SandboxV2DungeonMiscLogisticsEffectViewModel)`

- `Void _InitIfNot()`

- `Void OnAddDrinkClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonLogisticsEffectView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Text _title; // 0x20
	private Text _charCount; // 0x28
	private Text _drinkCost; // 0x30
	private Text _drinkObtained; // 0x38
	private Color _noDrink; // 0x40
	private Color _enoughDrink; // 0x50
	private Boolean m_isInited; // 0x60
	private Adapter m_adapter; // 0x68
	private UIPageFinder m_pageFinder; // 0x70
	private SandboxV2DungeonMiscLogisticsEffectViewModel m_cachedViewModel; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnAddDrinkClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x254ba2c VA: 0x7594b63a2c
	public Void Render(SandboxV2DungeonMiscLogisticsEffectViewModel viewModel) { }
	// RVA: 0x254bce0 VA: 0x7594b63ce0
	private Void _InitIfNot() { }
	// RVA: 0x254be44 VA: 0x7594b63e44
	public Void OnAddDrinkClick() { }
	// RVA: 0x254bef8 VA: 0x7594b63ef8
	public Void .ctor() { }
}
```