# UIRecycleHorizonLayoutGroup

**Namespace:** `Torappu.UI`


## Methods

- `Single GetElementPosByIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIRecycleHorizonLayoutGroup : UIRecycleLayoutGroup
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

	// RVA: 0x220f420 VA: 0x7594827420
	public override Single get_preferredWidth() { }
	// RVA: 0x220f4f0 VA: 0x75948274f0
	public override Single get_preferredHeight() { }
	// RVA: 0x220f558 VA: 0x7594827558
	protected override Single get_paddingFront() { }
	// RVA: 0x220f690 VA: 0x7594827690
	protected override Single get_paddingBack() { }
	// RVA: 0x220f704 VA: 0x7594827704
	protected override Void ApplyLayoutMeta(IVirtualView view, LayoutMeta meta) { }
	// RVA: 0x220fb58 VA: 0x7594827b58
	protected override Vector2 GetVisibleRange(Bounds viewBound) { }
	// RVA: 0x220fc10 VA: 0x7594827c10
	public Single GetElementPosByIndex(Int32 index) { }
	// RVA: 0x220fe38 VA: 0x7594827e38
	public Void .ctor() { }
}
```