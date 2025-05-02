# SandboxV2RacerInventoryDetailView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _panelEmpty`

- `GameObject _panelNotEmpty`

- `Text _textEmpty`

- `Image _imgIcon`

- `GameObject _panelMark`

- `GameObject _imgNoInfo`

- `GameObject _panelNotMarked`

- `GameObject _panelMarked`

- `Text _textName`

- `Text _textTypeName`

- `GameObject _panelMedal`

- `SimpleLayoutContent _contentMedal`

- `SimpleLayoutContent _contentAttribute`

- `SimpleLayoutContent _contentLevel`

- `UIRadarMap _radarMap`

- `SandboxV2RacerInventoryTalentView _talentPrefab`

- `RectTransform _bornTalentContainer`

- `RectTransform _learnedTalentContainer`

- `Boolean m_hasInited`

- `UIStateFinder m_stateFinder`

- `MedalAdapter m_medalAdapter`

- `AttributeAdapter m_attributeAdapter`

- `Int32 m_cachedRacerLevel`

- `LevelAdapter m_levelAdapter`

- `SandboxV2RacerInventoryTalentView m_bornTalent`

- `SandboxV2RacerInventoryTalentView m_learnedTalent`


## Methods

- `Void Render(SandboxV2RacerModel, String, Boolean, Int32)`

- `Void EventOnMarkBtnClicked()`

- `Void EventOnMedalGroupBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerInventoryDetailView : MonoBehaviour, IHotfixable
{
	private GameObject _panelEmpty; // 0x18
	private GameObject _panelNotEmpty; // 0x20
	private Text _textEmpty; // 0x28
	private Image _imgIcon; // 0x30
	private GameObject _panelMark; // 0x38
	private GameObject _imgNoInfo; // 0x40
	private GameObject _panelNotMarked; // 0x48
	private GameObject _panelMarked; // 0x50
	private Text _textName; // 0x58
	private Text _textTypeName; // 0x60
	private GameObject _panelMedal; // 0x68
	private SimpleLayoutContent _contentMedal; // 0x70
	private SimpleLayoutContent _contentAttribute; // 0x78
	private SimpleLayoutContent _contentLevel; // 0x80
	private UIRadarMap _radarMap; // 0x88
	private Text[] _textRadarMapName; // 0x90
	private SandboxV2RacerInventoryTalentView _talentPrefab; // 0x98
	private RectTransform _bornTalentContainer; // 0xa0
	private RectTransform _learnedTalentContainer; // 0xa8
	private Boolean m_hasInited; // 0xb0
	private List`1 m_cachedMedalList; // 0xb8
	private UIStateFinder m_stateFinder; // 0xc0
	private MedalAdapter m_medalAdapter; // 0xd0
	private List`1 m_cachedAttributeList; // 0xd8
	private AttributeAdapter m_attributeAdapter; // 0xe0
	private Int32 m_cachedRacerLevel; // 0xe8
	private LevelAdapter m_levelAdapter; // 0xf0
	private SandboxV2RacerInventoryTalentView m_bornTalent; // 0xf8
	private SandboxV2RacerInventoryTalentView m_learnedTalent; // 0x100
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnMarkBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnMedalGroupBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x25df138 VA: 0x7594bf7138
	public Void Render(SandboxV2RacerModel model, String emptyDesc, Boolean showTalentRefreshBtn, Int32 learnedSequenceNum) { }
	// RVA: 0x25dfe34 VA: 0x7594bf7e34
	public Void EventOnMarkBtnClicked() { }
	// RVA: 0x25dfed8 VA: 0x7594bf7ed8
	public Void EventOnMedalGroupBtnClicked() { }
	// RVA: 0x25df640 VA: 0x7594bf7640
	private Void _InitIfNot() { }
	// RVA: 0x25e0138 VA: 0x7594bf8138
	public Void .ctor() { }
}
```