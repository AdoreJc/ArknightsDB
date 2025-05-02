# VisualElementFactoryRegistry

**Namespace:** `UnityEngine.UIElements`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class VisualElementFactoryRegistry
{
	private static Dictionary`2 s_Factories; // 0x0

	internal static Dictionary`2 factories { get; }

	// RVA: 0x6a21924 VA: 0x7599039924
	internal static Dictionary`2 get_factories() { }
	// RVA: 0x6a22984 VA: 0x759903a984
	protected static Void RegisterFactory(IUxmlFactory factory) { }
	// RVA: 0x6a22e08 VA: 0x759903ae08
	internal static Boolean TryGetValue(String fullTypeName, out List`1 factoryList) { }
	// RVA: 0x6a219e4 VA: 0x75990399e4
	private static Void RegisterEngineFactories() { }
	// RVA: 0x6a226b4 VA: 0x759903a6b4
	internal static Void RegisterUserFactories() { }
}
```