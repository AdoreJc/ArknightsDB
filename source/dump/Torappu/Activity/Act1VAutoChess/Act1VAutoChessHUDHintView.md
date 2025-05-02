# Act1VAutoChessHUDHintView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _textHint`

- `Image _imageForce`

- `UIAnimationLocation _anim`

- `Single _safeDelay`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `Int32 m_currIndex`

- `Tween m_cachedTween`

- `String m_cachedIconId`


## Methods

- `Void _InitIfNot()`

- `Void Render(List`1, Boolean, Boolean)`

- `Void _PlayTextIfNeeded()`

- `Void <_PlayTextIfNeeded>b__12_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDHintView : MonoBehaviour, IHotfixable
{
	private Text _textHint; // 0x18
	private Image _imageForce; // 0x20
	private UIAnimationLocation _anim; // 0x28
	private Single _safeDelay; // 0x38
	private Boolean m_isInited; // 0x3c
	private UIPageFinder m_pageFinder; // 0x40
	private Int32 m_currIndex; // 0x50
	private List`1 m_cachedHints; // 0x58
	private Tween m_cachedTween; // 0x60
	private String m_cachedIconId; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__PlayTextIfNeeded; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x33785d0 VA: 0x75959905d0
	private Void _InitIfNot() { }
	// RVA: 0x33709b8 VA: 0x75959889b8
	public Void Render(List`1 hints, Boolean isHintSeq, Boolean isStateChange) { }
	// RVA: 0x3378674 VA: 0x7595990674
	private Void _PlayTextIfNeeded() { }
	// RVA: 0x3378a1c VA: 0x7595990a1c
	public Void .ctor() { }
	// RVA: 0x3378a94 VA: 0x7595990a94
	private Void <_PlayTextIfNeeded>b__12_0() { }
}
```