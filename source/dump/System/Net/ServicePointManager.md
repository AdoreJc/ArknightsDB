# ServicePointManager

**Namespace:** `System.Net`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class ServicePointManager
{
	private static ConcurrentDictionary`2 servicePoints; // 0x0
	private static ICertificatePolicy policy; // 0x8
	private static Int32 defaultConnectionLimit; // 0x10
	private static Int32 maxServicePointIdleTime; // 0x14
	private static Int32 maxServicePoints; // 0x18
	private static Int32 dnsRefreshTimeout; // 0x1c
	private static Boolean _checkCRL; // 0x20
	private static SecurityProtocolType _securityProtocol; // 0x24
	private static Boolean expectContinue; // 0x28
	private static Boolean useNagle; // 0x29
	private static ServerCertValidationCallback server_cert_cb; // 0x30
	private static Boolean tcp_keepalive; // 0x38
	private static Int32 tcp_keepalive_time; // 0x3c
	private static Int32 tcp_keepalive_interval; // 0x40

	public static Boolean CheckCertificateRevocationList { get; }
	public static Int32 DnsRefreshTimeout { get; }
	public static SecurityProtocolType SecurityProtocol { get; }
	internal static ServerCertValidationCallback ServerCertValidationCallback { get; }
	public static RemoteCertificateValidationCallback ServerCertificateValidationCallback { get; set; }

	// RVA: 0x633178c VA: 0x759894978c
	private static Void .cctor() { }
	// RVA: 0x633184c VA: 0x759894984c
	internal static ICertificatePolicy GetLegacyCertificatePolicy() { }
	// RVA: 0x63318a4 VA: 0x75989498a4
	public static Boolean get_CheckCertificateRevocationList() { }
	// RVA: 0x63318fc VA: 0x75989498fc
	public static Int32 get_DnsRefreshTimeout() { }
	// RVA: 0x6331954 VA: 0x7598949954
	public static SecurityProtocolType get_SecurityProtocol() { }
	// RVA: 0x63319ac VA: 0x75989499ac
	internal static ServerCertValidationCallback get_ServerCertValidationCallback() { }
	// RVA: 0x6331a04 VA: 0x7598949a04
	public static RemoteCertificateValidationCallback get_ServerCertificateValidationCallback() { }
	// RVA: 0x6331a8c VA: 0x7598949a8c
	public static Void set_ServerCertificateValidationCallback(RemoteCertificateValidationCallback value) { }
	// RVA: 0x63285fc VA: 0x75989405fc
	public static ServicePoint FindServicePoint(Uri address, IWebProxy proxy) { }
	// RVA: 0x6331ba0 VA: 0x7598949ba0
	internal static Void RemoveServicePoint(ServicePoint sp) { }
}
```