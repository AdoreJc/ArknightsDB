# AttributeHelperEngine

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
internal class AttributeHelperEngine
{
	public static DisallowMultipleComponent[] _disallowMultipleComponentArray; // 0x0
	public static ExecuteInEditMode[] _executeInEditModeArray; // 0x8
	public static RequireComponent[] _requireComponentArray; // 0x10


	// RVA: 0x6882450 VA: 0x7598e9a450
	private static Type GetParentTypeDisallowingMultipleInclusion(Type type) { }
	// RVA: 0x6882550 VA: 0x7598e9a550
	private static Type[] GetRequiredComponents(Type klass) { }
	// RVA: 0x68829bc VA: 0x7598e9a9bc
	private static Int32 GetExecuteMode(Type klass) { }
	// RVA: 0x6882ad0 VA: 0x7598e9aad0
	private static Int32 CheckIsEditorScript(Type klass) { }
	// RVA: 0x6882bb0 VA: 0x7598e9abb0
	private static Int32 GetDefaultExecutionOrderFor(Type klass) { }
	// RVA: 0x VA: 0x0
	private static T GetCustomAttributeOfType(Type klass) { }
	// RVA: 0x6882c34 VA: 0x7598e9ac34
	private static Void .cctor() { }
}
```