# EnemyDuelPrepareBannerView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Image _bannerPicImg`

- `UIAnimationLocation _bannerSwitchOutAnim`

- `UIAnimationLocation _bannerSwitchInAnim`

- `UIPageFinder m_pageFinder`

- `Param m_param`

- `Tween m_modeBannerPicLoopTween`

- `Int32 <curBannerIdx>k__BackingField`


## Properties

- `Int32 curBannerIdx`


## Methods

- `Int32 get_curBannerIdx()`

- `Void set_curBannerIdx(Int32)`

- `Void _SetBannerPic(String)`

- `Void _ChangeBannerLoopIdx(Int32)`

- `Tween _BuildBannerPicLoopTween(Single)`

- `Void Render(Param)`

- `Void <_BuildBannerPicLoopTween>b__13_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelPrepareBannerView : MonoBehaviour, IHotfixable
{
	private Image _bannerPicImg; // 0x18
	private UIAnimationLocation _bannerSwitchOutAnim; // 0x20
	private UIAnimationLocation _bannerSwitchInAnim; // 0x30
	private UIPageFinder m_pageFinder; // 0x40
	private Param m_param; // 0x50
	private Tween m_modeBannerPicLoopTween; // 0x58
	private Int32 <curBannerIdx>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_curBannerIdx; // 0x0
	private static DelegateBridge __Hotfix0_set_curBannerIdx; // 0x8
	private static DelegateBridge __Hotfix0__SetBannerPic; // 0x10
	private static DelegateBridge __Hotfix0__ChangeBannerLoopIdx; // 0x18
	private static DelegateBridge __Hotfix0__BuildBannerPicLoopTween; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 curBannerIdx { get; set; }

	// RVA: 0x29927f4 VA: 0x7594faa7f4
	public Int32 get_curBannerIdx() { }
	// RVA: 0x299285c VA: 0x7594faa85c
	private Void set_curBannerIdx(Int32 value) { }
	// RVA: 0x29928d8 VA: 0x7594faa8d8
	private Void _SetBannerPic(String picId) { }
	// RVA: 0x29929d4 VA: 0x7594faa9d4
	private Void _ChangeBannerLoopIdx(Int32 loopIdx) { }
	// RVA: 0x2992b08 VA: 0x7594faab08
	private Tween _BuildBannerPicLoopTween(Single interval) { }
	// RVA: 0x2992cf4 VA: 0x7594faacf4
	public Void Render(Param param) { }
	// RVA: 0x2992d98 VA: 0x7594faad98
	public Void .ctor() { }
	// RVA: 0x2992e08 VA: 0x7594faae08
	private Void <_BuildBannerPicLoopTween>b__13_0() { }
}
```