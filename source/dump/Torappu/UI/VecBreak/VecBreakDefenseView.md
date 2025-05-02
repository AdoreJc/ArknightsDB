# VecBreakDefenseView

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `Text _rightText`

- `VecBreakDefenseStageAdapter _adapter`

- `UILayoutDimensionListener _listener`

- `LoopHorizontalScrollRect _scrollRect`

- `GridLayoutGroup _layout`


## Methods

- `Void _FocusToItem(Int32)`

- `Void _DoFocusAction(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakDefenseView : DataBinder`1, IHotfixable
{
	private Text _rightText; // 0x20
	private VecBreakDefenseStageAdapter _adapter; // 0x28
	private UILayoutDimensionListener _listener; // 0x30
	private LoopHorizontalScrollRect _scrollRect; // 0x38
	private GridLayoutGroup _layout; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__FocusToItem; // 0x8
	private static DelegateBridge __Hotfix0__DoFocusAction; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x22cdd10 VA: 0x75948e5d10
	public override Void OnValueChanged(VecBreakDefenseProp property) { }
	// RVA: 0x22cde18 VA: 0x75948e5e18
	private Void _FocusToItem(Int32 index) { }
	// RVA: 0x22cdf70 VA: 0x75948e5f70
	private Void _DoFocusAction(Int32 index) { }
	// RVA: 0x22ce15c VA: 0x75948e615c
	public Void .ctor() { }
}
```