# BuildingSMRoomInfoList

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `SimpleLayoutContent _itemContainer`

- `Adapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void Render(StationRoomStructModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingSMRoomInfoList : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _itemContainer; // 0x18
	private Adapter m_adapter; // 0x20
	private Boolean m_isInited; // 0x28
	private StationCharStructModel[] m_chars; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3dae690 VA: 0x75963c6690
	public Void Render(StationRoomStructModel roomModel) { }
	// RVA: 0x3dae778 VA: 0x75963c6778
	private Void _InitIfNot() { }
	// RVA: 0x3dae934 VA: 0x75963c6934
	public Void .ctor() { }
}
```