# CriFsRequest

**Namespace:** `CriWare`


## Fields

- `DoneDelegate <doneDelegate>k__BackingField`

- `Boolean <isDone>k__BackingField`

- `String <error>k__BackingField`

- `Boolean <isDisposed>k__BackingField`


## Properties

- `DoneDelegate doneDelegate`

- `Boolean isDone`

- `String error`

- `Boolean isDisposed`


## Methods

- `DoneDelegate get_doneDelegate()`

- `Void set_doneDelegate(DoneDelegate)`

- `Boolean get_isDone()`

- `Void set_isDone(Boolean)`

- `String get_error()`

- `Void set_error(String)`

- `Boolean get_isDisposed()`

- `Void set_isDisposed(Boolean)`

- `YieldInstruction WaitForDone(MonoBehaviour)`

- `Void Done()`

- `IEnumerator CheckDone()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriFsRequest : CriDisposable
{
	private DoneDelegate <doneDelegate>k__BackingField; // 0x20
	private Boolean <isDone>k__BackingField; // 0x28
	private String <error>k__BackingField; // 0x30
	private Boolean <isDisposed>k__BackingField; // 0x38

	public DoneDelegate doneDelegate { get; set; }
	public Boolean isDone { get; set; }
	public String error { get; set; }
	public Boolean isDisposed { get; set; }

	// RVA: 0x413f6e4 VA: 0x75967576e4
	public DoneDelegate get_doneDelegate() { }
	// RVA: 0x413f6ec VA: 0x75967576ec
	protected Void set_doneDelegate(DoneDelegate value) { }
	// RVA: 0x413f6f4 VA: 0x75967576f4
	public Boolean get_isDone() { }
	// RVA: 0x413f6fc VA: 0x75967576fc
	private Void set_isDone(Boolean value) { }
	// RVA: 0x413f708 VA: 0x7596757708
	public String get_error() { }
	// RVA: 0x413f710 VA: 0x7596757710
	protected Void set_error(String value) { }
	// RVA: 0x413f718 VA: 0x7596757718
	public Boolean get_isDisposed() { }
	// RVA: 0x413f720 VA: 0x7596757720
	protected Void set_isDisposed(Boolean value) { }
	// RVA: 0x413f72c VA: 0x759675772c
	public override Void Dispose() { }
	// RVA: 0x413f7b4 VA: 0x75967577b4
	public virtual Void Stop() { }
	// RVA: 0x413f7b8 VA: 0x75967577b8
	public YieldInstruction WaitForDone(MonoBehaviour mb) { }
	// RVA: 0x413f854 VA: 0x7596757854
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x413f858 VA: 0x7596757858
	public virtual Void Update() { }
	// RVA: 0x413f85c VA: 0x759675785c
	protected Void Done() { }
	// RVA: 0x413f7e0 VA: 0x75967577e0
	private IEnumerator CheckDone() { }
	// RVA: 0x413f8ac VA: 0x75967578ac
	protected override Void Finalize() { }
	// RVA: 0x413f960 VA: 0x7596757960
	public Void .ctor() { }
}
```