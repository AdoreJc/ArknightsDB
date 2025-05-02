# AirisdkEvent

**Namespace:** `Torappu.AiriSDK.Fake`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AiriSDK.Fake
public class AirisdkEvent
{
	private static AirisdkEvent m_inst; // 0x0
	public Action`1 SystemShareEvent; // 0x10
	public Action`1 BuyEvent; // 0x18
	public Action`1 BirthSetEvent; // 0x20
	public Action`1 VerificationCodeEvent; // 0x28
	public Action`1 MigrationCodeEvent; // 0x30
	public Action`1 UnLinkEvent; // 0x38
	public Action`1 LinkEvent; // 0x40
	public Action`1 LoginEvent; // 0x48
	public Action`1 InitEvent; // 0x50
	public Action`1 ClearAccountInfoEvent; // 0x58
	public Action`1 DeleteAccountEvent; // 0x60
	public Action`1 GetAgreementEvent; // 0x68
	public Action`1 GetShopAgreementEvent; // 0x70
	public Action`1 GetUnderAgreementEvent; // 0x78
	public Action`1 RebornAccountEvent; // 0x80
	public Action`1 QuerySkuDetailsEvent; // 0x88

	public static AirisdkEvent Instance { get; }

	// RVA: 0x3ef731c VA: 0x759650f31c
	public static AirisdkEvent get_Instance() { }
	// RVA: 0x3ef73ac VA: 0x759650f3ac
	public Void .ctor() { }
}
```