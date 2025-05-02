# CharacterInfoIllustSpreadPanel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `UIWrappedScrollRect _scrollContainer`

- `UITouchZoom _panelTouchZoom`

- `CharacterInfoIllustWrapper _illustWrapper`

- `Vector2 _wrapperStandardPos`

- `Vector2 m_initWrapperSize`

- `RectTransform m_wrapperRectTrans`

- `UIPageFinder m_pageFinder`

- `Vector2 m_finalScrollPos`


## Properties

- `RectTransform wrapperRectTrans`


## Methods

- `RectTransform get_wrapperRectTrans()`

- `Void _RecordWrapperStandardStatus()`

- `Void NotifySpreadIllust()`

- `Void NotifyUnspreadIllust(Boolean)`

- `Void Start()`

- `Void _OnScaleChanged(Single)`

- `Void _OnScaleStart(Single)`

- `Void _OnScaleEnd(Single)`

- `Void _CalcInitWrapperSize()`

- `Void _ResetIllustPosTween()`

- `Void _ResetIllustPos()`

- `Single <_ResetIllustPosTween>b__24_0()`

- `Void <_ResetIllustPosTween>b__24_1(Single)`

- `Void <_ResetIllustPosTween>b__24_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoIllustSpreadPanel : DataBinder`1
{
	private static readonly Vector2 DEFAULT_NORMALIZE_POS; // 0x0
	private static readonly Vector2 STANDARD_ILLUST_SIZE; // 0x8
	private static readonly Vector2 ILLUST_PADDING; // 0x10
	private const Single DEFAULT_SCALE; // 0x0
	private const Single TWEEN_DURATION; // 0x0
	private UIWrappedScrollRect _scrollContainer; // 0x20
	private UITouchZoom _panelTouchZoom; // 0x28
	private CharacterInfoIllustWrapper _illustWrapper; // 0x30
	private Vector2 _wrapperStandardPos; // 0x38
	private Vector2 m_initWrapperSize; // 0x40
	private RectTransform m_wrapperRectTrans; // 0x48
	private UIPageFinder m_pageFinder; // 0x50
	private Vector2 m_finalScrollPos; // 0x60
	private static DelegateBridge __Hotfix0_get_wrapperRectTrans; // 0x18
	private static DelegateBridge __Hotfix0__RecordWrapperStandardStatus; // 0x20
	private static DelegateBridge __Hotfix0_NotifySpreadIllust; // 0x28
	private static DelegateBridge __Hotfix0_NotifyUnspreadIllust; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x38
	private static DelegateBridge __Hotfix0_Start; // 0x40
	private static DelegateBridge __Hotfix0__OnScaleChanged; // 0x48
	private static DelegateBridge __Hotfix0__OnScaleStart; // 0x50
	private static DelegateBridge __Hotfix0__OnScaleEnd; // 0x58
	private static DelegateBridge __Hotfix0__CalcInitWrapperSize; // 0x60
	private static DelegateBridge __Hotfix0__ResetIllustPosTween; // 0x68
	private static DelegateBridge __Hotfix0__ResetIllustPos; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	protected RectTransform wrapperRectTrans { get; }

	// RVA: 0x2d72588 VA: 0x759538a588
	protected RectTransform get_wrapperRectTrans() { }
	// RVA: 0x2d7265c VA: 0x759538a65c
	private Void _RecordWrapperStandardStatus() { }
	// RVA: 0x2d726f0 VA: 0x759538a6f0
	public Void NotifySpreadIllust() { }
	// RVA: 0x2d729e0 VA: 0x759538a9e0
	public Void NotifyUnspreadIllust(Boolean withTween) { }
	// RVA: 0x2d72da4 VA: 0x759538ada4
	public override Void OnValueChanged(CharacterIllustViewProperty property) { }
	// RVA: 0x2d72eac VA: 0x759538aeac
	private Void Start() { }
	// RVA: 0x2d73024 VA: 0x759538b024
	private Void _OnScaleChanged(Single scale) { }
	// RVA: 0x2d731b8 VA: 0x759538b1b8
	private Void _OnScaleStart(Single scale) { }
	// RVA: 0x2d73254 VA: 0x759538b254
	private Void _OnScaleEnd(Single scale) { }
	// RVA: 0x2d72848 VA: 0x759538a848
	private Void _CalcInitWrapperSize() { }
	// RVA: 0x2d72a80 VA: 0x759538aa80
	private Void _ResetIllustPosTween() { }
	// RVA: 0x2d72cbc VA: 0x759538acbc
	private Void _ResetIllustPos() { }
	// RVA: 0x2d732f0 VA: 0x759538b2f0
	public Void .ctor() { }
	// RVA: 0x2d733c8 VA: 0x759538b3c8
	private static Void .cctor() { }
	// RVA: 0x2d73434 VA: 0x759538b434
	private Single <_ResetIllustPosTween>b__24_0() { }
	// RVA: 0x2d73450 VA: 0x759538b450
	private Void <_ResetIllustPosTween>b__24_1(Single value) { }
	// RVA: 0x2d7346c VA: 0x759538b46c
	private Void <_ResetIllustPosTween>b__24_2() { }
}
```