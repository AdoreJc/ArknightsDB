# Act13sideDailyMissionSearchView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `TwoStateToggle _orgRandomToggle`

- `TwoStateToggle _matRandomToggle`

- `Text _textOrgSelection`

- `Text _textMatSelection`

- `Text _textSearchCount`

- `SimpleLayoutContent _orgOptionList`

- `SimpleLayoutContent _matOptionList`

- `Boolean m_hasInited`

- `OrgListAdapter m_orgListAdapter`

- `MatListAdapter m_matListAdapter`

- `Act13sideDailySearchViewModel m_model`


## Methods

- `Void Init(Action`1, Action`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyMissionSearchView : DataBinder`1
{
	private TwoStateToggle _orgRandomToggle; // 0x20
	private TwoStateToggle _matRandomToggle; // 0x28
	private Text _textOrgSelection; // 0x30
	private Text _textMatSelection; // 0x38
	private Text _textSearchCount; // 0x40
	private SimpleLayoutContent _orgOptionList; // 0x48
	private SimpleLayoutContent _matOptionList; // 0x50
	private Boolean m_hasInited; // 0x58
	private OrgListAdapter m_orgListAdapter; // 0x60
	private MatListAdapter m_matListAdapter; // 0x68
	private Act13sideDailySearchViewModel m_model; // 0x70
	private Action`1 m_onOrgSelected; // 0x78
	private Action`1 m_onMatSelected; // 0x80
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x343f368 VA: 0x7595a57368
	public Void Init(Action`1 onOrgSelected, Action`1 onItemSelected) { }
	// RVA: 0x343f404 VA: 0x7595a57404
	public override Void OnValueChanged(Act13sideDailySearchProperty property) { }
	// RVA: 0x343f758 VA: 0x7595a57758
	private Void _InitIfNot() { }
	// RVA: 0x343f9a4 VA: 0x7595a579a4
	public Void .ctor() { }
}
```