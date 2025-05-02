# PropagationPaths

**Namespace:** `UnityEngine.UIElements`


## Methods

- `Void Release()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class PropagationPaths
{
	private static readonly ObjectPool`1 s_Pool; // 0x0
	public readonly List`1 trickleDownPath; // 0x10
	public readonly List`1 targetElements; // 0x18
	public readonly List`1 bubbleUpPath; // 0x20
	private const Int32 k_DefaultPropagationDepth; // 0x0
	private const Int32 k_DefaultTargetCount; // 0x0


	// RVA: 0x69fe5e4 VA: 0x75990165e4
	public Void .ctor() { }
	// RVA: 0x69fe6d0 VA: 0x75990166d0
	internal static PropagationPaths Copy(PropagationPaths paths) { }
	// RVA: 0x69fe7b0 VA: 0x75990167b0
	public static PropagationPaths Build(VisualElement elem, EventBase evt, Type pathTypesRequested) { }
	// RVA: 0x69fea60 VA: 0x7599016a60
	public Void Release() { }
	// RVA: 0x69feb70 VA: 0x7599016b70
	private static Void .cctor() { }
}
```