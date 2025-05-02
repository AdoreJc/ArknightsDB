# Act13sideDailyMissionReplaceView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `SimpleLayoutContent _boardItemList`

- `Act13sideDailyReplaceItemView _itemTemplate`

- `RectTransform _candidateContainer`

- `Button _btnReplace`

- `Text _textAgenda`

- `Text _textAgendaMax`

- `Color _hintColor`

- `Boolean m_hasInited`

- `String m_actId`

- `Act13SideData m_actData`

- `Adapter m_listAdapter`

- `Act13sideDailyReplaceItemView m_candidateView`

- `Act13sideDailyReplaceViewModel m_model`


## Methods

- `Void _InitIfNot()`

- `Void Init(String, Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyMissionReplaceView : DataBinder`1
{
	private SimpleLayoutContent _boardItemList; // 0x20
	private Act13sideDailyReplaceItemView _itemTemplate; // 0x28
	private RectTransform _candidateContainer; // 0x30
	private Button _btnReplace; // 0x38
	private Text _textAgenda; // 0x40
	private Text _textAgendaMax; // 0x48
	private Color _hintColor; // 0x50
	private Boolean m_hasInited; // 0x60
	private String m_actId; // 0x68
	private Action`2 m_onItemSelect; // 0x70
	private Act13SideData m_actData; // 0x78
	private Adapter m_listAdapter; // 0x80
	private Act13sideDailyReplaceItemView m_candidateView; // 0x88
	private Act13sideDailyReplaceViewModel m_model; // 0x90
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x343e504 VA: 0x7595a56504
	public override Void OnValueChanged(Act13sideDailyReplaceProperty property) { }
	// RVA: 0x343e794 VA: 0x7595a56794
	private Void _InitIfNot() { }
	// RVA: 0x343ef0c VA: 0x7595a56f0c
	public Void Init(String activityId, Action`2 onItemSelectAction) { }
	// RVA: 0x343efc4 VA: 0x7595a56fc4
	public Void .ctor() { }
}
```