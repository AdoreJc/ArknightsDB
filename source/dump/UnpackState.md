# UnpackState

**Namespace:** ` `


## Fields

- `Boolean m_isAuto`

- `Boolean m_isZipperSePlaying`

- `AnimationState m_animState`

- `BagLightController m_bagLight`

- `Single m_remainingDelta`

- `Single m_cachedCurProgress`

- `Single m_cachedLastProgress`


## Properties

- `Single progress`

- `Boolean isZipperSePlaying`


## Methods

- `Single get_progress()`

- `Void set_progress(Single)`

- `Boolean get_isZipperSePlaying()`

- `Void set_isZipperSePlaying(Boolean)`

- `Void _BeginAutoPhase()`

- `Void _StopDragPhase()`

- `Void _OnDrag(PointerEventData)`

- `Void _OnBeginDrag(PointerEventData)`

- `Void _OnEndDrag(PointerEventData)`

- `Void _GotoNext()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class UnpackState : StateNode
{
	private Boolean m_isAuto; // 0x18
	private Boolean m_isZipperSePlaying; // 0x19
	private AnimationState m_animState; // 0x20
	private BagLightController m_bagLight; // 0x28
	private Single m_remainingDelta; // 0x30
	private Single m_cachedCurProgress; // 0x34
	private Single m_cachedLastProgress; // 0x38

	public Single progress { get; set; }
	private Boolean isZipperSePlaying { get; set; }

	// RVA: 0x36fdc38 VA: 0x7595d15c38
	public Single get_progress() { }
	// RVA: 0x36fdc7c VA: 0x7595d15c7c
	private Void set_progress(Single value) { }
	// RVA: 0x36fdce0 VA: 0x7595d15ce0
	private Boolean get_isZipperSePlaying() { }
	// RVA: 0x36fdce8 VA: 0x7595d15ce8
	private Void set_isZipperSePlaying(Boolean value) { }
	// RVA: 0x36fdda4 VA: 0x7595d15da4
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x36fe1ec VA: 0x7595d161ec
	public override Void OnTick(FP deltaTimeFp) { }
	// RVA: 0x36fe714 VA: 0x7595d16714
	public override Void OnExit(Int32 newState) { }
	// RVA: 0x36fe49c VA: 0x7595d1649c
	private Void _BeginAutoPhase() { }
	// RVA: 0x36fe794 VA: 0x7595d16794
	private Void _StopDragPhase() { }
	// RVA: 0x36feab8 VA: 0x7595d16ab8
	private Void _OnDrag(PointerEventData evData) { }
	// RVA: 0x36febdc VA: 0x7595d16bdc
	private Void _OnBeginDrag(PointerEventData evData) { }
	// RVA: 0x36fecf8 VA: 0x7595d16cf8
	private Void _OnEndDrag(PointerEventData evData) { }
	// RVA: 0x36feeac VA: 0x7595d16eac
	private Void _GotoNext() { }
	// RVA: 0x36fd94c VA: 0x7595d1594c
	public Void .ctor() { }
}
```