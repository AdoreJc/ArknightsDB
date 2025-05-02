# DHBasicAgreement

**Namespace:** `Org.BouncyCastle.Crypto.Agreement`


## Fields

- `DHPrivateKeyParameters key`

- `DHParameters dhParams`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Agreement
public class DHBasicAgreement : IBasicAgreement
{
	private DHPrivateKeyParameters key; // 0x10
	private DHParameters dhParams; // 0x18


	// RVA: 0x658c86c VA: 0x7598ba486c
	public virtual Void Init(ICipherParameters parameters) { }
	// RVA: 0x658c9c8 VA: 0x7598ba49c8
	public virtual Int32 GetFieldSize() { }
	// RVA: 0x658ca0c VA: 0x7598ba4a0c
	public virtual BigInteger CalculateAgreement(ICipherParameters pubKey) { }
	// RVA: 0x658cb64 VA: 0x7598ba4b64
	public Void .ctor() { }
}
```