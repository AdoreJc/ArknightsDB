# MissionBookTagTab

**Namespace:** `Torappu.UI.Mission`


## Fields

- `Animator _selectedState`

- `GameObject _startMissionTag`

- `Transform _hotspot`

- `GameObject _trackPoint`

- `IParentView m_parentView`

- `Boolean m_isSelected`

- `Int32 m_index`

- `MissionPageType m_pageType`


## Properties

- `MissionPageType pageType`


## Methods

- `MissionPageType get_pageType()`

- `Void OnEnable()`

- `Void SetData(Int32, MissionPageType, String, IParentView, Sprite)`

- `Void SetStatus(Int32)`

- `Void ActiveTrackPoint(Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MissionBookTagTab : MonoBehaviour
{
	private const String HOTSPOT_NAME_FORMAT; // 0x0
	private Animator _selectedState; // 0x18
	private Text[] _missionNameLabels; // 0x20
	private Image[] _missionImages; // 0x28
	private GameObject _startMissionTag; // 0x30
	private Transform _hotspot; // 0x38
	private GameObject _trackPoint; // 0x40
	private IParentView m_parentView; // 0x48
	private Boolean m_isSelected; // 0x50
	private Int32 m_index; // 0x54
	private MissionPageType m_pageType; // 0x58
	public const String MISSION_TAG_SELECTED; // 0x0
	public const String MISSION_TAG_UNSELECTED; // 0x0
	public const String MISSION_TAG_INIT; // 0x0

	public MissionPageType pageType { get; }

	// RVA: 0x27415dc VA: 0x7594d595dc
	public MissionPageType get_pageType() { }
	// RVA: 0x27415e4 VA: 0x7594d595e4
	private Void OnEnable() { }
	// RVA: 0x274059c VA: 0x7594d5859c
	public Void SetData(Int32 index, MissionPageType type, String typeName, IParentView parentView, Sprite icon) { }
	// RVA: 0x2740f08 VA: 0x7594d58f08
	public Void SetStatus(Int32 selectedIndex) { }
	// RVA: 0x2740be4 VA: 0x7594d58be4
	public Void ActiveTrackPoint(Boolean active) { }
	// RVA: 0x2741658 VA: 0x7594d59658
	public Void OnClick() { }
	// RVA: 0x274170c VA: 0x7594d5970c
	public Void .ctor() { }
}
```