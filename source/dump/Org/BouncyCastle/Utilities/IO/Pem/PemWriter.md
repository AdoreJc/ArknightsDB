# PemWriter

**Namespace:** `Org.BouncyCastle.Utilities.IO.Pem`


## Properties

- `TextWriter Writer`


## Methods

- `TextWriter get_Writer()`

- `Int32 GetOutputSize(PemObject)`

- `Void WriteObject(PemObjectGenerator)`

- `Void WriteEncoded(Byte[])`

- `Void WritePreEncapsulationBoundary(String)`

- `Void WritePostEncapsulationBoundary(String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Utilities.IO.Pem
public class PemWriter
{
	private const Int32 LineLength; // 0x0
	private readonly TextWriter writer; // 0x10
	private readonly Int32 nlLength; // 0x18
	private Char[] buf; // 0x20

	public TextWriter Writer { get; }

	// RVA: 0x66f81cc VA: 0x7598d101cc
	public Void .ctor(TextWriter writer) { }
	// RVA: 0x66f82e0 VA: 0x7598d102e0
	public TextWriter get_Writer() { }
	// RVA: 0x66f82e8 VA: 0x7598d102e8
	public Int32 GetOutputSize(PemObject obj) { }
	// RVA: 0x66f87c0 VA: 0x7598d107c0
	public Void WriteObject(PemObjectGenerator objGen) { }
	// RVA: 0x66f8da0 VA: 0x7598d10da0
	private Void WriteEncoded(Byte[] bytes) { }
	// RVA: 0x66f8d0c VA: 0x7598d10d0c
	private Void WritePreEncapsulationBoundary(String type) { }
	// RVA: 0x66f8e7c VA: 0x7598d10e7c
	private Void WritePostEncapsulationBoundary(String type) { }
}
```