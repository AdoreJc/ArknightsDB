# Salsa20Engine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Int32 rounds`

- `Int32 index`

- `Boolean initialised`

- `UInt32 cW0`

- `UInt32 cW1`

- `UInt32 cW2`


## Methods

- `Void ResetLimitCounter()`

- `Boolean LimitExceeded()`

- `Boolean LimitExceeded(UInt32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class Salsa20Engine : IStreamCipher
{
	public static readonly Int32 DEFAULT_ROUNDS; // 0x0
	private const Int32 StateSize; // 0x0
	private static readonly UInt32[] TAU_SIGMA; // 0x8
	protected static readonly Byte[] sigma; // 0x10
	protected static readonly Byte[] tau; // 0x18
	protected Int32 rounds; // 0x10
	private Int32 index; // 0x14
	internal UInt32[] engineState; // 0x18
	internal UInt32[] x; // 0x20
	private Byte[] keyStream; // 0x28
	private Boolean initialised; // 0x30
	private UInt32 cW0; // 0x34
	private UInt32 cW1; // 0x38
	private UInt32 cW2; // 0x3c

	protected virtual Int32 NonceSize { get; }
	public virtual String AlgorithmName { get; }

	// RVA: 0x6556f14 VA: 0x7598b6ef14
	internal Void PackTauOrSigma(Int32 keyLength, UInt32[] state, Int32 stateOffset) { }
	// RVA: 0x6557048 VA: 0x7598b6f048
	public Void .ctor() { }
	// RVA: 0x65570a8 VA: 0x7598b6f0a8
	public Void .ctor(Int32 rounds) { }
	// RVA: 0x65571c4 VA: 0x7598b6f1c4
	public virtual Void Init(Boolean forEncryption, ICipherParameters parameters) { }
	// RVA: 0x65574d8 VA: 0x7598b6f4d8
	protected virtual Int32 get_NonceSize() { }
	// RVA: 0x65574e0 VA: 0x7598b6f4e0
	public virtual String get_AlgorithmName() { }
	// RVA: 0x65575ac VA: 0x7598b6f5ac
	public virtual Byte ReturnByte(Byte input) { }
	// RVA: 0x65576ec VA: 0x7598b6f6ec
	protected virtual Void AdvanceCounter() { }
	// RVA: 0x6557738 VA: 0x7598b6f738
	public virtual Void ProcessBytes(Byte[] inBytes, Int32 inOff, Int32 len, Byte[] outBytes, Int32 outOff) { }
	// RVA: 0x65579e8 VA: 0x7598b6f9e8
	public virtual Void Reset() { }
	// RVA: 0x6557a10 VA: 0x7598b6fa10
	protected virtual Void ResetCounter() { }
	// RVA: 0x6557a3c VA: 0x7598b6fa3c
	protected virtual Void SetKey(Byte[] keyBytes, Byte[] ivBytes) { }
	// RVA: 0x6557c40 VA: 0x7598b6fc40
	protected virtual Void GenerateKeyStream(Byte[] output) { }
	// RVA: 0x6557cc4 VA: 0x7598b6fcc4
	internal static Void SalsaCore(Int32 rounds, UInt32[] input, UInt32[] x) { }
	// RVA: 0x6558150 VA: 0x7598b70150
	internal static UInt32 R(UInt32 x, Int32 y) { }
	// RVA: 0x6557a04 VA: 0x7598b6fa04
	private Void ResetLimitCounter() { }
	// RVA: 0x65576b0 VA: 0x7598b6f6b0
	private Boolean LimitExceeded() { }
	// RVA: 0x65579ac VA: 0x7598b6f9ac
	private Boolean LimitExceeded(UInt32 len) { }
	// RVA: 0x655815c VA: 0x7598b7015c
	private static Void .cctor() { }
}
```