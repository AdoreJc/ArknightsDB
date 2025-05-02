# RuntimePanel

**Namespace:** `UnityEngine.UIElements`


## Properties

- `PanelSettings panelSettings`


## Methods

- `PanelSettings get_panelSettings()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
internal class RuntimePanel : BaseRuntimePanel
{
	internal static readonly EventDispatcher s_EventDispatcher; // 0x0
	private readonly PanelSettings m_PanelSettings; // 0x1d8

	public PanelSettings panelSettings { get; }

	// RVA: 0x6a02a40 VA: 0x759901aa40
	public PanelSettings get_panelSettings() { }
	// RVA: 0x6a02a48 VA: 0x759901aa48
	public static RuntimePanel Create(ScriptableObject ownerObject) { }
	// RVA: 0x6a02aa8 VA: 0x759901aaa8
	private Void .ctor(ScriptableObject ownerObject) { }
	// RVA: 0x6a02cec VA: 0x759901acec
	public override Void Update() { }
	// RVA: 0x6a02d6c VA: 0x759901ad6c
	private static Void .cctor() { }
}
```