# Act20sideCarDetailCompObj

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Image _itemIcon`

- `Text _itemName`

- `Text _detailText`

- `GameObject _havePart`

- `GameObject _notHavePart`

- `GameObject _emptyPart`


## Methods

- `Void Render(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarDetailCompObj : MonoBehaviour, IHotfixable
{
	private Image _itemIcon; // 0x18
	private Text _itemName; // 0x20
	private Text _detailText; // 0x28
	private GameObject _havePart; // 0x30
	private GameObject _notHavePart; // 0x38
	private GameObject _emptyPart; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x32ed0ec VA: 0x75959050ec
	public Void Render(String compId, Boolean notAvail) { }
	// RVA: 0x32ed2e8 VA: 0x75959052e8
	public Void .ctor() { }
}
```