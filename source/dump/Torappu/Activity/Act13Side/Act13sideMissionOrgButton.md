# Act13sideMissionOrgButton

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Image _orgImg`

- `TwoStateToggle _activeToggle`

- `GameObject _unlockPart`

- `UICommonTrackPoint _trackPoint`

- `UICommonTrackPoint _newTrackPoint`

- `TrackPointViewProperty m_property`

- `TrackPointViewProperty m_newProperty`

- `Boolean m_isInited`

- `UIStringEvent m_onClick`

- `String m_targetOrg`


## Methods

- `Void _InitIfNot()`

- `Void Init(String, String, UIStringEvent)`

- `Void ApplySelect(String, String, Boolean, Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideMissionOrgButton : MonoBehaviour, IHotfixable
{
	private Image _orgImg; // 0x18
	private TwoStateToggle _activeToggle; // 0x20
	private GameObject _unlockPart; // 0x28
	private UICommonTrackPoint _trackPoint; // 0x30
	private UICommonTrackPoint _newTrackPoint; // 0x38
	private TrackPointViewProperty m_property; // 0x40
	private TrackPointViewProperty m_newProperty; // 0x48
	private Boolean m_isInited; // 0x50
	private UIStringEvent m_onClick; // 0x58
	private String m_targetOrg; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_ApplySelect; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3441770 VA: 0x7595a59770
	private Void _InitIfNot() { }
	// RVA: 0x3433844 VA: 0x7595a4b844
	public Void Init(String actId, String org_, UIStringEvent onClick) { }
	// RVA: 0x3433974 VA: 0x7595a4b974
	public Void ApplySelect(String actId, String currentOrg, Boolean haveReward, Boolean isTimely) { }
	// RVA: 0x34418a8 VA: 0x7595a598a8
	public Void OnClick() { }
	// RVA: 0x3441958 VA: 0x7595a59958
	public Void .ctor() { }
}
```