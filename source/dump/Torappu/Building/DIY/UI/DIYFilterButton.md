# DIYFilterButton

**Namespace:** `Torappu.Building.DIY.UI`


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
// Namespace : Torappu.Building.DIY.UI
public class DIYFilterButton : MonoBehaviour
{
	private GameObject[] _activeObjects; // 0x18
	private GameObject[] _inactiveObjects; // 0x20
	private Action`1 onButtonPressed; // 0x28
	private Boolean m_actived; // 0x30

	public Boolean actived { get; }

	// RVA: 0x37fedc0 VA: 0x7595e16dc0
	public Void add_onButtonPressed(Action`1 value) { }
	// RVA: 0x37fee70 VA: 0x7595e16e70
	public Void remove_onButtonPressed(Action`1 value) { }
	// RVA: 0x37fef20 VA: 0x7595e16f20
	public Boolean get_actived() { }
	// RVA: 0x37fef28 VA: 0x7595e16f28
	public Void SetEnabled(Boolean enabled) { }
	// RVA: 0x37ff010 VA: 0x7595e17010
	public Void OnButtonPressed() { }
	// RVA: 0x37ff030 VA: 0x7595e17030
	public Void .ctor() { }
}
```