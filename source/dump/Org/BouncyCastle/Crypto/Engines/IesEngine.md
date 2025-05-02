# IesEngine

**Namespace:** `Org.BouncyCastle.Crypto.Engines`


## Fields

- `Boolean forEncryption`

- `ICipherParameters privParam`

- `ICipherParameters pubParam`

- `IesParameters param`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Engines
public class IesEngine
{
	private readonly IBasicAgreement agree; // 0x10
	private readonly IDerivationFunction kdf; // 0x18
	private readonly IMac mac; // 0x20
	private readonly BufferedBlockCipher cipher; // 0x28
	private readonly Byte[] macBuf; // 0x30
	private Boolean forEncryption; // 0x38
	private ICipherParameters privParam; // 0x40
	private ICipherParameters pubParam; // 0x48
	private IesParameters param; // 0x50


	// RVA: 0x654c5b4 VA: 0x7598b645b4
	public Void .ctor(IBasicAgreement agree, IDerivationFunction kdf, IMac mac) { }
	// RVA: 0x654c6d8 VA: 0x7598b646d8
	public Void .ctor(IBasicAgreement agree, IDerivationFunction kdf, IMac mac, BufferedBlockCipher cipher) { }
	// RVA: 0x654c818 VA: 0x7598b64818
	public virtual Void Init(Boolean forEncryption, ICipherParameters privParameters, ICipherParameters pubParameters, ICipherParameters iesParameters) { }
	// RVA: 0x654c904 VA: 0x7598b64904
	private Byte[] DecryptBlock(Byte[] in_enc, Int32 inOff, Int32 inLen, Byte[] z) { }
	// RVA: 0x654d0e0 VA: 0x7598b650e0
	private Byte[] EncryptBlock(Byte[] input, Int32 inOff, Int32 inLen, Byte[] z) { }
	// RVA: 0x654cf88 VA: 0x7598b64f88
	private Byte[] GenerateKdfBytes(KdfParameters kParam, Int32 length) { }
	// RVA: 0x654d6cc VA: 0x7598b656cc
	public virtual Byte[] ProcessBlock(Byte[] input, Int32 inOff, Int32 inLen) { }
}
```