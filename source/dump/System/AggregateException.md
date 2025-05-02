# AggregateException

**Namespace:** `System`


## Methods

- `AggregateException Flatten()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class AggregateException : Exception
{
	private ReadOnlyCollection`1 m_innerExceptions; // 0x90

	public ReadOnlyCollection`1 InnerExceptions { get; }
	public override String Message { get; }

	// RVA: 0x6021318 VA: 0x7598639318
	public Void .ctor() { }
	// RVA: 0x6021434 VA: 0x7598639434
	public Void .ctor(IEnumerable`1 innerExceptions) { }
	// RVA: 0x6021550 VA: 0x7598639550
	public Void .ctor(Exception[] innerExceptions) { }
	// RVA: 0x602148c VA: 0x759863948c
	public Void .ctor(String message, IEnumerable`1 innerExceptions) { }
	// RVA: 0x60215a8 VA: 0x75986395a8
	public Void .ctor(String message, Exception[] innerExceptions) { }
	// RVA: 0x60215ac VA: 0x75986395ac
	private Void .ctor(String message, IList`1 innerExceptions) { }
	// RVA: 0x60219b4 VA: 0x75986399b4
	internal Void .ctor(IEnumerable`1 innerExceptionInfos) { }
	// RVA: 0x6021a0c VA: 0x7598639a0c
	internal Void .ctor(String message, IEnumerable`1 innerExceptionInfos) { }
	// RVA: 0x6021ad0 VA: 0x7598639ad0
	private Void .ctor(String message, IList`1 innerExceptionInfos) { }
	// RVA: 0x6021f1c VA: 0x7598639f1c
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x602210c VA: 0x759863a10c
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x6022258 VA: 0x759863a258
	public ReadOnlyCollection`1 get_InnerExceptions() { }
	// RVA: 0x6022260 VA: 0x759863a260
	public AggregateException Flatten() { }
	// RVA: 0x602262c VA: 0x759863a62c
	public override String get_Message() { }
	// RVA: 0x60227b8 VA: 0x759863a7b8
	public override String ToString() { }
}
```