# UIRecycleVerticalLayoutGroup

**Namespace:** `Torappu.UI`


## Methods

- `Single GetElementPosByIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIRecycleVerticalLayoutGroup : UIRecycleLayoutGroup
{
	private static DelegateBridge __Hotfix0_get_preferredWidth; // 0x0
	private static DelegateBridge __Hotfix0_get_preferredHeight; // 0x8
	private static DelegateBridge __Hotfix0_get_paddingFront; // 0x10
	private static DelegateBridge __Hotfix0_get_paddingBack; // 0x18
	private static DelegateBridge __Hotfix0_ApplyLayoutMeta; // 0x20
	private static DelegateBridge __Hotfix0_GetVisibleRange; // 0x28
	private static DelegateBridge __Hotfix0_GetElementPosByIndex; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override Single preferredWidth { get; }
	public override Single preferredHeight { get; }
	protected override Single paddingFront { get; }
	protected override Single paddingBack { get; }

	// RVA: 0x2212e50 VA: 0x759482ae50
	public override Single get_preferredWidth() { }
	// RVA: 0x2212eb8 VA: 0x759482aeb8
	public override Single get_preferredHeight() { }
	// RVA: 0x2212f20 VA: 0x759482af20
	protected override Single get_paddingFront() { }
	// RVA: 0x2212f90 VA: 0x759482af90
	protected override Single get_paddingBack() { }
	// RVA: 0x2213000 VA: 0x759482b000
	protected override Void ApplyLayoutMeta(IVirtualView view, LayoutMeta meta) { }
	// RVA: 0x22133f0 VA: 0x759482b3f0
	protected override Vector2 GetVisibleRange(Bounds viewBound) { }
	// RVA: 0x22134a4 VA: 0x759482b4a4
	public Single GetElementPosByIndex(Int32 index) { }
	// RVA: 0x2213530 VA: 0x759482b530
	public Void .ctor() { }
}
```