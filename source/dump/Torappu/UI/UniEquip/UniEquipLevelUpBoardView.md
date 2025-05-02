# UniEquipLevelUpBoardView

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `GameObject _arrow`

- `GameObject _targetNextArrow`

- `Image _levelImage`

- `GameObject _selectTargetLight`

- `Button _arrowBtn`

- `Button _boardBtn`

- `Color _targetLevelImageColor`

- `Color _notTargetLevelImageColor`

- `UniEquipLevelUpNormalInfoView _basicInfoView`

- `UniEquipLevelUpSubProfessionView _subProfessionView`

- `UniEquipLevelUpNormalInfoView _talentView`

- `Boolean m_boardLevelIsCur`

- `Int32 m_boardLevel`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(UniEquipLevelUpBoardObjViewModel)`

- `Void EventOnSelectTargetLevel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipLevelUpBoardView : MonoBehaviour, IHotfixable
{
	private GameObject _arrow; // 0x18
	private GameObject _targetNextArrow; // 0x20
	private Image _levelImage; // 0x28
	private List`1 _stageSprites; // 0x30
	private GameObject _selectTargetLight; // 0x38
	private Button _arrowBtn; // 0x40
	private Button _boardBtn; // 0x48
	private Color _targetLevelImageColor; // 0x50
	private Color _notTargetLevelImageColor; // 0x60
	private UniEquipLevelUpNormalInfoView _basicInfoView; // 0x70
	private UniEquipLevelUpSubProfessionView _subProfessionView; // 0x78
	private UniEquipLevelUpNormalInfoView _talentView; // 0x80
	private Boolean m_boardLevelIsCur; // 0x88
	private Int32 m_boardLevel; // 0x8c
	private UIStateFinder m_stateFinder; // 0x90
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnSelectTargetLevel; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22ffd2c VA: 0x7594917d2c
	public Void Render(UniEquipLevelUpBoardObjViewModel model) { }
	// RVA: 0x23003a0 VA: 0x75949183a0
	public Void EventOnSelectTargetLevel() { }
	// RVA: 0x2300474 VA: 0x7594918474
	public Void .ctor() { }
}
```