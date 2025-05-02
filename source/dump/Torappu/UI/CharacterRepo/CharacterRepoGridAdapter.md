# CharacterRepoGridAdapter

**Namespace:** `Torappu.UI.CharacterRepo`


## Fields

- `GameObject _characterPanelPrefab`

- `UICharacterCardSelectEvent cardStarMarkSelectEvent`

- `Boolean m_disableLockAndInSquad`

- `Boolean m_enableStarMarkSelectMode`

- `CharacterSortType m_currentSortType`

- `Boolean m_AVGIsFirstItemRegistered`

- `Params m_charCardParams`


## Methods

- `Void SetArguments(RepoGridParam)`

- `Void _OnCardClick(Int32)`

- `Void _OnStarMarkSelected(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterRepo
public class CharacterRepoGridAdapter : UICharacterCardScrollAdapter`1
{
	private GameObject _characterPanelPrefab; // 0x60
	public UICharacterCardSelectEvent cardStarMarkSelectEvent; // 0x68
	private Boolean m_disableLockAndInSquad; // 0x70
	private List`1 m_selectedInstIds; // 0x78
	private Dictionary`2 m_charId2TrackPointDataMap; // 0x80
	private HashSet`1 m_starMarkSelectedInstIds; // 0x88
	private Boolean m_enableStarMarkSelectMode; // 0x90
	private CharacterSortType m_currentSortType; // 0x94
	private Boolean m_AVGIsFirstItemRegistered; // 0x98
	private Params m_charCardParams; // 0xa0
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x0
	private static DelegateBridge __Hotfix0_SetArguments; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge __Hotfix0_CreateView; // 0x18
	private static DelegateBridge __Hotfix0__OnCardClick; // 0x20
	private static DelegateBridge __Hotfix0__OnStarMarkSelected; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2cfdc40 VA: 0x7595315c40
	protected override Void OnDataSourceChanged() { }
	// RVA: 0x2cfdcc4 VA: 0x7595315cc4
	public Void SetArguments(RepoGridParam param) { }
	// RVA: 0x2cfddd0 VA: 0x7595315dd0
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, CharacterCardViewModel data) { }
	// RVA: 0x2cfe12c VA: 0x759531612c
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x2cfe1ec VA: 0x75953161ec
	private Void _OnCardClick(Int32 chrInstId) { }
	// RVA: 0x2cfe298 VA: 0x7595316298
	private Void _OnStarMarkSelected(Int32 chrInstId) { }
	// RVA: 0x2cfe344 VA: 0x7595316344
	public Void .ctor() { }
}
```