# EnemyDuelEmoticonBarrageItem

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `GameObject _pnlSelfEmoticon`

- `Image _imgEmoticon`

- `Single _barrageDuration`

- `Ease _easeType`

- `Coord m_coordTop`

- `Coord m_coordBottom`

- `String m_cachedEmoticonThemeId`

- `String m_cachedEmoticonPicId`

- `UIPageFinder m_pageFinder`

- `Tween m_moveTween`

- `Single m_samplePos`


## Methods

- `Void Render(EmoticonBarrageItemParam, Single, Action`1)`

- `Void _Render(EmoticonBarrageItemParam)`

- `Void _RefreshSamplePos()`

- `Single <_Render>b__16_0()`

- `Void <_Render>b__16_1(Single)`

- `Void <_Render>b__16_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEmoticonBarrageItem : MonoBehaviour, IHotfixable
{
	private GameObject _pnlSelfEmoticon; // 0x18
	private Image _imgEmoticon; // 0x20
	private Coord[] _coords; // 0x28
	private Single _barrageDuration; // 0x30
	private Ease _easeType; // 0x34
	private Coord m_coordTop; // 0x38
	private Coord m_coordBottom; // 0x4c
	private String m_cachedEmoticonThemeId; // 0x60
	private String m_cachedEmoticonPicId; // 0x68
	private UIPageFinder m_pageFinder; // 0x70
	private Tween m_moveTween; // 0x80
	private Single m_samplePos; // 0x88
	private Action`1 m_actionOnExit; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0__RefreshSamplePos; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29836a8 VA: 0x7594f9b6a8
	public Void Render(EmoticonBarrageItemParam param, Single laneSamplePos, Action`1 onExit) { }
	// RVA: 0x298397c VA: 0x7594f9b97c
	private Void _Render(EmoticonBarrageItemParam param) { }
	// RVA: 0x2983cdc VA: 0x7594f9bcdc
	private Void _RefreshSamplePos() { }
	// RVA: 0x2983e14 VA: 0x7594f9be14
	public Void .ctor() { }
	// RVA: 0x2983ecc VA: 0x7594f9becc
	private Single <_Render>b__16_0() { }
	// RVA: 0x2983ed4 VA: 0x7594f9bed4
	private Void <_Render>b__16_1(Single val) { }
	// RVA: 0x2983edc VA: 0x7594f9bedc
	private Void <_Render>b__16_2() { }
}
```