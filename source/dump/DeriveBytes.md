# DeriveBytes

**Namespace:** ` `


## Fields

- `String _hashName`

- `Int32 _iterations`


## Properties

- `String HashName`

- `Int32 IterationCount`


## Methods

- `Void set_HashName(String)`

- `Void set_IterationCount(Int32)`

- `Void set_Password(Byte[])`

- `Void set_Salt(Byte[])`

- `Void Adjust(Byte[], Int32, Byte[])`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : 
public class DeriveBytes
{
	private static Byte[] keyDiversifier; // 0x0
	private static Byte[] ivDiversifier; // 0x8
	private static Byte[] macDiversifier; // 0x10
	private String _hashName; // 0x10
	private Int32 _iterations; // 0x18
	private Byte[] _password; // 0x20
	private Byte[] _salt; // 0x28

	public String HashName { set; }
	public Int32 IterationCount { set; }
	public Byte[] Password { set; }
	public Byte[] Salt { set; }

	// RVA: 0x5ed91e8 VA: 0x75984f11e8
	public Void .ctor() { }
	// RVA: 0x5eddd0c VA: 0x75984f5d0c
	public Void set_HashName(String value) { }
	// RVA: 0x5eddd14 VA: 0x75984f5d14
	public Void set_IterationCount(Int32 value) { }
	// RVA: 0x5ed91f0 VA: 0x75984f11f0
	public Void set_Password(Byte[] value) { }
	// RVA: 0x5ed92b4 VA: 0x75984f12b4
	public Void set_Salt(Byte[] value) { }
	// RVA: 0x5eddd1c VA: 0x75984f5d1c
	private Void Adjust(Byte[] a, Int32 aOff, Byte[] b) { }
	// RVA: 0x5edddf8 VA: 0x75984f5df8
	private Byte[] Derive(Byte[] diversifier, Int32 n) { }
	// RVA: 0x5ed9370 VA: 0x75984f1370
	public Byte[] DeriveKey(Int32 size) { }
	// RVA: 0x5ed93e0 VA: 0x75984f13e0
	public Byte[] DeriveIV(Int32 size) { }
	// RVA: 0x5edad1c VA: 0x75984f2d1c
	public Byte[] DeriveMAC(Int32 size) { }
	// RVA: 0x5ede228 VA: 0x75984f6228
	private static Void .cctor() { }
}
```