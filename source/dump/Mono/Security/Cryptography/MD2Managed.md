# MD2Managed

**Namespace:** `Mono.Security.Cryptography`


## Fields

- `Int32 count`


## Methods

- `Void MD2Transform(Byte[], Byte[], Byte[], Int32)`


## Dump
```C#
// Dll : Mono.Security.dll
// Namespace : Mono.Security.Cryptography
public class MD2Managed : MD2
{
	private Byte[] state; // 0x28
	private Byte[] checksum; // 0x30
	private Byte[] buffer; // 0x38
	private Int32 count; // 0x40
	private Byte[] x; // 0x48
	private static readonly Byte[] PI_SUBST; // 0x0


	// RVA: 0x5eea488 VA: 0x7598502488
	private Byte[] Padding(Int32 nLength) { }
	// RVA: 0x5eea3b4 VA: 0x75985023b4
	public Void .ctor() { }
	// RVA: 0x5eea524 VA: 0x7598502524
	public override Void Initialize() { }
	// RVA: 0x5eea584 VA: 0x7598502584
	protected override Void HashCore(Byte[] array, Int32 ibStart, Int32 cbSize) { }
	// RVA: 0x5eea8b8 VA: 0x75985028b8
	protected override Byte[] HashFinal() { }
	// RVA: 0x5eea660 VA: 0x7598502660
	private Void MD2Transform(Byte[] state, Byte[] checksum, Byte[] block, Int32 index) { }
	// RVA: 0x5eea9a8 VA: 0x75985029a8
	private static Void .cctor() { }
}
```