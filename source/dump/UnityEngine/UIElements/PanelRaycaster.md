# PanelRaycaster

**Namespace:** `UnityEngine.UIElements`


## Fields

- `BaseRuntimePanel m_Panel`


## Properties

- `IPanel panel`

- `GameObject selectableGameObject`


## Methods

- `IPanel get_panel()`

- `Void set_panel(IPanel)`

- `Void RegisterCallbacks()`

- `Void UnregisterCallbacks()`

- `Void OnPanelDestroyed()`

- `GameObject get_selectableGameObject()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UIElements
public class PanelRaycaster : BaseRaycaster, IRuntimePanelComponent
{
	private BaseRuntimePanel m_Panel; // 0x20

	public IPanel panel { get; set; }
	private GameObject selectableGameObject { get; }
	public override Int32 sortOrderPriority { get; }
	public override Int32 renderOrderPriority { get; }
	public override Camera eventCamera { get; }

	// RVA: 0x6a74d58 VA: 0x759908cd58
	public IPanel get_panel() { }
	// RVA: 0x6a74d60 VA: 0x759908cd60
	public Void set_panel(IPanel value) { }
	// RVA: 0x6a74eac VA: 0x759908ceac
	private Void RegisterCallbacks() { }
	// RVA: 0x6a74e14 VA: 0x759908ce14
	private Void UnregisterCallbacks() { }
	// RVA: 0x6a74f44 VA: 0x759908cf44
	private Void OnPanelDestroyed() { }
	// RVA: 0x6a74f4c VA: 0x759908cf4c
	private GameObject get_selectableGameObject() { }
	// RVA: 0x6a74f64 VA: 0x759908cf64
	public override Int32 get_sortOrderPriority() { }
	// RVA: 0x6a74f98 VA: 0x759908cf98
	public override Int32 get_renderOrderPriority() { }
	// RVA: 0x6a74fb8 VA: 0x759908cfb8
	public override Void Raycast(PointerEventData eventData, List`1 resultAppendList) { }
	// RVA: 0x6a75540 VA: 0x759908d540
	public override Camera get_eventCamera() { }
	// RVA: 0x6a74fb0 VA: 0x759908cfb0
	private static Int32 ConvertFloatBitsToInt(Single f) { }
	// RVA: 0x6a75548 VA: 0x759908d548
	public Void .ctor() { }
}
```