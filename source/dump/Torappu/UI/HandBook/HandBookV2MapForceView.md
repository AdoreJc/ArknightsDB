# HandBookV2MapForceView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2MapDotView _dotView`

- `Transform _container`

- `UIStringEvent <onBgClick>k__BackingField`

- `HandBookV2ForceViewModel m_viewModel`


## Properties

- `UIStringEvent onBgClick`


## Methods

- `UIStringEvent get_onBgClick()`

- `Void set_onBgClick(UIStringEvent)`

- `Void _RenderDot(HandBookV2PointData, Boolean)`

- `Void _OnDotClick()`

- `Void Render(HandBookV2ForceViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MapForceView : MonoBehaviour, IHotfixable
{
	private HandBookV2MapDotView _dotView; // 0x18
	private Transform _container; // 0x20
	private UIStringEvent <onBgClick>k__BackingField; // 0x28
	private Dictionary`2 m_mapDotView; // 0x30
	private HandBookV2ForceViewModel m_viewModel; // 0x38
	private static DelegateBridge __Hotfix0_get_onBgClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onBgClick; // 0x8
	private static DelegateBridge __Hotfix0__RenderDot; // 0x10
	private static DelegateBridge __Hotfix0__OnDotClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private UIStringEvent onBgClick { get; set; }

	// RVA: 0x2ed2634 VA: 0x75954ea634
	private UIStringEvent get_onBgClick() { }
	// RVA: 0x2ed269c VA: 0x75954ea69c
	public Void set_onBgClick(UIStringEvent value) { }
	// RVA: 0x2ed2720 VA: 0x75954ea720
	private Void _RenderDot(HandBookV2PointData pointData, Boolean isForceUnlock) { }
	// RVA: 0x2ed2910 VA: 0x75954ea910
	private Void _OnDotClick() { }
	// RVA: 0x2ed2a2c VA: 0x75954eaa2c
	public Void Render(HandBookV2ForceViewModel viewModel) { }
	// RVA: 0x2ed2b4c VA: 0x75954eab4c
	public Void .ctor() { }
}
```