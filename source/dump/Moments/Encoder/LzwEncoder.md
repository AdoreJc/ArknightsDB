# LzwEncoder

**Namespace:** `Moments.Encoder`


## Fields

- `Int32 initCodeSize`

- `Int32 curPixel`

- `Int32 n_bits`

- `Int32 maxbits`

- `Int32 maxcode`

- `Int32 maxmaxcode`

- `Int32 hsize`

- `Int32 free_ent`

- `Boolean clear_flg`

- `Int32 g_init_bits`

- `Int32 ClearCode`

- `Int32 EOFCode`

- `Int32 cur_accum`

- `Int32 cur_bits`

- `Int32 a_count`


## Methods

- `Void Add(Byte, Stream)`

- `Void ClearTable(Stream)`

- `Void ResetCodeTable(Int32)`

- `Void Compress(Int32, Stream)`

- `Void Encode(Stream)`

- `Void Flush(Stream)`

- `Int32 MaxCode(Int32)`

- `Int32 NextPixel()`

- `Void Output(Int32, Stream)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Moments.Encoder
public class LzwEncoder
{
	private static readonly Int32 EOF; // 0x0
	private Byte[] pixAry; // 0x10
	private Int32 initCodeSize; // 0x18
	private Int32 curPixel; // 0x1c
	private static readonly Int32 BITS; // 0x4
	private static readonly Int32 HSIZE; // 0x8
	private Int32 n_bits; // 0x20
	private Int32 maxbits; // 0x24
	private Int32 maxcode; // 0x28
	private Int32 maxmaxcode; // 0x2c
	private Int32[] htab; // 0x30
	private Int32[] codetab; // 0x38
	private Int32 hsize; // 0x40
	private Int32 free_ent; // 0x44
	private Boolean clear_flg; // 0x48
	private Int32 g_init_bits; // 0x4c
	private Int32 ClearCode; // 0x50
	private Int32 EOFCode; // 0x54
	private Int32 cur_accum; // 0x58
	private Int32 cur_bits; // 0x5c
	private Int32[] masks; // 0x60
	private Int32 a_count; // 0x68
	private Byte[] accum; // 0x70


	// RVA: 0x66c1230 VA: 0x7598cd9230
	public Void .ctor(Int32 width, Int32 height, Byte[] pixels, Int32 color_depth) { }
	// RVA: 0x66c149c VA: 0x7598cd949c
	private Void Add(Byte c, Stream outs) { }
	// RVA: 0x66c15a0 VA: 0x7598cd95a0
	private Void ClearTable(Stream outs) { }
	// RVA: 0x66c15e4 VA: 0x7598cd95e4
	private Void ResetCodeTable(Int32 hsize) { }
	// RVA: 0x66c177c VA: 0x7598cd977c
	private Void Compress(Int32 init_bits, Stream outs) { }
	// RVA: 0x66c13e4 VA: 0x7598cd93e4
	public Void Encode(Stream os) { }
	// RVA: 0x66c14f0 VA: 0x7598cd94f0
	private Void Flush(Stream outs) { }
	// RVA: 0x66c1a00 VA: 0x7598cd9a00
	private Int32 MaxCode(Int32 n_bits) { }
	// RVA: 0x66c1a10 VA: 0x7598cd9a10
	private Int32 NextPixel() { }
	// RVA: 0x66c1634 VA: 0x7598cd9634
	private Void Output(Int32 code, Stream outs) { }
	// RVA: 0x66c1aa8 VA: 0x7598cd9aa8
	private static Void .cctor() { }
}
```