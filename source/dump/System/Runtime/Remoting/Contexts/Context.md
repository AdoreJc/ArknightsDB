# Context

**Namespace:** `System.Runtime.Remoting.Contexts`


## Fields

- `Int32 domain_id`

- `Int32 context_id`

- `UIntPtr static_data`

- `UIntPtr data`

- `IMessageSink server_context_sink_chain`

- `IMessageSink client_context_sink_chain`

- `LocalDataStoreHolder _localDataStore`

- `DynamicPropertyCollection context_dynamic_properties`

- `ContextCallbackObject callback_object`


## Properties

- `LocalDataStore MyLocalStore`


## Methods

- `Void DoCallBack(CrossContextDelegate)`

- `LocalDataStore get_MyLocalStore()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Contexts
public class Context
{
	private Int32 domain_id; // 0x10
	private Int32 context_id; // 0x14
	private UIntPtr static_data; // 0x18
	private UIntPtr data; // 0x20
	private static Object[] local_slots; // 0x0
	private static IMessageSink default_server_context_sink; // 0x8
	private IMessageSink server_context_sink_chain; // 0x28
	private IMessageSink client_context_sink_chain; // 0x30
	private List`1 context_properties; // 0x38
	private static Int32 global_count; // 0x10
	private LocalDataStoreHolder _localDataStore; // 0x40
	private static LocalDataStoreMgr _localDataStoreMgr; // 0x18
	private static DynamicPropertyCollection global_dynamic_properties; // 0x20
	private DynamicPropertyCollection context_dynamic_properties; // 0x48
	private ContextCallbackObject callback_object; // 0x50

	public static Context DefaultContext { get; }
	public virtual Int32 ContextID { get; }
	public virtual IContextProperty[] ContextProperties { get; }
	internal Boolean IsDefaultContext { get; }
	internal Boolean NeedsContextSink { get; }
	internal static Boolean HasGlobalDynamicSinks { get; }
	internal Boolean HasDynamicSinks { get; }
	internal Boolean HasExitSinks { get; }
	private LocalDataStore MyLocalStore { get; }

	// RVA: 0x5f948bc VA: 0x75985ac8bc
	private static Void RegisterContext(Context ctx) { }
	// RVA: 0x5f948c0 VA: 0x75985ac8c0
	private static Void ReleaseContext(Context ctx) { }
	// RVA: 0x5f948c4 VA: 0x75985ac8c4
	public Void .ctor() { }
	// RVA: 0x5f94948 VA: 0x75985ac948
	protected override Void Finalize() { }
	// RVA: 0x5f94a18 VA: 0x75985aca18
	public static Context get_DefaultContext() { }
	// RVA: 0x5f94a20 VA: 0x75985aca20
	public virtual Int32 get_ContextID() { }
	// RVA: 0x5f94a28 VA: 0x75985aca28
	public virtual IContextProperty[] get_ContextProperties() { }
	// RVA: 0x5f94a9c VA: 0x75985aca9c
	internal Boolean get_IsDefaultContext() { }
	// RVA: 0x5f94aac VA: 0x75985acaac
	internal Boolean get_NeedsContextSink() { }
	// RVA: 0x5f94bbc VA: 0x75985acbbc
	public static Boolean RegisterDynamicProperty(IDynamicProperty prop, ContextBoundObject obj, Context ctx) { }
	// RVA: 0x5f9514c VA: 0x75985ad14c
	public static Boolean UnregisterDynamicProperty(String name, ContextBoundObject obj, Context ctx) { }
	// RVA: 0x5f94c34 VA: 0x75985acc34
	private static DynamicPropertyCollection GetDynamicPropertyCollection(ContextBoundObject obj, Context ctx) { }
	// RVA: 0x5f953b0 VA: 0x75985ad3b0
	internal static Void NotifyGlobalDynamicSinks(Boolean start, IMessage req_msg, Boolean client_site, Boolean async) { }
	// RVA: 0x5f95b0c VA: 0x75985adb0c
	internal static Boolean get_HasGlobalDynamicSinks() { }
	// RVA: 0x5f95bb0 VA: 0x75985adbb0
	internal Void NotifyDynamicSinks(Boolean start, IMessage req_msg, Boolean client_site, Boolean async) { }
	// RVA: 0x5f95c34 VA: 0x75985adc34
	internal Boolean get_HasDynamicSinks() { }
	// RVA: 0x5f91d54 VA: 0x75985a9d54
	internal Boolean get_HasExitSinks() { }
	// RVA: 0x5f95c74 VA: 0x75985adc74
	public virtual IContextProperty GetProperty(String name) { }
	// RVA: 0x5f95e5c VA: 0x75985ade5c
	public virtual Void SetProperty(IContextProperty prop) { }
	// RVA: 0x5f96020 VA: 0x75985ae020
	public virtual Void Freeze() { }
	// RVA: 0x5f961cc VA: 0x75985ae1cc
	public override String ToString() { }
	// RVA: 0x5f96228 VA: 0x75985ae228
	internal IMessageSink GetServerContextSinkChain() { }
	// RVA: 0x5f91e0c VA: 0x75985a9e0c
	internal IMessageSink GetClientContextSinkChain() { }
	// RVA: 0x5f96440 VA: 0x75985ae440
	internal IMessageSink CreateServerObjectSinkChain(MarshalByRefObject obj, Boolean forceInternalExecute) { }
	// RVA: 0x5f96704 VA: 0x75985ae704
	internal IMessageSink CreateEnvoySink(MarshalByRefObject serverObject) { }
	// RVA: 0x5f96908 VA: 0x75985ae908
	internal static Context SwitchToContext(Context newContext) { }
	// RVA: 0x5f96910 VA: 0x75985ae910
	internal static Context CreateNewContext(IConstructionCallMessage msg) { }
	// RVA: 0x5f97154 VA: 0x75985af154
	public Void DoCallBack(CrossContextDelegate deleg) { }
	// RVA: 0x5f972e4 VA: 0x75985af2e4
	private LocalDataStore get_MyLocalStore() { }
	// RVA: 0x5f9745c VA: 0x75985af45c
	public static LocalDataStoreSlot AllocateDataSlot() { }
	// RVA: 0x5f974c0 VA: 0x75985af4c0
	public static LocalDataStoreSlot AllocateNamedDataSlot(String name) { }
	// RVA: 0x5f9752c VA: 0x75985af52c
	public static Void FreeNamedDataSlot(String name) { }
	// RVA: 0x5f97598 VA: 0x75985af598
	public static LocalDataStoreSlot GetNamedDataSlot(String name) { }
	// RVA: 0x5f97604 VA: 0x75985af604
	public static Object GetData(LocalDataStoreSlot slot) { }
	// RVA: 0x5f97634 VA: 0x75985af634
	public static Void SetData(LocalDataStoreSlot slot, Object data) { }
	// RVA: 0x5f97674 VA: 0x75985af674
	private static Void .cctor() { }
}
```