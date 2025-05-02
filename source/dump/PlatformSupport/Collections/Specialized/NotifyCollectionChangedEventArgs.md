# NotifyCollectionChangedEventArgs

**Namespace:** `PlatformSupport.Collections.Specialized`


## Fields

- `NotifyCollectionChangedAction _action`

- `IList _newItems`

- `IList _oldItems`

- `Int32 _newStartingIndex`

- `Int32 _oldStartingIndex`


## Properties

- `NotifyCollectionChangedAction Action`

- `IList NewItems`

- `IList OldItems`

- `Int32 NewStartingIndex`

- `Int32 OldStartingIndex`


## Methods

- `Void InitializeAddOrRemove(NotifyCollectionChangedAction, IList, Int32)`

- `Void InitializeAdd(NotifyCollectionChangedAction, IList, Int32)`

- `Void InitializeRemove(NotifyCollectionChangedAction, IList, Int32)`

- `Void InitializeMoveOrReplace(NotifyCollectionChangedAction, IList, IList, Int32, Int32)`

- `NotifyCollectionChangedAction get_Action()`

- `IList get_NewItems()`

- `IList get_OldItems()`

- `Int32 get_NewStartingIndex()`

- `Int32 get_OldStartingIndex()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : PlatformSupport.Collections.Specialized
public class NotifyCollectionChangedEventArgs : EventArgs
{
	private NotifyCollectionChangedAction _action; // 0x10
	private IList _newItems; // 0x18
	private IList _oldItems; // 0x20
	private Int32 _newStartingIndex; // 0x28
	private Int32 _oldStartingIndex; // 0x2c

	public NotifyCollectionChangedAction Action { get; }
	public IList NewItems { get; }
	public IList OldItems { get; }
	public Int32 NewStartingIndex { get; }
	public Int32 OldStartingIndex { get; }

	// RVA: 0x65e0b10 VA: 0x7598bf8b10
	public Void .ctor(NotifyCollectionChangedAction action) { }
	// RVA: 0x65e0c88 VA: 0x7598bf8c88
	public Void .ctor(NotifyCollectionChangedAction action, Object changedItem) { }
	// RVA: 0x65e0e10 VA: 0x7598bf8e10
	public Void .ctor(NotifyCollectionChangedAction action, Object changedItem, Int32 index) { }
	// RVA: 0x65e0f98 VA: 0x7598bf8f98
	public Void .ctor(NotifyCollectionChangedAction action, IList changedItems) { }
	// RVA: 0x65e10e0 VA: 0x7598bf90e0
	public Void .ctor(NotifyCollectionChangedAction action, IList changedItems, Int32 startingIndex) { }
	// RVA: 0x65e126c VA: 0x7598bf926c
	public Void .ctor(NotifyCollectionChangedAction action, Object newItem, Object oldItem) { }
	// RVA: 0x65e1458 VA: 0x7598bf9458
	public Void .ctor(NotifyCollectionChangedAction action, Object newItem, Object oldItem, Int32 index) { }
	// RVA: 0x65e1604 VA: 0x7598bf9604
	public Void .ctor(NotifyCollectionChangedAction action, IList newItems, IList oldItems) { }
	// RVA: 0x65e1760 VA: 0x7598bf9760
	public Void .ctor(NotifyCollectionChangedAction action, IList newItems, IList oldItems, Int32 startingIndex) { }
	// RVA: 0x65e18c0 VA: 0x7598bf98c0
	public Void .ctor(NotifyCollectionChangedAction action, Object changedItem, Int32 index, Int32 oldIndex) { }
	// RVA: 0x65e1a50 VA: 0x7598bf9a50
	public Void .ctor(NotifyCollectionChangedAction action, IList changedItems, Int32 index, Int32 oldIndex) { }
	// RVA: 0x65e1b74 VA: 0x7598bf9b74
	internal Void .ctor(NotifyCollectionChangedAction action, IList newItems, IList oldItems, Int32 newIndex, Int32 oldIndex) { }
	// RVA: 0x65e0df8 VA: 0x7598bf8df8
	private Void InitializeAddOrRemove(NotifyCollectionChangedAction action, IList changedItems, Int32 startingIndex) { }
	// RVA: 0x65e0be4 VA: 0x7598bf8be4
	private Void InitializeAdd(NotifyCollectionChangedAction action, IList newItems, Int32 newStartingIndex) { }
	// RVA: 0x65e1cdc VA: 0x7598bf9cdc
	private Void InitializeRemove(NotifyCollectionChangedAction action, IList oldItems, Int32 oldStartingIndex) { }
	// RVA: 0x65e1414 VA: 0x7598bf9414
	private Void InitializeMoveOrReplace(NotifyCollectionChangedAction action, IList newItems, IList oldItems, Int32 startingIndex, Int32 oldStartingIndex) { }
	// RVA: 0x65e1d80 VA: 0x7598bf9d80
	public NotifyCollectionChangedAction get_Action() { }
	// RVA: 0x65e1d88 VA: 0x7598bf9d88
	public IList get_NewItems() { }
	// RVA: 0x65e1d90 VA: 0x7598bf9d90
	public IList get_OldItems() { }
	// RVA: 0x65e1d98 VA: 0x7598bf9d98
	public Int32 get_NewStartingIndex() { }
	// RVA: 0x65e1da0 VA: 0x7598bf9da0
	public Int32 get_OldStartingIndex() { }
}
```