# MobileFileExplorer

**Namespace:** `Torappu.Multiplayer`


## Fields

- `InputField _pathView`

- `ScrollRect _scrolll`

- `Button _cellTemplate`

- `String m_rootDir`

- `String m_filter`

- `String m_showedDir`


## Methods

- `Void Show(String, Action`1, String)`

- `Boolean _ShowItemList(String)`

- `Void _AddItem(String, ItemType)`

- `Void _ReturnParent()`

- `Void _ClickDir(String)`

- `Void _ClickFile(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class MobileFileExplorer : MonoBehaviour
{
	private InputField _pathView; // 0x18
	private ScrollRect _scrolll; // 0x20
	private Button _cellTemplate; // 0x28
	private String m_rootDir; // 0x30
	private String m_filter; // 0x38
	private Action`1 m_selected; // 0x40
	private String m_showedDir; // 0x48


	// RVA: 0x3590cc0 VA: 0x7595ba8cc0
	public Void Show(String rootPath, Action`1 slected, String filter) { }
	// RVA: 0x3590d94 VA: 0x7595ba8d94
	private Boolean _ShowItemList(String dirPath) { }
	// RVA: 0x3590ffc VA: 0x7595ba8ffc
	private Void _AddItem(String path, ItemType type) { }
	// RVA: 0x3591358 VA: 0x7595ba9358
	private Void _ReturnParent() { }
	// RVA: 0x35913c0 VA: 0x7595ba93c0
	private Void _ClickDir(String path) { }
	// RVA: 0x35913c4 VA: 0x7595ba93c4
	private Void _ClickFile(String path) { }
	// RVA: 0x3591414 VA: 0x7595ba9414
	public Void .ctor() { }
}
```