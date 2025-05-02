# WTauNafMultiplier

**Namespace:** `Org.BouncyCastle.Math.EC.Multiplier`


## Methods

- `AbstractF2mPoint MultiplyWTnaf(AbstractF2mPoint, ZTauElement, PreCompInfo, SByte, SByte)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Multiplier
public class WTauNafMultiplier : AbstractECMultiplier
{
	internal static readonly String PRECOMP_NAME; // 0x0


	// RVA: 0x647b8f8 VA: 0x7598a938f8
	protected override ECPoint MultiplyPositive(ECPoint point, BigInteger k) { }
	// RVA: 0x647bb40 VA: 0x7598a93b40
	private AbstractF2mPoint MultiplyWTnaf(AbstractF2mPoint p, ZTauElement lambda, PreCompInfo preCompInfo, SByte a, SByte mu) { }
	// RVA: 0x647bc94 VA: 0x7598a93c94
	private static AbstractF2mPoint MultiplyFromWTnaf(AbstractF2mPoint p, SByte[] u, PreCompInfo preCompInfo) { }
	// RVA: 0x647c14c VA: 0x7598a9414c
	public Void .ctor() { }
	// RVA: 0x647c154 VA: 0x7598a94154
	private static Void .cctor() { }
}
```