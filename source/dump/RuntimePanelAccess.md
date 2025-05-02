# RuntimePanelAccess

**Namespace:** ` `


## Fields

- `BaseRuntimePanel m_RuntimePanel`


## Methods

- `BaseRuntimePanel CreateRelatedRuntimePanel()`

- `Void DisposeRelatedPanel()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : 
private class RuntimePanelAccess
{
	private readonly PanelSettings m_Settings; // 0x10
	private BaseRuntimePanel m_RuntimePanel; // 0x18

	internal Boolean isInitialized { get; }
	internal BaseRuntimePanel panel { get; }

	// RVA: 0x6a01200 VA: 0x7599019200
	internal Void .ctor(PanelSettings settings) { }
	// RVA: 0x6a01560 VA: 0x7599019560
	internal Boolean get_isInitialized() { }
	// RVA: 0x6a00fa0 VA: 0x7599018fa0
	internal BaseRuntimePanel get_panel() { }
	// RVA: 0x6a014f8 VA: 0x75990194f8
	internal Void DisposePanel() { }
	// RVA: 0x6a00d78 VA: 0x7599018d78
	internal Void SetTargetTexture() { }
	// RVA: 0x6a00ea4 VA: 0x7599018ea4
	internal Void SetSortingPriority() { }
	// RVA: 0x6a00f14 VA: 0x7599018f14
	internal Void SetTargetDisplay() { }
	// RVA: 0x6a02464 VA: 0x759901a464
	private BaseRuntimePanel CreateRelatedRuntimePanel() { }
	// RVA: 0x6a0255c VA: 0x759901a55c
	private Void DisposeRelatedPanel() { }
	// RVA: 0x6a02408 VA: 0x759901a408
	internal Void MarkPotentiallyEmpty() { }
}
```