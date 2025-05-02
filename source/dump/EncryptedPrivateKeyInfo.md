# EncryptedPrivateKeyInfo

**Namespace:** ` `


## Fields

- `String _algorithm`

- `Int32 _iterations`


## Properties

- `String Algorithm`

- `Int32 IterationCount`


## Methods

- `String get_Algorithm()`

- `Int32 get_IterationCount()`

- `Void Decode(Byte[])`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : 
public class EncryptedPrivateKeyInfo
{
	private String _algorithm; // 0x10
	private Byte[] _salt; // 0x18
	private Int32 _iterations; // 0x20
	private Byte[] _data; // 0x28

	public String Algorithm { get; }
	public Byte[] EncryptedData { get; }
	public Byte[] Salt { get; }
	public Int32 IterationCount { get; }

	// RVA: 0x5eed6fc VA: 0x75985056fc
	public Void .ctor() { }
	// RVA: 0x5eed704 VA: 0x7598505704
	public Void .ctor(Byte[] data) { }
	// RVA: 0x5eeda18 VA: 0x7598505a18
	public String get_Algorithm() { }
	// RVA: 0x5eeda20 VA: 0x7598505a20
	public Byte[] get_EncryptedData() { }
	// RVA: 0x5eeda94 VA: 0x7598505a94
	public Byte[] get_Salt() { }
	// RVA: 0x5eedb54 VA: 0x7598505b54
	public Int32 get_IterationCount() { }
	// RVA: 0x5eed730 VA: 0x7598505730
	private Void Decode(Byte[] data) { }
}
```