# ActivationServices

**Namespace:** `System.Runtime.Remoting.Activation`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Activation
internal class ActivationServices
{
	private static IActivator _constructionActivator; // 0x0

	private static IActivator ConstructionActivator { get; }

	// RVA: 0x5f9ced0 VA: 0x75985b4ed0
	private static IActivator get_ConstructionActivator() { }
	// RVA: 0x5f92694 VA: 0x75985aa694
	public static IMessage Activate(RemotingProxy proxy, ConstructionCall ctorCall) { }
	// RVA: 0x5f9cf7c VA: 0x75985b4f7c
	public static IMessage RemoteActivate(IConstructionCallMessage ctorCall) { }
	// RVA: 0x5f90c90 VA: 0x75985a8c90
	public static ConstructionCall CreateConstructionCall(Type type, String activationUrl, Object[] activationAttributes) { }
	// RVA: 0x5f9d1c0 VA: 0x75985b51c0
	public static IMessage CreateInstanceFromMessage(IConstructionCallMessage ctorCall) { }
	// RVA: 0x5f9d5c4 VA: 0x75985b55c4
	public static Object CreateProxyForType(Type type) { }
	// RVA: 0x5f9d5c0 VA: 0x75985b55c0
	public static Object AllocateUninitializedClassInstance(Type type) { }
	// RVA: 0x5f9d704 VA: 0x75985b5704
	public static Void EnableProxyActivation(Type type, Boolean enable) { }
}
```