# BuildingCharAvatarStationAdatper

**Namespace:** `Torappu.Building.UI`


## Fields

- `IProvider m_provider`

- `Boolean m_isInited`

- `CharListAdapter m_listAdapter`


## Methods

- `Void Render()`

- `Void _OnCharClicked(BuildingCharModel, Object)`

- `Void _OnLockedSlotClicked(Object)`

- `Void _RegisterFirstEmptySlotToAVG()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingCharAvatarStationAdatper
{
	private IProvider m_provider; // 0x10
	private BuildingCharModel[] m_chars; // 0x18
	private Boolean m_isInited; // 0x20
	private CharListAdapter m_listAdapter; // 0x28


	// RVA: 0x3d42888 VA: 0x759635a888
	public Void .ctor(IProvider provider) { }
	// RVA: 0x3d428b8 VA: 0x759635a8b8
	public Void Render() { }
	// RVA: 0x3d42ce0 VA: 0x759635ace0
	private Void _OnCharClicked(BuildingCharModel charModel, Object index) { }
	// RVA: 0x3d42ea4 VA: 0x759635aea4
	private Void _OnLockedSlotClicked(Object index) { }
	// RVA: 0x3d42b30 VA: 0x759635ab30
	private Void _RegisterFirstEmptySlotToAVG() { }
}
```