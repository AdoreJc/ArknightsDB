# OperationCanceledException

**Namespace:** `System`


## Fields

- `CancellationToken _cancellationToken`


## Properties

- `CancellationToken CancellationToken`


## Methods

- `CancellationToken get_CancellationToken()`

- `Void set_CancellationToken(CancellationToken)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class OperationCanceledException : SystemException
{
	private CancellationToken _cancellationToken; // 0x90

	public CancellationToken CancellationToken { get; set; }

	// RVA: 0x60c0404 VA: 0x75986d8404
	public CancellationToken get_CancellationToken() { }
	// RVA: 0x60c040c VA: 0x75986d840c
	private Void set_CancellationToken(CancellationToken value) { }
	// RVA: 0x60c0418 VA: 0x75986d8418
	public Void .ctor() { }
	// RVA: 0x60c04e8 VA: 0x75986d84e8
	public Void .ctor(String message) { }
	// RVA: 0x60c0508 VA: 0x75986d8508
	public Void .ctor(String message, CancellationToken token) { }
	// RVA: 0x60c0540 VA: 0x75986d8540
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
}
```