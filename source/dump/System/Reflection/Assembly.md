# Assembly

**Namespace:** `System.Reflection`


## Properties

- `Boolean IsFullyTrusted`


## Methods

- `AssemblyNameFlags GetFlags()`

- `Boolean get_IsFullyTrusted()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public class Assembly : ICustomAttributeProvider, ISerializable, _Assembly
{

	public virtual String CodeBase { get; }
	public virtual String EscapedCodeBase { get; }
	public virtual String FullName { get; }
	internal virtual IntPtr MonoAssembly { get; }
	public virtual String Location { get; }
	public virtual Boolean ReflectionOnly { get; }
	public Boolean IsFullyTrusted { get; }
	public virtual Boolean IsDynamic { get; }

	// RVA: 0x5fee200 VA: 0x7598606200
	public virtual String get_CodeBase() { }
	// RVA: 0x5fee240 VA: 0x7598606240
	public virtual String get_EscapedCodeBase() { }
	// RVA: 0x5fee280 VA: 0x7598606280
	public virtual String get_FullName() { }
	// RVA: 0x5fee2c0 VA: 0x75986062c0
	internal virtual IntPtr get_MonoAssembly() { }
	// RVA: 0x5fee300 VA: 0x7598606300
	public virtual String get_Location() { }
	// RVA: 0x5fee340 VA: 0x7598606340
	public virtual Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5fee380 VA: 0x7598606380
	public virtual Boolean IsDefined(Type attributeType, Boolean inherit) { }
	// RVA: 0x5fee3c0 VA: 0x75986063c0
	public virtual Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x5fee400 VA: 0x7598606400
	public virtual Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x5fee440 VA: 0x7598606440
	public virtual Stream GetManifestResourceStream(String name) { }
	// RVA: 0x5fee480 VA: 0x7598606480
	internal Stream GetManifestResourceStream(Type type, String name, Boolean skipSecurityCheck, ref StackCrawlMark stackMark) { }
	// RVA: 0x5fee608 VA: 0x7598606608
	internal Stream GetManifestResourceStream(String name, ref StackCrawlMark stackMark, Boolean skipSecurityCheck) { }
	// RVA: 0x5fee618 VA: 0x7598606618
	internal String GetSimpleName() { }
	// RVA: 0x5fee644 VA: 0x7598606644
	internal Byte[] GetPublicKey() { }
	// RVA: 0x5fee670 VA: 0x7598606670
	internal Version GetVersion() { }
	// RVA: 0x5fee69c VA: 0x759860669c
	private AssemblyNameFlags GetFlags() { }
	// RVA: 0x5fee6c8 VA: 0x75986066c8
	internal virtual Type[] GetTypes(Boolean exportedOnly) { }
	// RVA: 0x5fee6d0 VA: 0x75986066d0
	public virtual Type[] GetTypes() { }
	// RVA: 0x5fee6e4 VA: 0x75986066e4
	public virtual Type GetType(String name, Boolean throwOnError) { }
	// RVA: 0x5fee6fc VA: 0x75986066fc
	public virtual Type GetType(String name) { }
	// RVA: 0x5fee714 VA: 0x7598606714
	internal Type InternalGetType(Module module, String name, Boolean throwOnError, Boolean ignoreCase) { }
	// RVA: 0x5fee720 VA: 0x7598606720
	internal static Void InternalGetAssemblyName(String assemblyFile, out MonoAssemblyName aname, out String codebase) { }
	// RVA: 0x5fee724 VA: 0x7598606724
	public virtual AssemblyName GetName(Boolean copiedName) { }
	// RVA: 0x5fee764 VA: 0x7598606764
	public virtual AssemblyName GetName() { }
	// RVA: 0x5fee778 VA: 0x7598606778
	public override String ToString() { }
	// RVA: 0x5fee780 VA: 0x7598606780
	public static Assembly GetAssembly(Type type) { }
	// RVA: 0x5fee848 VA: 0x7598606848
	public static Assembly GetEntryAssembly() { }
	// RVA: 0x5fee84c VA: 0x759860684c
	internal RuntimeAssembly InternalGetSatelliteAssembly(String name, CultureInfo culture, Version version, Boolean throwOnFileNotFound, ref StackCrawlMark stackMark) { }
	// RVA: 0x5feed38 VA: 0x7598606d38
	private static Assembly LoadFrom(String assemblyFile, Boolean refOnly, ref StackCrawlMark stackMark) { }
	// RVA: 0x5feed40 VA: 0x7598606d40
	public static Assembly LoadFrom(String assemblyFile, Evidence securityEvidence) { }
	// RVA: 0x5feed60 VA: 0x7598606d60
	public static Assembly Load(String assemblyString) { }
	// RVA: 0x5feed88 VA: 0x7598606d88
	public static Assembly Load(AssemblyName assemblyRef) { }
	// RVA: 0x5feedb0 VA: 0x7598606db0
	public static Assembly ReflectionOnlyLoad(String assemblyString) { }
	// RVA: 0x5feedf8 VA: 0x7598606df8
	private static Assembly load_with_partial_name(String name, Evidence e) { }
	// RVA: 0x5feedfc VA: 0x7598606dfc
	public static Assembly LoadWithPartialName(String partialName, Evidence securityEvidence) { }
	// RVA: 0x5feee04 VA: 0x7598606e04
	internal static Assembly LoadWithPartialName(String partialName, Evidence securityEvidence, Boolean oldBehavior) { }
	// RVA: 0x5feee7c VA: 0x7598606e7c
	public Module[] GetModules() { }
	// RVA: 0x5feee90 VA: 0x7598606e90
	internal virtual Module[] GetModulesInternal() { }
	// RVA: 0x5feeed0 VA: 0x7598606ed0
	public static Assembly GetExecutingAssembly() { }
	// RVA: 0x5feef10 VA: 0x7598606f10
	public static Assembly GetCallingAssembly() { }
	// RVA: 0x5feef14 VA: 0x7598606f14
	public virtual String[] GetManifestResourceNames() { }
	// RVA: 0x5feef54 VA: 0x7598606f54
	public virtual ManifestResourceInfo GetManifestResourceInfo(String resourceName) { }
	// RVA: 0x5feef94 VA: 0x7598606f94
	public virtual Boolean get_ReflectionOnly() { }
	// RVA: 0x5feefd4 VA: 0x7598606fd4
	public override Int32 GetHashCode() { }
	// RVA: 0x5feefdc VA: 0x7598606fdc
	public override Boolean Equals(Object o) { }
	// RVA: 0x5feefe4 VA: 0x7598606fe4
	private static Exception CreateNIE() { }
	// RVA: 0x5fef058 VA: 0x7598607058
	public Boolean get_IsFullyTrusted() { }
	// RVA: 0x5fef060 VA: 0x7598607060
	public virtual Type GetType(String name, Boolean throwOnError, Boolean ignoreCase) { }
	// RVA: 0x5fef084 VA: 0x7598607084
	public virtual Module GetModule(String name) { }
	// RVA: 0x5fef0a8 VA: 0x75986070a8
	public virtual Module[] GetModules(Boolean getResourceModules) { }
	// RVA: 0x5fef0cc VA: 0x75986070cc
	public virtual Boolean get_IsDynamic() { }
	// RVA: 0x5fef0d4 VA: 0x75986070d4
	public static Boolean op_Equality(Assembly left, Assembly right) { }
	// RVA: 0x5feece0 VA: 0x7598606ce0
	public static Boolean op_Inequality(Assembly left, Assembly right) { }
	// RVA: 0x5fef124 VA: 0x7598607124
	public Void .ctor() { }
}
```