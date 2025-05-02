# BindingList

**Namespace:** `System.ComponentModel`


## Fields

- `Int32 addNewPos`

- `Boolean raiseListChangedEvents`

- `Boolean raiseItemChangedEvents`

- `PropertyDescriptorCollection _itemTypeProperties`

- `PropertyChangedEventHandler _propertyChangedEventHandler`

- `AddingNewEventHandler _onAddingNew`

- `ListChangedEventHandler _onListChanged`

- `Int32 _lastChangeIndex`

- `Boolean allowNew`

- `Boolean allowEdit`

- `Boolean allowRemove`

- `Boolean userSetAllowNew`


## Properties

- `Boolean ItemTypeHasDefaultConstructor`

- `Boolean RaiseListChangedEvents`

- `Boolean AddingNewHandled`

- `Boolean AllowNew`

- `Boolean AllowEdit`

- `Boolean AllowRemove`


## Methods

- `Void Initialize()`

- `Boolean get_ItemTypeHasDefaultConstructor()`

- `Void add_AddingNew(AddingNewEventHandler)`

- `Void remove_AddingNew(AddingNewEventHandler)`

- `Object FireAddingNew()`

- `Void add_ListChanged(ListChangedEventHandler)`

- `Void remove_ListChanged(ListChangedEventHandler)`

- `Boolean get_RaiseListChangedEvents()`

- `Void set_RaiseListChangedEvents(Boolean)`

- `Void ResetBindings()`

- `Void ResetItem(Int32)`

- `Void FireListChanged(ListChangedType, Int32)`

- `T AddNew()`

- `Boolean get_AddingNewHandled()`

- `Boolean get_AllowNew()`

- `Void set_AllowNew(Boolean)`

- `Boolean get_AllowEdit()`

- `Void set_AllowEdit(Boolean)`

- `Boolean get_AllowRemove()`

- `Void set_AllowRemove(Boolean)`

- `Void HookPropertyChanged(T)`

- `Void UnhookPropertyChanged(T)`

- `Void Child_PropertyChanged(Object, PropertyChangedEventArgs)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class BindingList`1 : Collection`1, IBindingList, IList, ICollection, IEnumerable, ICancelAddNew, IRaiseItemChangedEvents
{
	private Int32 addNewPos; // 0x0
	private Boolean raiseListChangedEvents; // 0x0
	private Boolean raiseItemChangedEvents; // 0x0
	private PropertyDescriptorCollection _itemTypeProperties; // 0x0
	private PropertyChangedEventHandler _propertyChangedEventHandler; // 0x0
	private AddingNewEventHandler _onAddingNew; // 0x0
	private ListChangedEventHandler _onListChanged; // 0x0
	private Int32 _lastChangeIndex; // 0x0
	private Boolean allowNew; // 0x0
	private Boolean allowEdit; // 0x0
	private Boolean allowRemove; // 0x0
	private Boolean userSetAllowNew; // 0x0

	private Boolean ItemTypeHasDefaultConstructor { get; }
	public Boolean RaiseListChangedEvents { get; set; }
	private Boolean AddingNewHandled { get; }
	public Boolean AllowNew { get; set; }
	private Boolean System.ComponentModel.IBindingList.AllowNew { get; }
	public Boolean AllowEdit { get; set; }
	private Boolean System.ComponentModel.IBindingList.AllowEdit { get; }
	public Boolean AllowRemove { get; set; }
	private Boolean System.ComponentModel.IBindingList.AllowRemove { get; }
	private Boolean System.ComponentModel.IBindingList.SupportsChangeNotification { get; }
	protected virtual Boolean SupportsChangeNotificationCore { get; }
	private Boolean System.ComponentModel.IBindingList.SupportsSearching { get; }
	protected virtual Boolean SupportsSearchingCore { get; }
	private Boolean System.ComponentModel.IBindingList.SupportsSorting { get; }
	protected virtual Boolean SupportsSortingCore { get; }
	private Boolean System.ComponentModel.IBindingList.IsSorted { get; }
	protected virtual Boolean IsSortedCore { get; }
	private PropertyDescriptor System.ComponentModel.IBindingList.SortProperty { get; }
	protected virtual PropertyDescriptor SortPropertyCore { get; }
	private ListSortDirection System.ComponentModel.IBindingList.SortDirection { get; }
	protected virtual ListSortDirection SortDirectionCore { get; }
	private Boolean System.ComponentModel.IRaiseItemChangedEvents.RaisesItemChangedEvents { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IList`1 list) { }
	// RVA: 0x VA: 0x0
	private Void Initialize() { }
	// RVA: 0x VA: 0x0
	private Boolean get_ItemTypeHasDefaultConstructor() { }
	// RVA: 0x VA: 0x0
	public Void add_AddingNew(AddingNewEventHandler value) { }
	// RVA: 0x VA: 0x0
	public Void remove_AddingNew(AddingNewEventHandler value) { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnAddingNew(AddingNewEventArgs e) { }
	// RVA: 0x VA: 0x0
	private Object FireAddingNew() { }
	// RVA: 0x VA: 0x0
	public Void add_ListChanged(ListChangedEventHandler value) { }
	// RVA: 0x VA: 0x0
	public Void remove_ListChanged(ListChangedEventHandler value) { }
	// RVA: 0x VA: 0x0
	protected virtual Void OnListChanged(ListChangedEventArgs e) { }
	// RVA: 0x VA: 0x0
	public Boolean get_RaiseListChangedEvents() { }
	// RVA: 0x VA: 0x0
	public Void set_RaiseListChangedEvents(Boolean value) { }
	// RVA: 0x VA: 0x0
	public Void ResetBindings() { }
	// RVA: 0x VA: 0x0
	public Void ResetItem(Int32 position) { }
	// RVA: 0x VA: 0x0
	private Void FireListChanged(ListChangedType type, Int32 index) { }
	// RVA: 0x VA: 0x0
	protected override Void ClearItems() { }
	// RVA: 0x VA: 0x0
	protected override Void InsertItem(Int32 index, T item) { }
	// RVA: 0x VA: 0x0
	protected override Void RemoveItem(Int32 index) { }
	// RVA: 0x VA: 0x0
	protected override Void SetItem(Int32 index, T item) { }
	// RVA: 0x VA: 0x0
	public virtual Void CancelNew(Int32 itemIndex) { }
	// RVA: 0x VA: 0x0
	public virtual Void EndNew(Int32 itemIndex) { }
	// RVA: 0x VA: 0x0
	public T AddNew() { }
	// RVA: 0x VA: 0x0
	private Object System.ComponentModel.IBindingList.AddNew() { }
	// RVA: 0x VA: 0x0
	private Boolean get_AddingNewHandled() { }
	// RVA: 0x VA: 0x0
	protected virtual Object AddNewCore() { }
	// RVA: 0x VA: 0x0
	public Boolean get_AllowNew() { }
	// RVA: 0x VA: 0x0
	public Void set_AllowNew(Boolean value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.ComponentModel.IBindingList.get_AllowNew() { }
	// RVA: 0x VA: 0x0
	public Boolean get_AllowEdit() { }
	// RVA: 0x VA: 0x0
	public Void set_AllowEdit(Boolean value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.ComponentModel.IBindingList.get_AllowEdit() { }
	// RVA: 0x VA: 0x0
	public Boolean get_AllowRemove() { }
	// RVA: 0x VA: 0x0
	public Void set_AllowRemove(Boolean value) { }
	// RVA: 0x VA: 0x0
	private Boolean System.ComponentModel.IBindingList.get_AllowRemove() { }
	// RVA: 0x VA: 0x0
	private Boolean System.ComponentModel.IBindingList.get_SupportsChangeNotification() { }
	// RVA: 0x VA: 0x0
	protected virtual Boolean get_SupportsChangeNotificationCore() { }
	// RVA: 0x VA: 0x0
	private Boolean System.ComponentModel.IBindingList.get_SupportsSearching() { }
	// RVA: 0x VA: 0x0
	protected virtual Boolean get_SupportsSearchingCore() { }
	// RVA: 0x VA: 0x0
	private Boolean System.ComponentModel.IBindingList.get_SupportsSorting() { }
	// RVA: 0x VA: 0x0
	protected virtual Boolean get_SupportsSortingCore() { }
	// RVA: 0x VA: 0x0
	private Boolean System.ComponentModel.IBindingList.get_IsSorted() { }
	// RVA: 0x VA: 0x0
	protected virtual Boolean get_IsSortedCore() { }
	// RVA: 0x VA: 0x0
	private PropertyDescriptor System.ComponentModel.IBindingList.get_SortProperty() { }
	// RVA: 0x VA: 0x0
	protected virtual PropertyDescriptor get_SortPropertyCore() { }
	// RVA: 0x VA: 0x0
	private ListSortDirection System.ComponentModel.IBindingList.get_SortDirection() { }
	// RVA: 0x VA: 0x0
	protected virtual ListSortDirection get_SortDirectionCore() { }
	// RVA: 0x VA: 0x0
	private Void System.ComponentModel.IBindingList.ApplySort(PropertyDescriptor prop, ListSortDirection direction) { }
	// RVA: 0x VA: 0x0
	protected virtual Void ApplySortCore(PropertyDescriptor prop, ListSortDirection direction) { }
	// RVA: 0x VA: 0x0
	private Void System.ComponentModel.IBindingList.RemoveSort() { }
	// RVA: 0x VA: 0x0
	protected virtual Void RemoveSortCore() { }
	// RVA: 0x VA: 0x0
	private Int32 System.ComponentModel.IBindingList.Find(PropertyDescriptor prop, Object key) { }
	// RVA: 0x VA: 0x0
	protected virtual Int32 FindCore(PropertyDescriptor prop, Object key) { }
	// RVA: 0x VA: 0x0
	private Void System.ComponentModel.IBindingList.AddIndex(PropertyDescriptor prop) { }
	// RVA: 0x VA: 0x0
	private Void System.ComponentModel.IBindingList.RemoveIndex(PropertyDescriptor prop) { }
	// RVA: 0x VA: 0x0
	private Void HookPropertyChanged(T item) { }
	// RVA: 0x VA: 0x0
	private Void UnhookPropertyChanged(T item) { }
	// RVA: 0x VA: 0x0
	private Void Child_PropertyChanged(Object sender, PropertyChangedEventArgs e) { }
	// RVA: 0x VA: 0x0
	private Boolean System.ComponentModel.IRaiseItemChangedEvents.get_RaisesItemChangedEvents() { }
}
```