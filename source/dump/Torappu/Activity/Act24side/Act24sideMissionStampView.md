# Act24sideMissionStampView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `UIAtlasImage _stamp`

- `Image _stampSchedule`

- `GameObject _stampUnreceive`

- `GameObject _stampEntity`

- `GameObject _missionNumObj`

- `Text _missionNum`

- `Color _stampUncompleteColor`

- `Color _stampCompleteColor`


## Methods

- `Void Render(Act24sideMissionObjViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionStampView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _stamp; // 0x18
	private Image _stampSchedule; // 0x20
	private GameObject _stampUnreceive; // 0x28
	private GameObject _stampEntity; // 0x30
	private GameObject _missionNumObj; // 0x38
	private Text _missionNum; // 0x40
	private Color _stampUncompleteColor; // 0x48
	private Color _stampCompleteColor; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x32b75fc VA: 0x75958cf5fc
	public Void Render(Act24sideMissionObjViewModel model) { }
	// RVA: 0x32bd28c VA: 0x75958d528c
	public Void .ctor() { }
}
```