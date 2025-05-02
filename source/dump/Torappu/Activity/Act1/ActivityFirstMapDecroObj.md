# ActivityFirstMapDecroObj

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `Text _zoneIndex`

- `GameObject _selectedPart`

- `String m_zoneCacheId`


## Methods

- `Void InitData(DefaultZoneData)`

- `Void OnSelect(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstMapDecroObj : MonoBehaviour, IHotfixable
{
	private Text _zoneIndex; // 0x18
	private GameObject _selectedPart; // 0x20
	private String m_zoneCacheId; // 0x28
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_OnSelect; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3490a68 VA: 0x7595aa8a68
	public Void InitData(DefaultZoneData zoneData) { }
	// RVA: 0x3490b10 VA: 0x7595aa8b10
	public Void OnSelect(String selectId) { }
	// RVA: 0x3490c34 VA: 0x7595aa8c34
	public Void .ctor() { }
}
```