# SandboxPermTopicResHolder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Sprite _entryImg`

- `ZoneHomeSandboxPermTodoPluginBase _todoPluginPrefab`


## Properties

- `Sprite entryImg`

- `ZoneHomeSandboxPermTodoPluginBase todoPluginPrefab`


## Methods

- `Sprite get_entryImg()`

- `ZoneHomeSandboxPermTodoPluginBase get_todoPluginPrefab()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SandboxPermTopicResHolder : MonoBehaviour, IHotfixable
{
	private Sprite _entryImg; // 0x18
	private ZoneHomeSandboxPermTodoPluginBase _todoPluginPrefab; // 0x20
	private static DelegateBridge __Hotfix0_get_entryImg; // 0x0
	private static DelegateBridge __Hotfix0_get_todoPluginPrefab; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Sprite entryImg { get; }
	public ZoneHomeSandboxPermTodoPluginBase todoPluginPrefab { get; }

	// RVA: 0x2f13460 VA: 0x759552b460
	public Sprite get_entryImg() { }
	// RVA: 0x2f10a4c VA: 0x7595528a4c
	public ZoneHomeSandboxPermTodoPluginBase get_todoPluginPrefab() { }
	// RVA: 0x2f134c8 VA: 0x759552b4c8
	public Void .ctor() { }
}
```