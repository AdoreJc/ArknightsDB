# EventCallbackList

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Int32 <trickleDownCallbackCount>k__BackingField`

- `Int32 <bubbleUpCallbackCount>k__BackingField`


## Properties

- `Int32 trickleDownCallbackCount`

- `Int32 bubbleUpCallbackCount`

- `Int32 Count`

- `EventCallbackFunctorBase Item`


## Methods

- `Int32 get_trickleDownCallbackCount()`

- `Void set_trickleDownCallbackCount(Int32)`

- `Int32 get_bubbleUpCallbackCount()`

- `Void set_bubbleUpCallbackCount(Int32)`

- `Boolean Contains(Int64, Delegate, CallbackPhase)`

- `EventCallbackFunctorBase Find(Int64, Delegate, CallbackPhase)`

- `Boolean Remove(Int64, Delegate, CallbackPhase)`

- `Void Add(EventCallbackFunctorBase)`

- `Void AddRange(EventCallbackList)`

- `Int32 get_Count()`

- `EventCallbackFunctorBase get_Item(Int32)`

- `Void Clear()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class EventCallbackList
{
	private List`1 m_List; // 0x10
	private Int32 <trickleDownCallbackCount>k__BackingField; // 0x18
	private Int32 <bubbleUpCallbackCount>k__BackingField; // 0x1c

	public Int32 trickleDownCallbackCount { get; set; }
	public Int32 bubbleUpCallbackCount { get; set; }
	public Int32 Count { get; }
	public EventCallbackFunctorBase Item { get; }

	// RVA: 0x69e157c VA: 0x7598ff957c
	public Int32 get_trickleDownCallbackCount() { }
	// RVA: 0x69e1584 VA: 0x7598ff9584
	private Void set_trickleDownCallbackCount(Int32 value) { }
	// RVA: 0x69e158c VA: 0x7598ff958c
	public Int32 get_bubbleUpCallbackCount() { }
	// RVA: 0x69e1594 VA: 0x7598ff9594
	private Void set_bubbleUpCallbackCount(Int32 value) { }
	// RVA: 0x69e1204 VA: 0x7598ff9204
	public Void .ctor() { }
	// RVA: 0x69e1164 VA: 0x7598ff9164
	public Void .ctor(EventCallbackList source) { }
	// RVA: 0x69e159c VA: 0x7598ff959c
	public Boolean Contains(Int64 eventTypeId, Delegate callback, CallbackPhase phase) { }
	// RVA: 0x69e15b4 VA: 0x7598ff95b4
	public EventCallbackFunctorBase Find(Int64 eventTypeId, Delegate callback, CallbackPhase phase) { }
	// RVA: 0x69e169c VA: 0x7598ff969c
	public Boolean Remove(Int64 eventTypeId, Delegate callback, CallbackPhase phase) { }
	// RVA: 0x69e17bc VA: 0x7598ff97bc
	public Void Add(EventCallbackFunctorBase item) { }
	// RVA: 0x69e1294 VA: 0x7598ff9294
	public Void AddRange(EventCallbackList list) { }
	// RVA: 0x69e18a4 VA: 0x7598ff98a4
	public Int32 get_Count() { }
	// RVA: 0x69e18ec VA: 0x7598ff98ec
	public EventCallbackFunctorBase get_Item(Int32 i) { }
	// RVA: 0x69e1488 VA: 0x7598ff9488
	public Void Clear() { }
}
```