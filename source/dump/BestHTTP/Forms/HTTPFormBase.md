# HTTPFormBase

**Namespace:** `BestHTTP.Forms`


## Fields

- `Boolean <IsChanged>k__BackingField`

- `Boolean <HasBinary>k__BackingField`

- `Boolean <HasLongValue>k__BackingField`


## Properties

- `Boolean IsEmpty`

- `Boolean IsChanged`

- `Boolean HasBinary`

- `Boolean HasLongValue`


## Methods

- `Void set_Fields(List`1)`

- `Boolean get_IsEmpty()`

- `Boolean get_IsChanged()`

- `Void set_IsChanged(Boolean)`

- `Boolean get_HasBinary()`

- `Void set_HasBinary(Boolean)`

- `Boolean get_HasLongValue()`

- `Void set_HasLongValue(Boolean)`

- `Void AddBinaryData(String, Byte[])`

- `Void AddBinaryData(String, Byte[], String)`

- `Void AddBinaryData(String, Byte[], String, String)`

- `Void AddField(String, String)`

- `Void AddField(String, String, Encoding)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.Forms
public class HTTPFormBase
{
	private const Int32 LongLength; // 0x0
	private List`1 <Fields>k__BackingField; // 0x10
	private Boolean <IsChanged>k__BackingField; // 0x18
	private Boolean <HasBinary>k__BackingField; // 0x19
	private Boolean <HasLongValue>k__BackingField; // 0x1a

	public List`1 Fields { get; set; }
	public Boolean IsEmpty { get; }
	public Boolean IsChanged { get; set; }
	public Boolean HasBinary { get; set; }
	public Boolean HasLongValue { get; set; }

	// RVA: 0x661ab10 VA: 0x7598c32b10
	public List`1 get_Fields() { }
	// RVA: 0x661ab18 VA: 0x7598c32b18
	public Void set_Fields(List`1 value) { }
	// RVA: 0x661ab20 VA: 0x7598c32b20
	public Boolean get_IsEmpty() { }
	// RVA: 0x661ab74 VA: 0x7598c32b74
	public Boolean get_IsChanged() { }
	// RVA: 0x661ab7c VA: 0x7598c32b7c
	protected Void set_IsChanged(Boolean value) { }
	// RVA: 0x661ab88 VA: 0x7598c32b88
	public Boolean get_HasBinary() { }
	// RVA: 0x661ab90 VA: 0x7598c32b90
	protected Void set_HasBinary(Boolean value) { }
	// RVA: 0x661ab9c VA: 0x7598c32b9c
	public Boolean get_HasLongValue() { }
	// RVA: 0x661aba4 VA: 0x7598c32ba4
	protected Void set_HasLongValue(Boolean value) { }
	// RVA: 0x661abb0 VA: 0x7598c32bb0
	public Void AddBinaryData(String fieldName, Byte[] content) { }
	// RVA: 0x661adb8 VA: 0x7598c32db8
	public Void AddBinaryData(String fieldName, Byte[] content, String fileName) { }
	// RVA: 0x661abbc VA: 0x7598c32bbc
	public Void AddBinaryData(String fieldName, Byte[] content, String fileName, String mimeType) { }
	// RVA: 0x661adc0 VA: 0x7598c32dc0
	public Void AddField(String fieldName, String value) { }
	// RVA: 0x661adf8 VA: 0x7598c32df8
	public Void AddField(String fieldName, String value, Encoding e) { }
	// RVA: 0x661aff8 VA: 0x7598c32ff8
	public virtual Void CopyFrom(HTTPFormBase fields) { }
	// RVA: 0x661b0a8 VA: 0x7598c330a8
	public virtual Void PrepareRequest(HTTPRequest request) { }
	// RVA: 0x661b0e8 VA: 0x7598c330e8
	public virtual Byte[] GetData() { }
	// RVA: 0x661b128 VA: 0x7598c33128
	public Void .ctor() { }
}
```