# Rl03OuterBuffBottomView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Image _icon`

- `GameObject _normalPanel`

- `GameObject _difficultPanel`

- `Rl03OuterBuffBottomDifficultyView _diffView`

- `Rl03OuterBuffBottomNormalView _normalView`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `Rl03OuterBuffNodeBaseViewModel m_cachedNodeViewModel`


## Methods

- `Void Render(Rl03OuterBuffViewModel, Rl03OuterBuffNodeBaseViewModel)`

- `Void _RenderIcon(Rl03OuterBuffNodeBaseViewModel)`

- `Void OnConfirmUpgrade()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffBottomView : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private List`1 _iconGroups; // 0x20
	private GameObject _normalPanel; // 0x28
	private GameObject _difficultPanel; // 0x30
	private Rl03OuterBuffBottomDifficultyView _diffView; // 0x38
	private Rl03OuterBuffBottomNormalView _normalView; // 0x40
	public Action`1 onConfirmUpgrade; // 0x48
	private Boolean m_isInited; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private Rl03OuterBuffNodeBaseViewModel m_cachedNodeViewModel; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderIcon; // 0x8
	private static DelegateBridge __Hotfix0_OnConfirmUpgrade; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x26a7224 VA: 0x7594cbf224
	public Void Render(Rl03OuterBuffViewModel viewModel, Rl03OuterBuffNodeBaseViewModel nodeViewModel) { }
	// RVA: 0x26a744c VA: 0x7594cbf44c
	private Void _RenderIcon(Rl03OuterBuffNodeBaseViewModel viewModel) { }
	// RVA: 0x26a7654 VA: 0x7594cbf654
	public Void OnConfirmUpgrade() { }
	// RVA: 0x26a76f4 VA: 0x7594cbf6f4
	public Void .ctor() { }
}
```