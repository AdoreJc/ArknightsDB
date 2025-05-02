# RuntimeAssembly

**Namespace:** `System.Reflection`


## Fields

- `Object _evidence`

- `Object _minimum`

- `Object _optional`

- `Object _refuse`

- `Object _granted`

- `Object _denied`


## Methods

- `String get_location()`

- `Boolean GetManifestResourceInfoInternal(String, ManifestResourceInfo)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
internal class RuntimeAssembly : Assembly
{
	internal IntPtr _mono_assembly; // 0x10
	private Object _evidence; // 0x18
	internal ResolveEventHolder resolve_event_holder; // 0x20
	private Object _minimum; // 0x28
	private Object _optional; // 0x30
	private Object _refuse; // 0x38
	private Object _granted; // 0x40
	private Object _denied; // 0x48
	internal Boolean fromByteArray; // 0x50
	internal String assemblyName; // 0x58

	public override Boolean ReflectionOnly { get; }
	public override String CodeBase { get; }
	public override String EscapedCodeBase { get; }
	public override String FullName { get; }
	internal override IntPtr MonoAssembly { get; }
	public override String Location { get; }

	// RVA: 0x5ff1f00 VA: 0x7598609f00
	protected Void .ctor() { }
	// RVA: 0x5ff1f74 VA: 0x7598609f74
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5ff2000 VA: 0x759860a000
	internal static RuntimeAssembly LoadWithPartialNameInternal(String partialName, Evidence securityEvidence, ref StackCrawlMark stackMark) { }
	// RVA: 0x5ff2088 VA: 0x759860a088
	internal static RuntimeAssembly LoadWithPartialNameInternal(AssemblyName an, Evidence securityEvidence, ref StackCrawlMark stackMark) { }
	// RVA: 0x5ff20b0 VA: 0x759860a0b0
	public override AssemblyName GetName(Boolean copiedName) { }
	// RVA: 0x5ff20b8 VA: 0x759860a0b8
	public override Type GetType(String name, Boolean throwOnError, Boolean ignoreCase) { }
	// RVA: 0x5ff217c VA: 0x759860a17c
	public override Module GetModule(String name) { }
	// RVA: 0x5ff22ac VA: 0x759860a2ac
	public override Module[] GetModules(Boolean getResourceModules) { }
	// RVA: 0x5ff2448 VA: 0x759860a448
	internal static Byte[] GetAotId() { }
	// RVA: 0x5ff24a4 VA: 0x759860a4a4
	private static String get_code_base(Assembly a, Boolean escaped) { }
	// RVA: 0x5ff24ac VA: 0x759860a4ac
	private String get_location() { }
	// RVA: 0x5ff24b0 VA: 0x759860a4b0
	internal static String get_fullname(Assembly a) { }
	// RVA: 0x5ff24a0 VA: 0x759860a4a0
	internal static Boolean GetAotIdInternal(Byte[] aotid) { }
	// RVA: 0x5ff24b4 VA: 0x759860a4b4
	public override Boolean get_ReflectionOnly() { }
	// RVA: 0x5ff24b8 VA: 0x759860a4b8
	internal static String GetCodeBase(Assembly a, Boolean escaped) { }
	// RVA: 0x5ff24c0 VA: 0x759860a4c0
	public override String get_CodeBase() { }
	// RVA: 0x5ff24c8 VA: 0x759860a4c8
	public override String get_EscapedCodeBase() { }
	// RVA: 0x5ff24d0 VA: 0x759860a4d0
	public override String get_FullName() { }
	// RVA: 0x5ff24d4 VA: 0x759860a4d4
	internal override IntPtr get_MonoAssembly() { }
	// RVA: 0x5ff24dc VA: 0x759860a4dc
	public override String get_Location() { }
	// RVA: 0x5ff2540 VA: 0x759860a540
	private Boolean GetManifestResourceInfoInternal(String name, ManifestResourceInfo info) { }
	// RVA: 0x5ff2544 VA: 0x759860a544
	public override ManifestResourceInfo GetManifestResourceInfo(String resourceName) { }
	// RVA: 0x5ff2654 VA: 0x759860a654
	public override String[] GetManifestResourceNames() { }
	// RVA: 0x5ff2658 VA: 0x759860a658
	internal IntPtr GetManifestResourceInternal(String name, out Int32 size, out Module module) { }
	// RVA: 0x5ff265c VA: 0x759860a65c
	public override Stream GetManifestResourceStream(String name) { }
	// RVA: 0x5ff2a10 VA: 0x759860aa10
	public override Boolean IsDefined(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff2a80 VA: 0x759860aa80
	public override Object[] GetCustomAttributes(Boolean inherit) { }
	// RVA: 0x5ff2ae8 VA: 0x759860aae8
	public override Object[] GetCustomAttributes(Type attributeType, Boolean inherit) { }
	// RVA: 0x5ff2b58 VA: 0x759860ab58
	internal override Module[] GetModulesInternal() { }
	// RVA: 0x5ff2b5c VA: 0x759860ab5c
	public override Int32 GetHashCode() { }
	// RVA: 0x5ff2b64 VA: 0x759860ab64
	public override Boolean Equals(Object o) { }
	// RVA: 0x5ff2c04 VA: 0x759860ac04
	public override String ToString() { }
}
```