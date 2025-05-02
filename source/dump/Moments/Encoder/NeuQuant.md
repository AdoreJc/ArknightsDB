# NeuQuant

**Namespace:** `Moments.Encoder`


## Fields

- `Int32 alphadec`

- `Int32 lengthcount`

- `Int32 samplefac`


## Methods

- `Void Inxbuild()`

- `Void Learn()`

- `Int32 Map(Int32, Int32, Int32)`

- `Void Unbiasnet()`

- `Void Alterneigh(Int32, Int32, Int32, Int32, Int32)`

- `Void Altersingle(Int32, Int32, Int32, Int32, Int32)`

- `Int32 Contest(Int32, Int32, Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Moments.Encoder
public class NeuQuant
{
	protected static readonly Int32 netsize; // 0x0
	protected static readonly Int32 prime1; // 0x4
	protected static readonly Int32 prime2; // 0x8
	protected static readonly Int32 prime3; // 0xc
	protected static readonly Int32 prime4; // 0x10
	protected static readonly Int32 minpicturebytes; // 0x14
	protected static readonly Int32 maxnetpos; // 0x18
	protected static readonly Int32 netbiasshift; // 0x1c
	protected static readonly Int32 ncycles; // 0x20
	protected static readonly Int32 intbiasshift; // 0x24
	protected static readonly Int32 intbias; // 0x28
	protected static readonly Int32 gammashift; // 0x2c
	protected static readonly Int32 gamma; // 0x30
	protected static readonly Int32 betashift; // 0x34
	protected static readonly Int32 beta; // 0x38
	protected static readonly Int32 betagamma; // 0x3c
	protected static readonly Int32 initrad; // 0x40
	protected static readonly Int32 radiusbiasshift; // 0x44
	protected static readonly Int32 radiusbias; // 0x48
	protected static readonly Int32 initradius; // 0x4c
	protected static readonly Int32 radiusdec; // 0x50
	protected static readonly Int32 alphabiasshift; // 0x54
	protected static readonly Int32 initalpha; // 0x58
	protected Int32 alphadec; // 0x10
	protected static readonly Int32 radbiasshift; // 0x5c
	protected static readonly Int32 radbias; // 0x60
	protected static readonly Int32 alpharadbshift; // 0x64
	protected static readonly Int32 alpharadbias; // 0x68
	protected Byte[] thepicture; // 0x18
	protected Int32 lengthcount; // 0x20
	protected Int32 samplefac; // 0x24
	protected Int32[][] network; // 0x28
	protected Int32[] netindex; // 0x30
	protected Int32[] bias; // 0x38
	protected Int32[] freq; // 0x40
	protected Int32[] radpower; // 0x48


	// RVA: 0x66c0c74 VA: 0x7598cd8c74
	public Void .ctor(Byte[] thepic, Int32 len, Int32 sample) { }
	// RVA: 0x66c1b00 VA: 0x7598cd9b00
	public Byte[] ColorMap() { }
	// RVA: 0x66c1d70 VA: 0x7598cd9d70
	public Void Inxbuild() { }
	// RVA: 0x66c2044 VA: 0x7598cda044
	public Void Learn() { }
	// RVA: 0x66c0f44 VA: 0x7598cd8f44
	public Int32 Map(Int32 b, Int32 g, Int32 r) { }
	// RVA: 0x66c0f1c VA: 0x7598cd8f1c
	public Byte[] Process() { }
	// RVA: 0x66c2b5c VA: 0x7598cdab5c
	public Void Unbiasnet() { }
	// RVA: 0x66c28c4 VA: 0x7598cda8c4
	protected Void Alterneigh(Int32 rad, Int32 i, Int32 b, Int32 g, Int32 r) { }
	// RVA: 0x66c27b0 VA: 0x7598cda7b0
	protected Void Altersingle(Int32 alpha, Int32 i, Int32 b, Int32 g, Int32 r) { }
	// RVA: 0x66c2518 VA: 0x7598cda518
	protected Int32 Contest(Int32 b, Int32 g, Int32 r) { }
	// RVA: 0x66c2c94 VA: 0x7598cdac94
	private static Void .cctor() { }
}
```