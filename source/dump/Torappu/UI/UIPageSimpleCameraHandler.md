# UIPageSimpleCameraHandler

**Namespace:** `Torappu.UI`


## Fields

- `Camera m_simpleCamera`


## Methods

- `Boolean IsValid()`

- `Camera GetSimpleCamera()`

- `SortingInfo GetInitSortingInfo()`

- `Void RequestSimpleCamera()`

- `Void ReleaseSimpleCamera()`

- `Void BindInitCanvasOnSimplePage(Canvas)`

- `Void AdjustSimpleCamToHighest()`

- `Void AdjustSimpleCamToLowest()`

- `Void AdjustSimplePageOrder(UIPage, UIPage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPageSimpleCameraHandler : ISimpleCameraHandler, IHotfixable
{
	private Camera m_simpleCamera; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_IsValid; // 0x8
	private static DelegateBridge __Hotfix0_GetSimpleCamera; // 0x10
	private static DelegateBridge __Hotfix0_GetInitSortingInfo; // 0x18
	private static DelegateBridge __Hotfix0_RequestSimpleCamera; // 0x20
	private static DelegateBridge __Hotfix0_ReleaseSimpleCamera; // 0x28
	private static DelegateBridge __Hotfix0_BindInitCanvasOnSimplePage; // 0x30
	private static DelegateBridge __Hotfix0_AdjustSimpleCamToHighest; // 0x38
	private static DelegateBridge __Hotfix0_AdjustSimpleCamToLowest; // 0x40
	private static DelegateBridge __Hotfix0_AdjustSimplePageOrder; // 0x48


	// RVA: 0x2159838 VA: 0x7594771838
	public Void .ctor(Camera camera) { }
	// RVA: 0x21598cc VA: 0x75947718cc
	public Boolean IsValid() { }
	// RVA: 0x2159964 VA: 0x7594771964
	public Camera GetSimpleCamera() { }
	// RVA: 0x21599cc VA: 0x75947719cc
	public SortingInfo GetInitSortingInfo() { }
	// RVA: 0x2159a30 VA: 0x7594771a30
	public Void RequestSimpleCamera() { }
	// RVA: 0x2159ab0 VA: 0x7594771ab0
	public Void ReleaseSimpleCamera() { }
	// RVA: 0x2159b30 VA: 0x7594771b30
	public Void BindInitCanvasOnSimplePage(Canvas canvas) { }
	// RVA: 0x2159bbc VA: 0x7594771bbc
	public Void AdjustSimpleCamToHighest() { }
	// RVA: 0x2159c88 VA: 0x7594771c88
	public Void AdjustSimpleCamToLowest() { }
	// RVA: 0x2159d38 VA: 0x7594771d38
	public Void AdjustSimplePageOrder(UIPage lower, UIPage upper) { }
}
```