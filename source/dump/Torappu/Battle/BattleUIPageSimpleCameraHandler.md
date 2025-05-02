# BattleUIPageSimpleCameraHandler

**Namespace:** `Torappu.Battle`


## Fields

- `Camera m_simpleCamera`


## Methods

- `Camera GetSimpleCamera()`

- `Boolean IsValid()`

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
// Namespace : Torappu.Battle
public class BattleUIPageSimpleCameraHandler : ISimpleCameraHandler, IHotfixable
{
	private const Int32 BATTLE_UI_SIMPLE_PAGE_SORTING_ORDER_LOWER_BASE; // 0x0
	private const Int32 BATTLE_UI_SIMPLE_PAGE_SORTING_ORDER_BASE; // 0x0
	private Camera m_simpleCamera; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetSimpleCamera; // 0x8
	private static DelegateBridge __Hotfix0_IsValid; // 0x10
	private static DelegateBridge __Hotfix0_GetInitSortingInfo; // 0x18
	private static DelegateBridge __Hotfix0_RequestSimpleCamera; // 0x20
	private static DelegateBridge __Hotfix0_ReleaseSimpleCamera; // 0x28
	private static DelegateBridge __Hotfix0_BindInitCanvasOnSimplePage; // 0x30
	private static DelegateBridge __Hotfix0_AdjustSimpleCamToHighest; // 0x38
	private static DelegateBridge __Hotfix0_AdjustSimpleCamToLowest; // 0x40
	private static DelegateBridge __Hotfix0_AdjustSimplePageOrder; // 0x48


	// RVA: 0x1bdd518 VA: 0x75941f5518
	public Void .ctor(Camera camera) { }
	// RVA: 0x1bde42c VA: 0x75941f642c
	public Camera GetSimpleCamera() { }
	// RVA: 0x1bde494 VA: 0x75941f6494
	public Boolean IsValid() { }
	// RVA: 0x1bde52c VA: 0x75941f652c
	public SortingInfo GetInitSortingInfo() { }
	// RVA: 0x1bde594 VA: 0x75941f6594
	public Void RequestSimpleCamera() { }
	// RVA: 0x1bde5f8 VA: 0x75941f65f8
	public Void ReleaseSimpleCamera() { }
	// RVA: 0x1bde65c VA: 0x75941f665c
	public Void BindInitCanvasOnSimplePage(Canvas canvas) { }
	// RVA: 0x1bde6e8 VA: 0x75941f66e8
	public Void AdjustSimpleCamToHighest() { }
	// RVA: 0x1bde74c VA: 0x75941f674c
	public Void AdjustSimpleCamToLowest() { }
	// RVA: 0x1bde7b0 VA: 0x75941f67b0
	public Void AdjustSimplePageOrder(UIPage lower, UIPage upper) { }
}
```