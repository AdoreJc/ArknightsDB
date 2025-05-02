# UIDisposableSender

**Namespace:** `Torappu.UI`


## Fields

- `Boolean <isDisposed>k__BackingField`


## Properties

- `Boolean isDisposed`


## Methods

- `Boolean get_isDisposed()`

- `Void set_isDisposed(Boolean)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIDisposableSender : IDisposable
{
	private ListSet`1 m_wrappedHandlers; // 0x10
	private Boolean <isDisposed>k__BackingField; // 0x18

	public Boolean isDisposed { get; set; }

	// RVA: 0x21d41b4 VA: 0x75947ec1b4
	public Boolean get_isDisposed() { }
	// RVA: 0x21d41bc VA: 0x75947ec1bc
	private Void set_isDisposed(Boolean value) { }
	// RVA: 0x VA: 0x0
	public ResultHandler`1 SendRequest(Request request) { }
	// RVA: 0x21d41c8 VA: 0x75947ec1c8
	public Void Dispose() { }
	// RVA: 0x21d43b0 VA: 0x75947ec3b0
	public Void .ctor() { }
}
```