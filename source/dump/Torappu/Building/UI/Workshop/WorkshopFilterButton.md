# WorkshopFilterButton

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `Boolean m_actived`


## Properties

- `Boolean actived`


## Methods

- `Void add_onButtonPressed(Action`1)`

- `Void remove_onButtonPressed(Action`1)`

- `Boolean get_actived()`

- `Void SetEnabled(Boolean)`

- `Void OnButtonPressed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class WorkshopFilterButton : MonoBehaviour
{
	private GameObject[] _activeObjects; // 0x18
	private GameObject[] _inactiveObjects; // 0x20
	private Action`1 onButtonPressed; // 0x28
	private Boolean m_actived; // 0x30

	public Boolean actived { get; }

	// RVA: 0x3d7313c VA: 0x759638b13c
	public Void add_onButtonPressed(Action`1 value) { }
	// RVA: 0x3d731ec VA: 0x759638b1ec
	public Void remove_onButtonPressed(Action`1 value) { }
	// RVA: 0x3d7329c VA: 0x759638b29c
	public Boolean get_actived() { }
	// RVA: 0x3d732a4 VA: 0x759638b2a4
	public Void SetEnabled(Boolean enabled) { }
	// RVA: 0x3d7338c VA: 0x759638b38c
	public Void OnButtonPressed() { }
	// RVA: 0x3d733ac VA: 0x759638b3ac
	public Void .ctor() { }
}
```