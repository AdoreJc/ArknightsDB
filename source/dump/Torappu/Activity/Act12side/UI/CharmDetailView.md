# CharmDetailView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Text _name`

- `Text _price`

- `Text _effect`

- `Text _desc`

- `GameObject _specialObtainLine`

- `Text _sepcialObtainLabel`

- `GameObject _dropView`

- `Transform _dropRoot`

- `CharmDropStageItem _dropItemPrefab`


## Methods

- `Void Flush(CharmModel, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class CharmDetailView : MonoBehaviour, IHotfixable
{
	private Text _name; // 0x18
	private GameObject[] _rarityIcones; // 0x20
	private Text _price; // 0x28
	private Text _effect; // 0x30
	private Text _desc; // 0x38
	private GameObject _specialObtainLine; // 0x40
	private Text _sepcialObtainLabel; // 0x48
	private GameObject _dropView; // 0x50
	private Transform _dropRoot; // 0x58
	private CharmDropStageItem _dropItemPrefab; // 0x60
	private List`1 m_dropItems; // 0x68
	private List`1 m_dropStages; // 0x70
	private static DelegateBridge __Hotfix0_Flush; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x34509e0 VA: 0x7595a689e0
	public Void Flush(CharmModel cm, String activityID) { }
	// RVA: 0x34515fc VA: 0x7595a695fc
	public Void .ctor() { }
}
```