# UpdaterArray

**Namespace:** ` `


## Properties

- `IVisualTreeUpdater Item`

- `IVisualTreeUpdater Item`


## Methods

- `Void set_Item(VisualTreeUpdatePhase, IVisualTreeUpdater)`

- `IVisualTreeUpdater get_Item(VisualTreeUpdatePhase)`

- `IVisualTreeUpdater get_Item(Int32)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : 
private class UpdaterArray
{
	private IVisualTreeUpdater[] m_VisualTreeUpdaters; // 0x10

	public IVisualTreeUpdater Item { get; set; }
	public IVisualTreeUpdater Item { get; }

	// RVA: 0x699b060 VA: 0x7598fb3060
	public Void .ctor() { }
	// RVA: 0x699b684 VA: 0x7598fb3684
	public Void set_Item(VisualTreeUpdatePhase phase, IVisualTreeUpdater value) { }
	// RVA: 0x699b554 VA: 0x7598fb3554
	public IVisualTreeUpdater get_Item(VisualTreeUpdatePhase phase) { }
	// RVA: 0x699b2cc VA: 0x7598fb32cc
	public IVisualTreeUpdater get_Item(Int32 index) { }
}
```