# SoapServices

**Namespace:** `System.Runtime.Remoting`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
public class SoapServices
{
	private static Hashtable _xmlTypes; // 0x0
	private static Hashtable _xmlElements; // 0x8
	private static Hashtable _soapActions; // 0x10
	private static Hashtable _soapActionsMethods; // 0x18
	private static Hashtable _typeInfos; // 0x20

	public static String XmlNsForClrTypeWithAssembly { get; }
	public static String XmlNsForClrTypeWithNs { get; }
	public static String XmlNsForClrTypeWithNsAndAssembly { get; }

	// RVA: 0x5f8b7b4 VA: 0x75985a37b4
	public static String get_XmlNsForClrTypeWithAssembly() { }
	// RVA: 0x5f8b7f4 VA: 0x75985a37f4
	public static String get_XmlNsForClrTypeWithNs() { }
	// RVA: 0x5f8b834 VA: 0x75985a3834
	public static String get_XmlNsForClrTypeWithNsAndAssembly() { }
	// RVA: 0x5f8b874 VA: 0x75985a3874
	public static String CodeXmlNamespaceForClrTypeNamespace(String typeNamespace, String assemblyName) { }
	// RVA: 0x5f8baf0 VA: 0x75985a3af0
	private static String GetNameKey(String name, String namspace) { }
	// RVA: 0x5f8bb58 VA: 0x75985a3b58
	private static String GetAssemblyName(MethodBase mb) { }
	// RVA: 0x5f8bc8c VA: 0x75985a3c8c
	public static Boolean GetXmlElementForInteropType(Type type, out String xmlElement, out String xmlNamespace) { }
	// RVA: 0x5f8bd90 VA: 0x75985a3d90
	public static String GetXmlNamespaceForMethodCall(MethodBase mb) { }
	// RVA: 0x5f8be24 VA: 0x75985a3e24
	public static String GetXmlNamespaceForMethodResponse(MethodBase mb) { }
	// RVA: 0x5f8beb8 VA: 0x75985a3eb8
	public static Boolean GetXmlTypeForInteropType(Type type, out String xmlType, out String xmlTypeNamespace) { }
	// RVA: 0x5f865a4 VA: 0x759859e5a4
	public static Void PreLoad(Assembly assembly) { }
	// RVA: 0x5f86098 VA: 0x759859e098
	public static Void PreLoad(Type type) { }
	// RVA: 0x5f85d78 VA: 0x759859dd78
	public static Void RegisterInteropXmlElement(String xmlElement, String xmlNamespace, Type type) { }
	// RVA: 0x5f85f08 VA: 0x759859df08
	public static Void RegisterInteropXmlType(String xmlType, String xmlTypeNamespace, Type type) { }
	// RVA: 0x5f8ba0c VA: 0x75985a3a0c
	private static String EncodeNs(String ns) { }
	// RVA: 0x5f8bfb4 VA: 0x75985a3fb4
	private static Void .cctor() { }
}
```