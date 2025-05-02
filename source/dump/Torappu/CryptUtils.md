# CryptUtils

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CryptUtils
{


	// RVA: 0x34f92d0 VA: 0x7595b112d0
	public static String CalculateMD5FromString(String source) { }
	// RVA: 0x34f944c VA: 0x7595b1144c
	public static String CalculateShortMD5FromString(String source, Int32 cutLength) { }
	// RVA: 0x34f9474 VA: 0x7595b11474
	public static String CalculateMD5FromFile(String file) { }
	// RVA: 0x34f9938 VA: 0x7595b11938
	public static String CalculateMD5FromFileOrEmpty(String file) { }
	// RVA: 0x34f9a6c VA: 0x7595b11a6c
	public static String[] GenerateKeysRSA() { }
	// RVA: 0x34f9cd0 VA: 0x7595b11cd0
	public static String SignWithMD5RSA(String content, String key) { }
	// RVA: 0x34f9d9c VA: 0x7595b11d9c
	public static Byte[] SignWithMD5RSA(Byte[] contentBytes, String key) { }
	// RVA: 0x34fa108 VA: 0x7595b12108
	public static Boolean VerifySignMD5RSA(String content, String sign, String publicKey) { }
	// RVA: 0x34fa1c8 VA: 0x7595b121c8
	public static Boolean VerifySignMD5RSA(Byte[] contentBytes, Byte[] sign, String publicKey) { }
	// RVA: 0x34fa544 VA: 0x7595b12544
	public static String EncryptRSA(Byte[] plainText, String key) { }
	// RVA: 0x34fa778 VA: 0x7595b12778
	public static Byte[] DecryptRSA(String cipher, String key) { }
	// RVA: 0x34fa97c VA: 0x7595b1297c
	public Void .ctor() { }
}
```