# ActivityFirstMissionItem

**Namespace:** `Torappu.Activity.Act1`


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
// Namespace : Torappu.Activity.Act1
public class ActivityFirstMissionItem : MonoBehaviour, IHotfixable
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
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0__OnItemCardClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3491a28 VA: 0x7595aa9a28
	public Void Render(MissionViewModel missionData) { }
	// RVA: 0x3491f30 VA: 0x7595aa9f30
	public Void OnClick() { }
	// RVA: 0x3491fc4 VA: 0x7595aa9fc4
	private Void _OnItemCardClicked(Int32 position) { }
	// RVA: 0x34920f0 VA: 0x7595aaa0f0
	public Void .ctor() { }
}
```