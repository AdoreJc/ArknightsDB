# RL02OuterBuffMapView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `RL02OuterBuffLineGroupView _lineGroupView`

- `RL02OuterBuffNodeGroupView _nodeGroupView`

- `UITouchZoom _mapTouchZoom`

- `UIWrappedScrollRect _mapScroll`

- `UILayoutDimensionListener _layoutListener`

- `Action <onBackgroundClicked>k__BackingField`

- `IBindings m_bindings`


## Properties

- `Action onBackgroundClicked`


## Methods

- `Void set_onNodeClicked(Action`1)`

- `Action get_onBackgroundClicked()`

- `Void set_onBackgroundClicked(Action)`

- `Void OnInit(UIPage, IBindings)`

- `Void OnBackgroundClicked()`

- `Void _OnSetMapScale(Single)`

- `Void _OnSetMapRangeScale(Single, Single)`

- `Void _OnSetTouchEnabled(Boolean)`

- `Void _OnMapScaleChanged(Single)`

- `Void _OnMapScaleStateChanged(Boolean)`

- `Void _OnMapLayoutChanged()`

- `Void <OnInit>b__15_0(Single)`

- `Void <OnInit>b__15_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffMapView : DataBinder`1, IHotfixable
{
	private RL02OuterBuffLineGroupView _lineGroupView; // 0x20
	private RL02OuterBuffNodeGroupView _nodeGroupView; // 0x28
	private UITouchZoom _mapTouchZoom; // 0x30
	private UIWrappedScrollRect _mapScroll; // 0x38
	private UILayoutDimensionListener _layoutListener; // 0x40
	private Action`1 <onNodeClicked>k__BackingField; // 0x48
	private Action <onBackgroundClicked>k__BackingField; // 0x50
	private IBindings m_bindings; // 0x58
	private static DelegateBridge __Hotfix0_get_onNodeClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onNodeClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onBackgroundClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onBackgroundClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnInit; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0_OnBackgroundClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnSetMapScale; // 0x38
	private static DelegateBridge __Hotfix0__OnSetMapRangeScale; // 0x40
	private static DelegateBridge __Hotfix0__OnSetTouchEnabled; // 0x48
	private static DelegateBridge __Hotfix0__OnMapScaleChanged; // 0x50
	private static DelegateBridge __Hotfix0__OnMapScaleStateChanged; // 0x58
	private static DelegateBridge __Hotfix0__OnMapLayoutChanged; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	private Action`1 onNodeClicked { get; set; }
	private Action onBackgroundClicked { get; set; }

	// RVA: 0x26c17e8 VA: 0x7594cd97e8
	private Action`1 get_onNodeClicked() { }
	// RVA: 0x26bab40 VA: 0x7594cd2b40
	public Void set_onNodeClicked(Action`1 value) { }
	// RVA: 0x26c1850 VA: 0x7594cd9850
	private Action get_onBackgroundClicked() { }
	// RVA: 0x26babc4 VA: 0x7594cd2bc4
	public Void set_onBackgroundClicked(Action value) { }
	// RVA: 0x26bace4 VA: 0x7594cd2ce4
	public Void OnInit(UIPage page, IBindings bindings) { }
	// RVA: 0x26c1a0c VA: 0x7594cd9a0c
	public override Void OnValueChanged(RL02OuterBuffProperty property) { }
	// RVA: 0x26c1bac VA: 0x7594cd9bac
	public Void OnBackgroundClicked() { }
	// RVA: 0x26c1c48 VA: 0x7594cd9c48
	private Void _OnSetMapScale(Single targetScale) { }
	// RVA: 0x26c1cd4 VA: 0x7594cd9cd4
	private Void _OnSetMapRangeScale(Single min, Single max) { }
	// RVA: 0x26c1d6c VA: 0x7594cd9d6c
	private Void _OnSetTouchEnabled(Boolean enabled) { }
	// RVA: 0x26c1e20 VA: 0x7594cd9e20
	private Void _OnMapScaleChanged(Single scale) { }
	// RVA: 0x26c1f8c VA: 0x7594cd9f8c
	private Void _OnMapScaleStateChanged(Boolean isZooming) { }
	// RVA: 0x26c20a8 VA: 0x7594cda0a8
	private Void _OnMapLayoutChanged() { }
	// RVA: 0x26c22b4 VA: 0x7594cda2b4
	public Void .ctor() { }
	// RVA: 0x26c2344 VA: 0x7594cda344
	private Void <OnInit>b__15_0(Single scale) { }
	// RVA: 0x26c2370 VA: 0x7594cda370
	private Void <OnInit>b__15_1(Single scale) { }
}
```