# RoguelikeEntryBottomView

**Namespace:** `Torappu.UI.RoguelikeEntry`


## Fields

- `RoguelikeEntryBottomAdapter _adapter`

- `UILayoutDimensionListener _listener`

- `LoopHorizontalScrollRect _scrollRect`

- `GridLayoutGroup _layout`

- `Int32 m_cachedSequenceId`

- `Tween m_cachedTween`


## Methods

- `Void _FocusToItem(Int32)`

- `Single <_FocusToItem>b__10_0()`

- `Void <_FocusToItem>b__10_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeEntry
public class RoguelikeEntryBottomView : DataBinder`1, IHotfixable
{
	private const Single FOCUS_DURATION; // 0x0
	private const Int32 SLIDE_MAX_LENGTH; // 0x0
	private RoguelikeEntryBottomAdapter _adapter; // 0x20
	private UILayoutDimensionListener _listener; // 0x28
	private LoopHorizontalScrollRect _scrollRect; // 0x30
	private GridLayoutGroup _layout; // 0x38
	private Int32 m_cachedSequenceId; // 0x40
	private Tween m_cachedTween; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__FocusToItem; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x262fe78 VA: 0x7594c47e78
	public override Void OnValueChanged(RoguelikeEntryProperty property) { }
	// RVA: 0x2630000 VA: 0x7594c48000
	private Void _FocusToItem(Int32 targetIndex) { }
	// RVA: 0x2630470 VA: 0x7594c48470
	public Void .ctor() { }
	// RVA: 0x2630508 VA: 0x7594c48508
	private Single <_FocusToItem>b__10_0() { }
	// RVA: 0x2630524 VA: 0x7594c48524
	private Void <_FocusToItem>b__10_1(Single value) { }
}
```