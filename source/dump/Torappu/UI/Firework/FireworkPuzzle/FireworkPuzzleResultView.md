# FireworkPuzzleResultView

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `UIAnimationLocation _animEnter`

- `RectTransform _plateContainer`

- `UISpineWrapper _spineWrapper`

- `Text _textDesc`

- `Boolean m_hasInited`

- `Int32 m_cachedEnterSeqNum`

- `Tween m_enterTween`

- `FireworkPuzzleResultModel m_resultModel`

- `FireworkPlateViewStyle m_plateStyle`

- `FireworkPlateView m_plateView`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _RenderNpc(FireworkPuzzleResultModel)`

- `Void _InitIfNot()`

- `Boolean IsTweening()`

- `Void _PlayEnterAnimIfNeed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleResultView : DataBinder`1
{
	private UIAnimationLocation _animEnter; // 0x20
	private RectTransform _plateContainer; // 0x30
	private UISpineWrapper _spineWrapper; // 0x38
	private Text _textDesc; // 0x40
	private Boolean m_hasInited; // 0x48
	private Int32 m_cachedEnterSeqNum; // 0x4c
	private Tween m_enterTween; // 0x50
	private FireworkPuzzleResultModel m_resultModel; // 0x58
	private FireworkPlateViewStyle m_plateStyle; // 0x60
	private FireworkPlateView m_plateView; // 0x68
	private UIPageFinder m_pageFinder; // 0x70
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderNpc; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_IsTweening; // 0x18
	private static DelegateBridge __Hotfix0__PlayEnterAnimIfNeed; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2900068 VA: 0x7594f18068
	public override Void OnValueChanged(FireworkPuzzleResultProp property) { }
	// RVA: 0x2900398 VA: 0x7594f18398
	private Void _RenderNpc(FireworkPuzzleResultModel resultModel) { }
	// RVA: 0x29001bc VA: 0x7594f181bc
	private Void _InitIfNot() { }
	// RVA: 0x28ffcb8 VA: 0x7594f17cb8
	public Boolean IsTweening() { }
	// RVA: 0x29004c0 VA: 0x7594f184c0
	private Void _PlayEnterAnimIfNeed() { }
	// RVA: 0x2900650 VA: 0x7594f18650
	public Void .ctor() { }
}
```