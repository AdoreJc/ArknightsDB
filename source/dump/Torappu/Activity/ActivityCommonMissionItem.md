# ActivityCommonMissionItem

**Namespace:** `Torappu.Activity`


## Fields

- `Text _missionDetail`

- `Text _coinCount`

- `Transform _itemContainer`

- `GameObject _canAchievePart`

- `GameObject _onUsingPart`

- `Text _stateText`

- `Single _itemCardScaleFactor`

- `RectTransform _lineBar`

- `Single _lineLength`

- `UIStringEvent sendEvent`

- `UIItemCard m_itemCard`

- `String m_missionId`


## Methods

- `Void Render(MissionViewModel)`

- `Void OnClick()`

- `Void _OnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityCommonMissionItem : MonoBehaviour
{
	private Text _missionDetail; // 0x18
	private Text _coinCount; // 0x20
	private Transform _itemContainer; // 0x28
	private GameObject _canAchievePart; // 0x30
	private GameObject _onUsingPart; // 0x38
	private Text _stateText; // 0x40
	private Single _itemCardScaleFactor; // 0x48
	private RectTransform _lineBar; // 0x50
	private Single _lineLength; // 0x58
	public UIStringEvent sendEvent; // 0x60
	private UIItemCard m_itemCard; // 0x68
	private List`1 m_itemCardList; // 0x70
	private String m_missionId; // 0x78


	// RVA: 0x30d272c VA: 0x75956ea72c
	public Void Render(MissionViewModel missionData) { }
	// RVA: 0x30d2c1c VA: 0x75956eac1c
	public Void OnClick() { }
	// RVA: 0x30d2c78 VA: 0x75956eac78
	private Void _OnItemCardClicked(Int32 position) { }
	// RVA: 0x30d2d58 VA: 0x75956ead58
	public Void .ctor() { }
}
```