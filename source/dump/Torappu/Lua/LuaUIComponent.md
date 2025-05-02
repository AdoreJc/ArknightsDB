# LuaUIComponent

**Namespace:** `Torappu.Lua`


## Fields

- `Transform _root`

- `String _dialogClass`

- `UICoreCompHost _hostType`

- `LuaUIContext m_luaContext`

- `IEnumerator m_initRoutine`

- `UIPageFinder m_pageFiner`

- `UIStateFinder m_stateFinder`

- `UICompDialogFinder m_dialogFinder`


## Properties

- `Transform root`

- `String mainDialog`


## Methods

- `ILoadAsset _SelectAssetLoader()`

- `Boolean _TestIfCoreCompReady()`

- `Transform get_root()`

- `String get_mainDialog()`

- `T LoadAsset(String)`

- `Void OnLeaveContext()`

- `Void UnloadAsset(Object)`

- `Void Start()`

- `Void OnDestroy()`

- `IEnumerator _WaitForCoreCompReady(Action)`

- `Void _InitComponent()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Lua
public class LuaUIComponent : MonoBehaviour, IContextHost
{
	private const Int32 INIT_WAIT_FRAMES; // 0x0
	private Transform _root; // 0x18
	private String _dialogClass; // 0x20
	private ControllerDefine[] _ctrlDefines; // 0x28
	private ValueFieldDefine[] _valueDefines; // 0x30
	private UICoreCompHost _hostType; // 0x38
	private LuaUIContext m_luaContext; // 0x40
	private IEnumerator m_initRoutine; // 0x48
	private UIPageFinder m_pageFiner; // 0x50
	private UIStateFinder m_stateFinder; // 0x60
	private UICompDialogFinder m_dialogFinder; // 0x70

	public Transform root { get; }
	public String mainDialog { get; }

	// RVA: 0x35b3f6c VA: 0x7595bcbf6c
	private ILoadAsset _SelectAssetLoader() { }
	// RVA: 0x35b3fd8 VA: 0x7595bcbfd8
	private Boolean _TestIfCoreCompReady() { }
	// RVA: 0x35b3ff0 VA: 0x7595bcbff0
	public Transform get_root() { }
	// RVA: 0x35b4008 VA: 0x7595bcc008
	public String get_mainDialog() { }
	// RVA: 0x35b4010 VA: 0x7595bcc010
	public IDictionary`2 CompDeclaration() { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x35b4018 VA: 0x7595bcc018
	public Void OnLeaveContext() { }
	// RVA: 0x35b401c VA: 0x7595bcc01c
	public Void UnloadAsset(Object asset) { }
	// RVA: 0x35b40d8 VA: 0x7595bcc0d8
	private Void Start() { }
	// RVA: 0x35b434c VA: 0x7595bcc34c
	private Void OnDestroy() { }
	// RVA: 0x35b42bc VA: 0x7595bcc2bc
	private IEnumerator _WaitForCoreCompReady(Action nextStep) { }
	// RVA: 0x35b42a4 VA: 0x7595bcc2a4
	private Void _InitComponent() { }
	// RVA: 0x35b442c VA: 0x7595bcc42c
	public Void .ctor() { }
}
```