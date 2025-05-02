# KeccakDigest

**Namespace:** `Org.BouncyCastle.Crypto.Digests`


## Fields

- `Int32 rate`

- `Int32 bitsInQueue`

- `Int32 fixedOutputLength`

- `Boolean squeezing`

- `Int32 bitsAvailableForSqueezing`


## Methods

- `Void ClearDataQueueSection(Int32, Int32)`

- `Void CopyIn(KeccakDigest)`

- `Void Init(Int32)`

- `Void InitSponge(Int32, Int32)`

- `Void AbsorbQueue()`

- `Void PadAndSwitchToSqueezingPhase()`

- `Void KeccakPermutation(Byte[])`

- `Void KeccakPermutationAfterXor(Byte[], Byte[], Int32)`

- `Void KeccakPermutationOnWords(UInt64[])`

- `Void Theta(UInt64[])`

- `Void Rho(UInt64[])`

- `Void Pi(UInt64[])`

- `Void Chi(UInt64[])`

- `Void KeccakAbsorb(Byte[], Byte[], Int32)`

- `Void KeccakExtract1024bits(Byte[], Byte[])`

- `Void KeccakExtract(Byte[], Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Digests
public class KeccakDigest : IDigest, IMemoable
{
	private static readonly UInt64[] KeccakRoundConstants; // 0x0
	private static readonly Int32[] KeccakRhoOffsets; // 0x8
	protected Byte[] state; // 0x10
	protected Byte[] dataQueue; // 0x18
	protected Int32 rate; // 0x20
	protected Int32 bitsInQueue; // 0x24
	protected Int32 fixedOutputLength; // 0x28
	protected Boolean squeezing; // 0x2c
	protected Int32 bitsAvailableForSqueezing; // 0x30
	protected Byte[] chunk; // 0x38
	protected Byte[] oneByte; // 0x40
	private UInt64[] C; // 0x48
	private UInt64[] tempA; // 0x50
	private UInt64[] chiC; // 0x58

	public virtual String AlgorithmName { get; }

	// RVA: 0x657a360 VA: 0x7598b92360
	private static UInt64[] KeccakInitializeRoundConstants() { }
	// RVA: 0x657a430 VA: 0x7598b92430
	private static Int32[] KeccakInitializeRhoOffsets() { }
	// RVA: 0x657a4f8 VA: 0x7598b924f8
	private Void ClearDataQueueSection(Int32 off, Int32 len) { }
	// RVA: 0x657a538 VA: 0x7598b92538
	public Void .ctor() { }
	// RVA: 0x657a540 VA: 0x7598b92540
	public Void .ctor(Int32 bitLength) { }
	// RVA: 0x657a728 VA: 0x7598b92728
	public Void .ctor(KeccakDigest source) { }
	// RVA: 0x657a828 VA: 0x7598b92828
	private Void CopyIn(KeccakDigest source) { }
	// RVA: 0x657a8e0 VA: 0x7598b928e0
	public virtual String get_AlgorithmName() { }
	// RVA: 0x657a93c VA: 0x7598b9293c
	public virtual Int32 GetDigestSize() { }
	// RVA: 0x657a954 VA: 0x7598b92954
	public virtual Void Update(Byte input) { }
	// RVA: 0x657a994 VA: 0x7598b92994
	public virtual Void BlockUpdate(Byte[] input, Int32 inOff, Int32 len) { }
	// RVA: 0x657a9a8 VA: 0x7598b929a8
	public virtual Int32 DoFinal(Byte[] output, Int32 outOff) { }
	// RVA: 0x657a9f0 VA: 0x7598b929f0
	protected virtual Int32 DoFinal(Byte[] output, Int32 outOff, Byte partialByte, Int32 partialBits) { }
	// RVA: 0x657aa9c VA: 0x7598b92a9c
	public virtual Void Reset() { }
	// RVA: 0x657aaa4 VA: 0x7598b92aa4
	public virtual Int32 GetByteLength() { }
	// RVA: 0x657a640 VA: 0x7598b92640
	private Void Init(Int32 bitLength) { }
	// RVA: 0x657aabc VA: 0x7598b92abc
	private Void InitSponge(Int32 rate, Int32 capacity) { }
	// RVA: 0x657ac10 VA: 0x7598b92c10
	private Void AbsorbQueue() { }
	// RVA: 0x657ac44 VA: 0x7598b92c44
	protected virtual Void Absorb(Byte[] data, Int32 off, Int64 databitlen) { }
	// RVA: 0x657aee0 VA: 0x7598b92ee0
	private Void PadAndSwitchToSqueezingPhase() { }
	// RVA: 0x657b100 VA: 0x7598b93100
	protected virtual Void Squeeze(Byte[] output, Int32 offset, Int64 outputLength) { }
	// RVA: 0x657b334 VA: 0x7598b93334
	private static Void FromBytesToWords(UInt64[] stateAsWords, Byte[] state) { }
	// RVA: 0x657b3b8 VA: 0x7598b933b8
	private static Void FromWordsToBytes(Byte[] state, UInt64[] stateAsWords) { }
	// RVA: 0x657b280 VA: 0x7598b93280
	private Void KeccakPermutation(Byte[] state) { }
	// RVA: 0x657b4d8 VA: 0x7598b934d8
	private Void KeccakPermutationAfterXor(Byte[] state, Byte[] data, Int32 dataLengthInBytes) { }
	// RVA: 0x657b434 VA: 0x7598b93434
	private Void KeccakPermutationOnWords(UInt64[] state) { }
	// RVA: 0x657b540 VA: 0x7598b93540
	private Void Theta(UInt64[] A) { }
	// RVA: 0x657b664 VA: 0x7598b93664
	private Void Rho(UInt64[] A) { }
	// RVA: 0x657b7a0 VA: 0x7598b937a0
	private Void Pi(UInt64[] A) { }
	// RVA: 0x657b878 VA: 0x7598b93878
	private Void Chi(UInt64[] A) { }
	// RVA: 0x657b994 VA: 0x7598b93994
	private static Void Iota(UInt64[] A, Int32 indexRound) { }
	// RVA: 0x657ac40 VA: 0x7598b92c40
	private Void KeccakAbsorb(Byte[] byteState, Byte[] data, Int32 dataInBytes) { }
	// RVA: 0x657b0d0 VA: 0x7598b930d0
	private Void KeccakExtract1024bits(Byte[] byteState, Byte[] data) { }
	// RVA: 0x657b0e8 VA: 0x7598b930e8
	private Void KeccakExtract(Byte[] byteState, Byte[] data, Int32 laneCount) { }
	// RVA: 0x657ba34 VA: 0x7598b93a34
	public virtual IMemoable Copy() { }
	// RVA: 0x657ba94 VA: 0x7598b93a94
	public virtual Void Reset(IMemoable other) { }
	// RVA: 0x657bb18 VA: 0x7598b93b18
	private static Void .cctor() { }
}
```