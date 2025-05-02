# TestLogConsole

**Namespace:** `Torappu`


## Fields

- `Rect area`

- `Boolean m_collasped`

- `Vector2 m_scrollPos`


## Methods

- `Void OnEnable()`

- `Void OnDisable()`

- `Void HandleLog(String, String, LogType)`

- `Void OnGUI()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TestLogConsole : MonoBehaviour
{
	private Rect area; // 0x18
	private List`1 m_itemList; // 0x28
	private Boolean m_collasped; // 0x30
	private Vector2 m_scrollPos; // 0x34


	// RVA: 0x2d07ef0 VA: 0x759531fef0
	private Void OnEnable() { }
	// RVA: 0x2d07f70 VA: 0x759531ff70
	private Void OnDisable() { }
	// RVA: 0x2d07ff0 VA: 0x759531fff0
	private Void HandleLog(String logString, String stackTrace, LogType type) { }
	// RVA: 0x2d08130 VA: 0x7595320130
	private Void OnGUI() { }
	// RVA: 0x2d0853c VA: 0x759532053c
	public Void .ctor() { }
}
```