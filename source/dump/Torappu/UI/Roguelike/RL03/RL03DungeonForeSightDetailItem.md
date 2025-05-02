# RL03DungeonForeSightDetailItem

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `Transform _nodeContainer`

- `RL03TotemItemView _totemItemView`

- `Image _relicPic`

- `Single _scaler`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInited`

- `RL03TotemItemView m_totemItemView`

- `RL03TotemViewModel m_totemViewModel`


## Methods

- `Void _InitIfNot()`

- `Void RenderRelic(String, String)`

- `Void RenderClear()`

- `Void RenderTotem(String, RL03TotemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03DungeonForeSightDetailItem : MonoBehaviour, IHotfixable
{
	private Transform _nodeContainer; // 0x18
	private RL03TotemItemView _totemItemView; // 0x20
	private Image _relicPic; // 0x28
	private Single _scaler; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private Boolean m_isInited; // 0x48
	private RL03TotemItemView m_totemItemView; // 0x50
	private RL03TotemViewModel m_totemViewModel; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderRelic; // 0x8
	private static DelegateBridge __Hotfix0_RenderClear; // 0x10
	private static DelegateBridge __Hotfix0_RenderTotem; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b8ae54 VA: 0x75951a2e54
	private Void _InitIfNot() { }
	// RVA: 0x2b8af3c VA: 0x75951a2f3c
	public Void RenderRelic(String topicId, String relicId) { }
	// RVA: 0x2b8b040 VA: 0x75951a3040
	public Void RenderClear() { }
	// RVA: 0x2b8b0dc VA: 0x75951a30dc
	public Void RenderTotem(String topicId, RL03TotemViewModel viewModel) { }
	// RVA: 0x2b8b1dc VA: 0x75951a31dc
	public Void .ctor() { }
}
```