# Act24sideMissionDelegateTitleView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Color _hunterColor`

- `Color _collectionColor`

- `Color _explorationColor`

- `Color _titleHunterColor`

- `Color _titleCollectionColor`

- `Color _titleExploraionColor`

- `GameObject _hunterLeft`

- `GameObject _collectionLeft`

- `GameObject _explorationLeft`

- `GameObject _hunterTitle`

- `GameObject _collectionTitle`

- `GameObject _explorationTitle`

- `Text _titleTxt`


## Methods

- `Void Render(MissionType)`

- `Void _MissionTypeDisplay(MissionType)`

- `Void _SetTypeDisplay(Color, Color, GameObject, GameObject)`

- `Void _ResetAll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionDelegateTitleView : MonoBehaviour, IHotfixable
{
	private List`1 _typeColorAtlasImage; // 0x18
	private Color _hunterColor; // 0x20
	private Color _collectionColor; // 0x30
	private Color _explorationColor; // 0x40
	private Color _titleHunterColor; // 0x50
	private Color _titleCollectionColor; // 0x60
	private Color _titleExploraionColor; // 0x70
	private GameObject _hunterLeft; // 0x80
	private GameObject _collectionLeft; // 0x88
	private GameObject _explorationLeft; // 0x90
	private GameObject _hunterTitle; // 0x98
	private GameObject _collectionTitle; // 0xa0
	private GameObject _explorationTitle; // 0xa8
	private Text _titleTxt; // 0xb0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__MissionTypeDisplay; // 0x8
	private static DelegateBridge __Hotfix0__SetTypeDisplay; // 0x10
	private static DelegateBridge __Hotfix0__ResetAll; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x32b4a5c VA: 0x75958cca5c
	public Void Render(MissionType type) { }
	// RVA: 0x32b4adc VA: 0x75958ccadc
	private Void _MissionTypeDisplay(MissionType type) { }
	// RVA: 0x32b4c98 VA: 0x75958ccc98
	private Void _SetTypeDisplay(Color typeColor, Color titleColor, GameObject title, GameObject left) { }
	// RVA: 0x32b4bd8 VA: 0x75958ccbd8
	private Void _ResetAll() { }
	// RVA: 0x32b4f44 VA: 0x75958ccf44
	public Void .ctor() { }
}
```