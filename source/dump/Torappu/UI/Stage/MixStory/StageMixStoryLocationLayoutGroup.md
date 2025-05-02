# StageMixStoryLocationLayoutGroup

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `RectTransform _dynamicRectRoot`

- `RectTransform _dynamicPaddingFront`

- `RectTransform _dynamicPaddingBack`

- `RectTransform _dynamicFocusRect`

- `Action <itemLayoutStartEvent>k__BackingField`

- `Action <itemLayoutEndEvent>k__BackingField`


## Properties

- `Action itemLayoutStartEvent`

- `Action itemLayoutEndEvent`

- `Single focusPosition`


## Methods

- `Action get_itemLayoutStartEvent()`

- `Void set_itemLayoutStartEvent(Action)`

- `Void set_itemLayoutEvent(Action`3)`

- `Action get_itemLayoutEndEvent()`

- `Void set_itemLayoutEndEvent(Action)`

- `Single get_focusPosition()`

- `Single <>xLuaBaseProxy_get_paddingFront()`

- `Single <>xLuaBaseProxy_get_paddingBack()`

- `Void <>xLuaBaseProxy_LateUpdate()`

- `Void <>xLuaBaseProxy_ApplyLayoutMeta(IVirtualView, LayoutMeta)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryLocationLayoutGroup : UIRecycleHorizonLayoutGroup
{
	private RectTransform _dynamicRectRoot; // 0x60
	private RectTransform _dynamicPaddingFront; // 0x68
	private RectTransform _dynamicPaddingBack; // 0x70
	private RectTransform _dynamicFocusRect; // 0x78
	private Action <itemLayoutStartEvent>k__BackingField; // 0x80
	private Action`3 <itemLayoutEvent>k__BackingField; // 0x88
	private Action <itemLayoutEndEvent>k__BackingField; // 0x90
	private static DelegateBridge __Hotfix0_get_itemLayoutStartEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_itemLayoutStartEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_itemLayoutEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_itemLayoutEvent; // 0x18
	private static DelegateBridge __Hotfix0_get_itemLayoutEndEvent; // 0x20
	private static DelegateBridge __Hotfix0_set_itemLayoutEndEvent; // 0x28
	private static DelegateBridge __Hotfix0_get_focusPosition; // 0x30
	private static DelegateBridge __Hotfix0_get_paddingFront; // 0x38
	private static DelegateBridge __Hotfix0_get_paddingBack; // 0x40
	private static DelegateBridge __Hotfix0_LateUpdate; // 0x48
	private static DelegateBridge __Hotfix0_ApplyLayoutMeta; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private Action itemLayoutStartEvent { get; set; }
	private Action`3 itemLayoutEvent { get; set; }
	private Action itemLayoutEndEvent { get; set; }
	public Single focusPosition { get; }
	protected override Single paddingFront { get; }
	protected override Single paddingBack { get; }

	// RVA: 0x2fe7154 VA: 0x75955ff154
	private Action get_itemLayoutStartEvent() { }
	// RVA: 0x2fe71bc VA: 0x75955ff1bc
	public Void set_itemLayoutStartEvent(Action value) { }
	// RVA: 0x2fe7240 VA: 0x75955ff240
	private Action`3 get_itemLayoutEvent() { }
	// RVA: 0x2fe72a8 VA: 0x75955ff2a8
	public Void set_itemLayoutEvent(Action`3 value) { }
	// RVA: 0x2fe732c VA: 0x75955ff32c
	private Action get_itemLayoutEndEvent() { }
	// RVA: 0x2fe7394 VA: 0x75955ff394
	public Void set_itemLayoutEndEvent(Action value) { }
	// RVA: 0x2fe7418 VA: 0x75955ff418
	public Single get_focusPosition() { }
	// RVA: 0x2fe753c VA: 0x75955ff53c
	protected override Single get_paddingFront() { }
	// RVA: 0x2fe765c VA: 0x75955ff65c
	protected override Single get_paddingBack() { }
	// RVA: 0x2fe7780 VA: 0x75955ff780
	protected override Void LateUpdate() { }
	// RVA: 0x2fe7854 VA: 0x75955ff854
	protected override Void ApplyLayoutMeta(IVirtualView view, LayoutMeta meta) { }
	// RVA: 0x2fe79e0 VA: 0x75955ff9e0
	public Void .ctor() { }
	// RVA: 0x2fe7a50 VA: 0x75955ffa50
	private Single <>xLuaBaseProxy_get_paddingFront() { }
	// RVA: 0x2fe7a58 VA: 0x75955ffa58
	private Single <>xLuaBaseProxy_get_paddingBack() { }
	// RVA: 0x2fe7a60 VA: 0x75955ffa60
	private Void <>xLuaBaseProxy_LateUpdate() { }
	// RVA: 0x2fe7a68 VA: 0x75955ffa68
	private Void <>xLuaBaseProxy_ApplyLayoutMeta(IVirtualView P0, LayoutMeta P1) { }
}
```