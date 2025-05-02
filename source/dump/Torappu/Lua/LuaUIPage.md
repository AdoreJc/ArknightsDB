# LuaUIPage

**Namespace:** `Torappu.Lua`


## Fields

- `String _mainDialog`

- `RectTransform _dlgRoot`

- `LuaUIContext m_context`


## Properties

- `Transform root`

- `String mainDialog`


## Methods

- `Transform get_root()`

- `String get_mainDialog()`

- `Void OnLeaveContext()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnPageRouted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Lua
public class LuaUIPage : UIPage, IContextHost
{
	private String _mainDialog; // 0xd0
	private RectTransform _dlgRoot; // 0xd8
	private LuaUIContext m_context; // 0xe0
	private static DelegateBridge __Hotfix0_get_root; // 0x0
	private static DelegateBridge __Hotfix0_get_mainDialog; // 0x8
	private static DelegateBridge __Hotfix0_OnLeaveContext; // 0x10
	private static DelegateBridge __Hotfix0_OnCreate; // 0x18
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x20
	private static DelegateBridge __Hotfix0_CompDeclaration; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Transform root { get; }
	public String mainDialog { get; }

	// RVA: 0x35b4648 VA: 0x7595bcc648
	public Transform get_root() { }
	// RVA: 0x35b4700 VA: 0x7595bcc700
	public String get_mainDialog() { }
	// RVA: 0x35b4768 VA: 0x7595bcc768
	public Void OnLeaveContext() { }
	// RVA: 0x35b47d4 VA: 0x7595bcc7d4
	protected override Void OnCreate(DataBundle savedInstance) { }
	// RVA: 0x35b4a1c VA: 0x7595bcca1c
	protected override Void OnPageRouted() { }
	// RVA: 0x35b4aa4 VA: 0x7595bccaa4
	public IDictionary`2 CompDeclaration() { }
	// RVA: 0x35b4b08 VA: 0x7595bccb08
	public Void .ctor() { }
	// RVA: 0x35b4b78 VA: 0x7595bccb78
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x35b4b80 VA: 0x7595bccb80
	private Void <>xLuaBaseProxy_OnPageRouted() { }
}
```