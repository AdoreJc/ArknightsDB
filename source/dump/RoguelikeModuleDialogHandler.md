# RoguelikeModuleDialogHandler

**Namespace:** ` `


## Fields

- `String m_resPath`

- `TInput m_input`

- `Int32 m_instId`

- `MenuConfig <menuConfig>k__BackingField`

- `Single <showTweenDuration>k__BackingField`


## Properties

- `Type dialogType`

- `Int32 instId`

- `MenuConfig menuConfig`

- `Single showTweenDuration`


## Methods

- `Type get_dialogType()`

- `Int32 get_instId()`

- `MenuConfig get_menuConfig()`

- `Void set_menuConfig(MenuConfig)`

- `Single get_showTweenDuration()`

- `Void set_showTweenDuration(Single)`

- `Boolean OpenModuleDialog(UICompDialogMgr)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoguelikeModuleDialogHandler`2 : IRoguelikeModuleDialogHandler
{
	private String m_resPath; // 0x0
	private TInput m_input; // 0x0
	private Int32 m_instId; // 0x0
	private MenuConfig <menuConfig>k__BackingField; // 0x0
	private Single <showTweenDuration>k__BackingField; // 0x0

	public Type dialogType { get; }
	public Int32 instId { get; }
	public MenuConfig menuConfig { get; set; }
	public Single showTweenDuration { get; set; }

	// RVA: 0x VA: 0x0
	public Type get_dialogType() { }
	// RVA: 0x VA: 0x0
	public Int32 get_instId() { }
	// RVA: 0x VA: 0x0
	public MenuConfig get_menuConfig() { }
	// RVA: 0x VA: 0x0
	public Void set_menuConfig(MenuConfig value) { }
	// RVA: 0x VA: 0x0
	public Single get_showTweenDuration() { }
	// RVA: 0x VA: 0x0
	public Void set_showTweenDuration(Single value) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(String resPath, TInput options) { }
	// RVA: 0x VA: 0x0
	public Boolean OpenModuleDialog(UICompDialogMgr dialogMgr) { }
}
```