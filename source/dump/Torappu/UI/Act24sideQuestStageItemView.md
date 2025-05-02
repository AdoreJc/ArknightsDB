# Act24sideQuestStageItemView

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _bgNormalGo`

- `GameObject _bgNormalSelectGo`

- `GameObject _bgDragonGo`

- `GameObject _bgDragonSelectGo`

- `RectTransform _rtInfo`

- `Single _unselectOffset`

- `Single _selectOffset`

- `Text _textStageName`

- `Color _colorStageNameNormal`

- `Color _colorStageNameHighlight`

- `UIAtlasImage _imgQuestIcon`

- `UIAtlasObject _atlasQuest`

- `String _iconNormalName`

- `String _iconNormalSelectName`

- `String _iconHardName`

- `String _iconHardSelectName`

- `SimpleLayoutContent _rankList`

- `GameObject _newFlagGo`

- `Act24sideQuestStageItemModel m_questItemModel`

- `Boolean m_isSelect`

- `UIStateFinder m_stateFinder`

- `Boolean m_hasInited`

- `RankListAdapter m_rankListAdapter`


## Methods

- `Void Render(Act24sideQuestStageItemModel, Boolean)`

- `Void _InitIfNot()`

- `String _GetSpriteName(Boolean, Boolean, Boolean)`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class Act24sideQuestStageItemView : MonoBehaviour, IHotfixable
{
	private GameObject _bgNormalGo; // 0x18
	private GameObject _bgNormalSelectGo; // 0x20
	private GameObject _bgDragonGo; // 0x28
	private GameObject _bgDragonSelectGo; // 0x30
	private RectTransform _rtInfo; // 0x38
	private Single _unselectOffset; // 0x40
	private Single _selectOffset; // 0x44
	private Text _textStageName; // 0x48
	private Color _colorStageNameNormal; // 0x50
	private Color _colorStageNameHighlight; // 0x60
	private UIAtlasImage _imgQuestIcon; // 0x70
	private UIAtlasObject _atlasQuest; // 0x78
	private String _iconNormalName; // 0x80
	private String _iconNormalSelectName; // 0x88
	private String _iconHardName; // 0x90
	private String _iconHardSelectName; // 0x98
	private SimpleLayoutContent _rankList; // 0xa0
	private GameObject _newFlagGo; // 0xa8
	private Act24sideQuestStageItemModel m_questItemModel; // 0xb0
	private Boolean m_isSelect; // 0xb8
	private UIStateFinder m_stateFinder; // 0xc0
	private Boolean m_hasInited; // 0xd0
	private RankListAdapter m_rankListAdapter; // 0xd8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__GetSpriteName; // 0x10
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x20f8df0 VA: 0x7594710df0
	public Void Render(Act24sideQuestStageItemModel questItemModel, Boolean isSelect) { }
	// RVA: 0x20f90dc VA: 0x75947110dc
	private Void _InitIfNot() { }
	// RVA: 0x20f91ac VA: 0x75947111ac
	private String _GetSpriteName(Boolean isHard, Boolean isSelect, Boolean isDragon) { }
	// RVA: 0x20f9324 VA: 0x7594711324
	public Void EventOnItemClick() { }
	// RVA: 0x20f9478 VA: 0x7594711478
	public Void .ctor() { }
}
```